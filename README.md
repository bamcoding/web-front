# web-front
## CSS essential contents
### 1. 기본 선택자
1. 전체 선택자 
2. 태그 선택자
3. 클래스 선택자
4. ID 선택자

### 2. 복합선택자
1. 일치 선택자 (EF)
2. 자식 선택자 (E > F)
3. 후손 선택자 (E F)
4. 인접 형제 선택자 (E + F)
5. 일반 형제 선택자 (E ~ F)

*중복 선언 시 주의사항
1. 명시도 점수(상속[none],전체[0],태그[1],클래스[10],ID[100],인라인[1000] 선택자)
2. 마지막 선언으로 적용
3. 중요도 (!improtant)

### 3. 가상요소 선택자(:)
1. hover
2. active
3. focus
4. first-child
5. last-child
6. nth-child

*xxx-child 주의사항
1. .content p:nth-child(1)는 contents 클래스의 전체 후손 중에 p태그의 첫번째 요소이다.
2. 위 선언문은 아래 상황에서 동작하지 않는다
~~~
<div class=".content">
  <div>1</div>
  <p>2</p>
</div>
~~~
3. 기본 선택자 없이 사용 가능하므로 위와 같은 사례에 유의한다.

















