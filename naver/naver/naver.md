모바일퍼스트방법
=============================================
@media 구문을 이용해서 모바일기준 768미만 데탑기준 768최소값을 할당해줘서 768보다 커질경우 미만일때 display:none; 으로 감춰둔 ip_security부분을 display flex로 다시 활성화 해줌

매우 오래걸렸고 어려웠던 부분
=============================================
ip보안 on/off 버튼 부분만드는곳에 시간투자를 많이했습니다 checkbox를 이용해 구현해봤는데 글씨 on/off로 나타내기위해 label값에 가상요소를 사용하여 befor구문에 OFF를 할당해두어 가장 초기에보이는값으로 만들어두고 after 구문에  off가 같이 나타나지않에 content를 빈칸으로 둠 그리고 input:checked + label::before 을 이용하여 체크박스와 label에 체크가들어오면 on이 표시되도록 설정


해결하지 못한 부분
=============================================
label이 focus 할당받지못해서 키보드로 on off 제어가 되지않았지만 일단 화면에 보이는건 input요소를 투명으로한후 label on/off쪽에 투명칸을만들어주어 키보드로 할당할수있는것처럼 표기해둠  임시로 해뒀지만 방법을 찾지못하겠습니다 ㅠ


수정사항
=============================================
- 마크업
    - ~~로고를 <h1> 요소로 제공하는 것이 적절.~~
    - ~~<picture>, <source>, <img> 요소를 사용하여 로고를 마크업 하고 네이버 홈으로 연결되도록 하이퍼 링크를 추가할 것.~~
    - ~~대체 텍스트는 “네이버” 또는 “Naver”가 적절함~~
    - ~~아이디, 비밀번호 등 <label> 요소에 레이블 텍스트가 제공되지 않음.~~
    - ~~로그인 버튼과 로그인 상태 유지 영역의 마크업 순서가 변경되는 것이 바람직 함.~~
    -~~로그인 버튼에 tabindex=”-1”을 제공하여서는 안됨.~~
    - ON/OFF 체크박스가 컴포넌트 단위로 묶여서 관리되지 않음.
    - ~~<a> 링크가 새창으로 열릴 경우 rel="noopener noreferrer”를 함께 명시하는 것을 추천함.~~
- 스타일링
    ~~- 변수를 사용하지 않은 점이 아쉬움~~
    - 컴포넌트와 레이아웃을 분리하여 작성하는 것을 고민해 보기 바람.
- 과제 구현 과정에 대한 설명
    - ~~마크다운이 간결하게 잘 작성되어 있네요. 다만 중간에 설계 과정이나 구현과정이 좀 더 상세하게 기록되었더라면 하는 아쉬움이 남아요.~~
    -~~ 과제 구현 시 해결하지 못한 부분은 수업 시간에 함께 고민해보고 문제를 해결해 보기로 해요.~~

====================================
    컴포넌트에 대한 이해부족 찾아보자