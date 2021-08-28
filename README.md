# web-front
## CSS essential contents
### 1. 기본 선택자
- 전체 선택자 
- 태그 선택자
- 클래스 선택자
- ID 선택자

### 2. 복합선택자
- 일치 선택자 (EF)
- 자식 선택자 (E > F)
- 후손 선택자 (E F)
- 인접 형제 선택자 (E + F)
- 일반 형제 선택자 (E ~ F)

*중복 선언 시 주의사항
- 명시도 점수(상속[none],전체[0],태그[1],클래스[10],ID[100],인라인[1000] 선택자)
- 마지막 선언으로 적용
- 중요도 (!improtant)

### 3. 가상요소 선택자(:)
- hover
- active
- focus
- first-child
- last-child
- nth-child

*xxx-child 주의사항
- .content p:nth-child(1)는 contents 클래스의 전체 후손 중에 p태그의 첫번째 요소이다.
- 위 선언문은 아래 상황에서 동작하지 않는다
<div class=".content">
  <div>1</div>
  <p>2</p>
</div>
- 기본 선택자 없이 사용 가능하므로 위와 같은 사례에 유의한다.

















