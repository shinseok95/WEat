# WEat 프로젝트<br>

<img src="https://user-images.githubusercontent.com/48644958/107149630-f91a5800-699c-11eb-8bb7-f7e84ad5bb46.png" height="50%" width="50%"></img><br>

## 소개

### 행사 소개

- 2020 제 4회 SW중심대학 오픈해커톤 **[한국정보처리학회장상 수상작]**<br><br>
  - 소개 : 40개교 SW중심대학 출신의 개발자 4인, 디자이너 1인이 한 팀을 이뤄, 2박 3일간 오픈소스 프로젝트 기획, 개발, 구현, 협업하는 해커톤 행상입니다.<br>
  - 주제 : 디지털뉴딜을 위한 소프트웨어의 도전<br>
  - 주최 : 과학기술정보통신부<br>
  - 주관 : 정보통신기획평가원, SW중심대학협의회<br><br>
  
### 앱 소개
  
- 배달 주문 공유 플랫폼<br><br>
  - 배달 앱들의 높은 최소 주문 금액 및 배달팁을 해결하기 위한 **배달 주문 공유 플랫폼**입니다.<br>
  - GPS 기반으로 자신 위치 주변에 비슷한 주문을 하려는 사용자들을 매칭 시켜주는 서비스를 제공합니다.<br>
  - 주문을 공유하려는 사용자가 게시글을 업로드하면, 관심이 있는 사용자가 이에 댓글을 달아서 연결되는 방식입니다.<br><br>

## 사용 기술

<img src="https://user-images.githubusercontent.com/48644958/107149190-988a1b80-699a-11eb-977b-0ae636234ad1.png" height="70%" width="70%"></img><br>

### Client

- Android

### Server

- Firebase Realtime Database

### API

- Googla map API

### Language

- Java
- Kotlin

### Tools

- Android studio
- Window 10
- Git

## Application

### 발표 영상

<img src="https://user-images.githubusercontent.com/48644958/107149664-2f57d780-699d-11eb-801c-fca98410e5b6.png" height="10%" width="10%"></img><br>
> [영상 바로가기](https://www.youtube.com/watch?v=2HP40fnlzMI&feature=youtu.be)


<img src="https://user-images.githubusercontent.com/48644958/107150530-92e40400-69a1-11eb-89ca-383c9a87910f.png" height="30%" width="30%"></img><br>
  
 ### 스플래시 & 로그인
 
- 앱 실행시 보이는 Splash screen입니다. <br><br>

<img src="https://user-images.githubusercontent.com/48644958/107149710-8067cb80-699d-11eb-91df-3cae330b382e.png" height="30%" width="30%"></img><br>

- Firebase에서 제공하는 authentication과 연동하여 Gmail로 로그인이 가능합니다.<br>
- 로그인시, 닉네임을 설정할 수 있으며 이는 Shared preperence에 저장되어 사용됩니다.<br><br>

<img src="https://user-images.githubusercontent.com/48644958/107149754-c91f8480-699d-11eb-958e-ec2fe1684a88.png" height="30%" width="30%"></img><br>

### 메인 화면

- Google Map API를 사용하여 지도를 표현하였고, GPS 기반으로 현재 자신의 위치를 보여줍니다.<br><br>


<img src="https://user-images.githubusercontent.com/48644958/107149809-20255980-699e-11eb-8a30-70da794b35fb.png" height="30%" width="30%"></img><br>

- 자신의 주변에서 게시된 글을 카테고리별 아이콘으로 구분하여 보여주고, 이를 클릭하면 해당 내용 확인 및 이동이 가능합니다.<br><br>
 

<img src="https://user-images.githubusercontent.com/48644958/107149939-b8234300-699e-11eb-9164-21cda632eed8.png" height="30%" width="30%"></img><br>

### 게시판 화면

- 전체 게시글을 볼 수 있으며, Firebase 서버와 연동하여 실시간으로 게시글이 업로드됩니다.<br>
- 모집이 마감된 게시글의 경우, 글쓴이가 이를 마감처리 할 수 있습니다. <br><br>

<img src="https://user-images.githubusercontent.com/48644958/107149828-44813600-699e-11eb-8539-42439ec31d98.png" height="30%" width="30%"></img><br>

### 게시글 화면

- 사용자가 올린 게시글을 볼 수 있으며, Firebase 서버를 통해 실시간으로 댓글이 입력되는 것을 볼 수 있습니다.<br><br>

<img src="https://user-images.githubusercontent.com/48644958/107149895-8a3dfe80-699e-11eb-89ef-c8cdfd426fba.png" height="30%" width="30%"></img><br>

### 게시글 입력 화면

- 카테고리별로 게시글을 분류하여 작성할 수 있습니다.<br><br>
