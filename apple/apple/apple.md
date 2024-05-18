[과제 구현 영상]



<img width="50%" src="https://github.com/chlyun/homework/assets/119630708/9a3de5b5-7f5e-472c-89e5-54e05494e27b.gif"/>

마크업
====================
a태그인 링크태그에 aria label을 활용하여 스크린리더가 읽어줄때 버튼의 상세설명을 붙혀줌

그림판으로 살짝 그려보고시작한 사진 첨부해봅니다..


<img width="50%" src="https://github.com/chlyun/homework/assets/119630708/c6be4601-6e5a-4fe0-9f83-09bea6b32e4f"/>




카드 컴포넌트
====================
display grid를사용해 그리드 contents 들인  h2,sub-head,d-day,more-informaiton을 align-content: start; 로 시작점 정렬하고 text-align: center;로 가운데 정렬해주었음  gap을주어   h2,sub-head,d-day,more-informaiton 간의 간격을 발생시킴

more-informaiton에 flex속성을 넣어 기본값인 row 속성을 이용해 옆으로 배치하과 justify-content:center; 로 가운데 정렬해주고 gap을이용해 버튼간의 사이 간격을 넣어줌

@media 속성을 이용해서 1024이상의 사이즈가되면 font size와 줄바꿈인 br 태그의 newline 클래스명을 이용새 display:none으로 줄바꿈을 없애줌  

레이아웃
===================
section 태그를이용해 2개의 섹션인 main-items, sub-items 들에게 grid속성을 부여 main-items 같은경우 columns를 화면비율이 커져도 나눌일이없음 sub-items같은경우 1024이상의 사이즈가되면 columns가 1대1 비율로 2개로 나눠지게 설계해둠 

각각의 그리드 콘텐츠들 안에 card의 배경이미지를 설계 cover을 사용하여  지정한 요소를 빈틈없이 다 덮을수있도록 확대/축소를 위해 넣어줌 그리고 no-repeat를 사용해 반복없음으로 설정 position을 이용해 가운데 화면이 보일수있도록 50% 높이 조절을위해 높이값도 50%로 할당해줌   

그리고 container 쿼리를 이용하여 type은 inline size 로 width값에따라 반응형동작하도록 설계후 1024이상의 크기가 할당되었을경우 이미지를 한층더 고해상도인 이미지로 교체해주었다.



어려웠던점
========================

background속성을 이용해 이미지를 주었을때 레이아웃 위치를 잡는곳에서 조금 시간을 많이쓴거같다 

나중에 img 태그를이용해 설계해볼예정!
