body {
    margin: 0;            /* 바디 파트의 마진을 0으로(없게) 설정한다 */
    background-color: #100c0d;
}


a {
    text-decoration: none;  /* 텍스트에 추가되는 줄 이펙트를 없앰 / 근데 여기에 쓴 a가 뭔지 모르겠음 -> 뭔지 알았음 ㅋㅋ ㅈ밥쉑 */
    /* color: #100c0d;  흠 글자 색인거같긴한데 전체가 다 바뀜, 하나씩 바꿀수는 없나 */
}






.DraftMaster_bar {   /* .다음 이름 붙인게 html에서 그 구문을 건드린다는 뜻인거같음 */
    background-color: #f8f2ef;  /* 바 배경 색 결정 */
    display: flex;   /* 가로 정렬로 보이게 바꿈 */
    align-items: center;  /* 상하 위치를 중간으로 정렬, 아이템마다 다르게 할려면 어떻게 하지? 로고를 살짝 위로 두고싶은데 align-self를 써야하나 <- 어케쓰는지 잘 모르겠다 */
    justify-content: space-between; /* 좌우 정렬, 근데 딱 정렬 느낌이라 원하는 위치에 두고싶음 / 다른 방법 써야할듯? 근데 나한테 있는 옵션이 없음 */
    padding : 8px 12px;  /* 바 여백 결정 */
}





.DraftMaster__logo {
    font-size: 20px;
}

.leftlogo {
    color:#100c0d;
}





.DraftMaster__menu {
    /* color: #100c0d;  'hover'전 상태일때 폰트 색을 바꾸고싶었는데 안되는듯? */
    display: flex;
    list-style: none;  /* 앞에 붙어있던 점 없애줌 */
}

.DraftMaster__menu li {
    box-sizing: content-box;
    width:;
    height:;
    padding:0px;
    border:3px solid #151520;
    border-radius: 4px;

    margin: 0px 3px;
    width:80px;
    height:40px;
    text-align: center;
    justify-content: center;
    padding: 8px 15px;  /* 메뉴안의 리스트당 패딩을 결정해줌 */
    background-color: #f8f2ef;
}

.menu_list {
color: #100c0d;
}


.menu_list:hover {
    color:#f8f2ef;/* 아래 폰트 색 안바뀌는거 건드려봤는데 이걸로 바꿀수있었음 ㅋㅋ 근데 로고는 빼고싶은데 어케하는거지  뭔가 하나씩 html에서 파트를 나눠서 해줘야하는건가 */
}


.DraftMaster__menu a:hover {
    /* 메뉴안의 리스트에 '어떤행위' 를 했을 때 상태를 지정/ 현재는 'hover'상태를 지정 */
    background-color: #151520;
    color :#f8f2ef;  
    /* 'hover'상태일때 폰트 색을 바꾸고싶었는데 안되는듯 */
    /* border-radius: 4px; */
}
