# homework
테킷 프론트엔드스쿨 10기 과제 저장소

float를사용한 방법
========================
avater를 왼쪽에서 오른쪽으로 ->정렬시키기위해 float:left태그를 이용했고 온라인과 오프라인 구별을 위해 avater_gray태그하나 avater_green 태그를 따로만들어줌 absoulte를 이용한이유는 absoulte 를 이용하면 가장 가까운 포지션이있는 부모요소를 기준으로 배치한다고 배운거같아서 avater태그기준으로 위치를 잡기위해 avater 태그안에 온/오프라인을 넣어둠 top과 left를 이용해 위치를 잡아줬다  

즉 avater_gray,green은 avater을 기준으로 기준점을 잡고 움직임

max-width와 min-width를 사용한이유는 화면이 넓어지든 좁아지든 한줄에 4개를 유지하기위해 넣어줌

flex를 이용한방법
=========================
display속성을 이용해 flex contanier를 정의하고  flex flow를 이용해 row 왼쪽에서 오른쪽으로 표시 float left와 비슷함을 이용 그리고 wrap를 준이유는 nowrap은 한줄에표시 wrap를 이용해서 여러줄묶음으로 만듬 
order을 이용해서 man값을 -1로 앞으로당기고woman값을 1로줘서 뒤로미룸 여기서 woman 1은 굳이안줘도 되지만 써보려고 줘봤다 그리고 만약 wrap 줄바꿈에서 wrap-reverse를 주면 order을 굳이 사용할필요없이 반대로 나타났을거같다



수정본
==============================================
