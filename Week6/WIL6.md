WIL6 ------------------------

Box model과 FLEX Box

5주차 리뷰 

---상속순위 !!---

겹치는 경우에는 순위가 높은애가 높아짐

\1) 사용자 스타일 (컴퓨터 사용자)

\2) 제작자 스타일 (개발자=나)

가. !important ( red !import )

나. 인라인 스타일 - 인라인 선택자 (태그 안에 구체적으로 적용하는것)ex) 전체선택자가 오렌지고 인라인 선택자가 

다. id 스타일 - id 선택자( # )

라. 클래스 스타일 - 클래스 선택자 ( . )

마. 타입 스타일- 타입 선택자

-와일드카드 -- 전체 선택자( \* )

\3) 브라우저 기본 스타일 (개발자가 스타일 적용 안했을 경우를 대비하기 위해 )

본수업 !!!!!!!!!!!!!!!

박스의 테두리 -> border 

solid 진한 선

BOX MODEL--top > right > bottom > left 순서대로 적용.(padding, margin) or top&bottom > left&right 순서로 적용 가능 . 

1\. 블록 레벨 요소-- > 한 줄을 차지하는 박스

div, p , h 등등 부모요소의 전체공간 차지 

2\. 인라인 레벨 요소-- > 자신만을 감싸는 박스

padding(패딩의 오리털) - 컨텐츠(내몸)와  border(겉감) 사이의 간격 

margin(다른 패딩 입은 사람과의 거리, border 로부터 다른 컨텐츠 사이의 여백) -  


FLEX BOX LAYOUT

->flexible layout 아이템이 배열될 방향인 '주축'을 정할 수 있다! 

justify-content : main axis - row 저주 콘서트 주축(암기팁)

align-items : cross axis - column 크로스 라인 수직축(암기팁)

TMI)css grid layouts

`    `can i use ?--어느버전에서 어떤걸 쓸 수 있는지(지원하는지) !!
