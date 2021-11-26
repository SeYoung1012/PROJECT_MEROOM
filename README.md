# PROJECT_MEROOM
# 3차 프로젝트
### 1.소개
   - 비트캠프 3차 프로젝트 진행(2021-11-02 ~ 2021-11-23(22))
   - 프로젝트 명 : 미룸
   - 프로젝트 선정이유 : 제주도로 국내 여행을 떠난 여행객들을 위해서 제주도를 기반으로 한 기업들과 상생해서 프로모션과 이벤트를 제공하며,<br>
   여행을 편하게 즐길 수 있는 숙소와 액티비티와 원데이 클래스로 제주도의 문화와 추억을 쌓을 수 있게 해주는 서비스의 사이트

   - 팀원(역할) :  김세영(메인페이지/고객센터) - 답변하기, 뉴스 ,이벤트, 프로모션 게시판, 1:1문의 기능<br>
　　　　　&nbsp;손설빈(원데이클레스/예약) - 원데이 클레스 소개, 예약, 결제 , 환불 관련 기능<br>
　　　　　&nbsp;박상민(객실/예약) - 객실정보 소개, 객실 예약, 결제, 환불, 리뷰조회 기능 <br>
　　　　　&nbsp;조남규(주변소개/부대시설) - google map을 활용한 주변소개, 부대시설 소개 <br>
　　　　　&nbsp;종대의(관리자 페이지) - 각 페이지에 대한 CRUD 기능 처리와 통계기능 종합 <br>
　　　　　&nbsp;최무늬(로그인/회원가입/마이페이지) - 기본 로그인,회원가입(kakao,naver api)포함,<br>
　　　　　&nbsp;마이페이지 회원정보, 적립금, 리뷰 기능 구현<br>         
<br><br>               
### 2.소스코드
  * [model](/final-project/tree/main/MeRoom/src/main/java/com/spring/mr/vo/) &nbsp;,&nbsp; (/final-project/tree/main/MeRoom/src/main/java/com/spring/mr/service/)
  * [view](/final-project/tree/main/MeRoom/src/main/webapp/views/)
  * [controller](/final-project/tree/main/MeRoom/src/main/java/com/spring/mr/controller/)
  * [sql](/final-project/tree/main/MeRoom/sql/)
<br><br>
### 3.구현ERD
![구현ERD](https://user-images.githubusercontent.com/68181461/138590422-93e5e9f0-af55-49e2-a067-eeaf578b758a.png)
<br><br>

### 4. 사용기술
  * (서버기술) : Spring, Mybatis, Apache Tomcat 9.0, Java , Maven, JSP, JSTL
  * (화면기술) : HTML5,. CSS3, JavaScript, JQuery, JSP, Aajx
  * (데이터 베이스) : oracle
  * (사용API) : KAKAO MAP, i'mport, JSCalender, Google Developers, KAKAO Developers, Naver DEvelopers, Coolsms<br>
          Summernote, SMTP 
### 5.실행결과

-메인 화면
![MeRoomMain](https://user-images.githubusercontent.com/87887586/143540958-6ddf2789-5a81-4c57-8c3f-9132f4cd1368.gif)

-어바웃(오시는 길)
![MeRoomIntroduce](https://user-images.githubusercontent.com/87887586/143541512-5b6998ff-e535-4220-a61a-b028a04f520b.gif)

-일대일 문의(유효성검사)
![question](https://user-images.githubusercontent.com/87887586/143542069-4e73413e-4bee-47fa-88c5-85a763f893bf.gif)

-자주묻는 질문
![fa](https://user-images.githubusercontent.com/87887586/143542928-fe5858d7-399a-4493-89b1-1013ea0ceafa.gif)

-뉴스 게시판
![newslist](https://user-images.githubusercontent.com/87887586/143544451-bea743c7-09e2-485d-9a5b-a12ff8871342.png)

![newsdetail](https://user-images.githubusercontent.com/87887586/143544460-987c56b1-d211-4c4f-ac59-2cd6b797834d.png)

![newswrite](https://user-images.githubusercontent.com/87887586/143544467-b9c7e965-0dc1-474d-a98f-b123afa2734c.png)

-이벤트 게시판

![eventlist](https://user-images.githubusercontent.com/87887586/143544613-fc2a3d86-9c2d-4fd9-b43a-36edcab2da93.png)
![eventdetail](https://user-images.githubusercontent.com/87887586/143544622-985dbac6-b863-4935-8a0e-f4842695ce7f.png)
![eventwrite](https://user-images.githubusercontent.com/87887586/143544648-1e967c99-bd3f-4b93-991d-d85770fccfad.png)

-프로모션게시판
![promotionlist](https://user-images.githubusercontent.com/87887586/143544738-056f39b1-6a3e-4cfa-be46-f07357a1de5c.png)
![promotiondetail](https://user-images.githubusercontent.com/87887586/143544760-47705177-5be6-4968-a94a-b73f746e9bc2.png)
![promotionwrite](https://user-images.githubusercontent.com/87887586/143544767-74895acb-2251-49b1-800c-a87ae29cfb43.png)
