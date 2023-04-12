# :pushpin: bluemarket
중고거래 웹사이트 블루마켓 프로젝트

</br>

## 1. 제작 기간 & 참여 인원
- 2023년 2월 2일 ~ 3월 20일
- 참여 인원: 4명

</br>

## 2. 사용 기술
#### `Back-end`
  - Java
  - JavaScript
  - Spring MVC
  - Apache Tomcat
  - JSON
  - MySQL
  - JSP
#### `Front-end`
  - kakao-login API
  - kakao-map API
  - FullCalendar API
  - CSS
  
  </br>

## 3. ERD 설계
![블루마켓 ERD](https://user-images.githubusercontent.com/124217957/226547037-100e0921-2144-4a6e-bb82-37a7cf85ea70.PNG)

</br>

## 4. 프로젝트 내에서 주로 맡아서 한 것
- default.jsp 구현
- main.jsp 구현
- 로그인 / 회원가입
- 공지사항, 자주하는 질문
- 각종 게시판(DB와 연동하여 CRUD)
- 웹사이트 내 전반적인 디자인(CSS)
- 게시판 내 sidebar , menu list 등의 기능

</br>

## 5. 프로젝트 내 핵심 기능
중고거래 웹사이트를 제작하기로 기획하였고 구매자와 판매자 간의 중개 기능을 하는 사이트로써  
판매자는 자신이 판매하고자 하는 물품을 등록 할 수 있고 구매자는 원하는 물건의 게시글을 찾으면
블루톡 이라는 메신저 기능으로 판매자와 1:1 대화를 할수 있습니다.
중고거래 특성상 직거래 할 일이 많으므로 지도 API를 활용하여 내 주변의 판매글을 지도 내에서 찾아
볼 수 있게 하였고 달력을 활용해 거래일정 등을 등록해 한 눈에 보기 쉽게 하였습니다.

<details>
<summary><b>핵심 기능 설명 펼치기</b></summary>
<div markdown="1">

### 5.1. 전체 흐름
![블루마켓 프로세스](https://user-images.githubusercontent.com/124217957/226548705-3ae759ca-25b8-4423-becf-38837b07edf5.PNG)


### 5.2. 판매일정

![판매일정](https://user-images.githubusercontent.com/124217957/226549639-c47c7456-5775-4115-9c74-564ca413d924.PNG)


### 5.3. 우리동네 (지도로 보기)

![우리동네](https://user-images.githubusercontent.com/124217957/226549684-9b4622c3-4b45-4b23-ba58-4fc0f9e58071.PNG)


### 5.4. 블루톡 (채팅)

![블루톡1](https://user-images.githubusercontent.com/124217957/226550000-44887955-fbb3-4e82-9473-68af352539f9.PNG)

- **메인페이지에서 블루톡 내역 보기** 
  - 블루톡 클릭 시 채팅방 목록 보여주기. 
    이제까지 대화했던 대화방 목록이 표시되고, 대화한 적이 없었다면 표시하지 않습니다.


![블루톡2](https://user-images.githubusercontent.com/124217957/226550008-75f2162d-43d1-4490-a672-e55e55e1bde3.PNG)

- **판매 또는 구매글에서 해당 판매자와 대화** 
  - 원하는 물품을 클릭하면 해당 물품의 판매요청 또는 구매요청자와 대화가 연결됩니다.


</div>
</details>

</br>

## 6. 마무리하며
팀원들과 협업하여 만들어 본 첫 프로젝트였던 만큼 정말 열심히 해서 만족스러웠지만
지나고나니 아쉬움이 남는 부분이 있었습니다.
