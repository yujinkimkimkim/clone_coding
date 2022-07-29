# clone_coding1

<마지막!!>
1. 회색으로 덮이기 전에도 글씨 있게 하기
2. 회색 박스 안에 있는 사진들에 글씨랑 시간 추가하기
3. margin: outo 해서 가운데 정렬하기
4. 아래에 글씨 많은 곳도 하기
5. width 넉넉하게 줘서 문장 안 넘어가게 하기
6. 제품이랑 선물추천 칸도 구현 조금 되어있습니다!

<3주차!!>
1. 회색으로 사진 덮이면서 설명 나오는 거
2. 검색 그림 누르면 창 나오게 해보기
3. 제품이랑 선물추천 창 만들기
4. 버튼 그림들 수정


<피드백 1 : 파일 분리하기>
![image](https://user-images.githubusercontent.com/105366292/178192763-246c6fa6-8e2c-4a01-ba5e-d730e4d60594.png)

-css랑 html 파일 분리

-image 파일 만들어서 사진들 다 안에 넣었습니다!

<피드백 2 : 박스들 위치 억지로 조정하지 않고 박스 안에 박스 넣고 해서 체계적으로 하기>
![image](https://user-images.githubusercontent.com/105366292/178192819-2195dd6e-f781-4c65-ae03-315c65262b54.png)
(html 사진)

사진 한 개 있는 div랑 사진 두 개 있는 div를 큰 div 안에 넣어서 그 div를 더 큰 div 안에 넣는 구성으로 다시 바꿨습니다!
![image](https://user-images.githubusercontent.com/105366292/178192901-c41a8803-daa3-4d69-9dc5-8c66ed5078b3.png)
![image](https://user-images.githubusercontent.com/105366292/178192953-b36a2ee7-7b28-474a-8e55-d4d008fceb88.png)

css 입니다! gray_box 안에 display: flex 빼야하는데 깜빡했습니다
마지막에 더 큰 div(gray_box)가 회색 배경이 되고 두 div를 갖고 있는 div(grays)한테 margin을 줬습니다!
두 개 사진 들은 div(gray1_2)은 display : flex로 하되 flex-direction: column를 써서 아래로 정렬되게 했습니다!
두 div를 갖고 있는 div(grays)는 display : flex 만 했는데 이유가 저것만 쓰면 자동으로 row로 맞춰져서 안썼습니다!

<2주차 피드백>
1. hover 했을 때 회색으로 덮어지게 하는 거
2. 다다일상 기록도 슬라이드 형태로 만들기
3.버튼들 디자인 바꾸기

<더 수정한 내용>
1.이미지들 슬라이드 배너 오류 수정 및 추가
2. 메인 화면 글씨 추가

<개선할 점>
1. hover 했을 때 아래에서 위로 올라오는 애니메이션 형태로 되게 하기
