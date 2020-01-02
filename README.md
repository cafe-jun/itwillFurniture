<h1><b>Project Info</b></h1>

<img src="/githubimage/projectMain.png" width="850px" height="400px"></img><br/>

*Project Content*
----------------------
<h5>itwillFurniture 저장소는 가구 쇼핑몰 프로젝트를 소스코드 및 프로젝트 실행시 필요한 파일들을 담고 있는 저장소입니다.</h5>
<h5>KAARR KLINT 홈페이지를 모티브로 하여 가구 쇼핑몰을 개발했습니다. 가구 결제/주문 및 그외 공지사항,WishList 등을 구현하였으며 </h5>
<h5>개발기간은 2019-11-16 ~ 12-26 입니다.</h5>
<br/>

*Project technology stack*
-------------------------
<h5>OS : Window 7 </h5>
<h5>WAS : Tomcat 8 </h5>
<h5>Front-End : javascript,Jquery</h5>
<h5>Back-End : Spring framework</h5>
<h5>DB : Oracle DB</h5>
<br/>


*Project developer & role*
----------------------------
* <code>김동철(조장)</code> : <b>Home & 커뮤니티화면,Quick Menu Source 통합(.git) 및 버전관리</b>
* <code>조유록</code> : <b>회사소개/Event Page(List,Detail),My Page(회원정보,결제내역),결제 페이지 구성</b>
* <code>박재선</code> : <b>커뮤니티/결제 화면 Query,Wish List 구현</b>
* <code>신준석</code> : <b>회원가입 & 로그인,지점관리,CartList & 결제 기능 구현</b>
* <code>최효은</code> : <b>제품목록(Living&Bed),List 및 Detail 화면 구성,상품 DB 관리</b>
* <code>박난주</code> : <b>제품 목록(Dining & Deco),List 및 Detail 화면 구성,상품 DB 관리</b>
<br/>


*Project DB ERD (Entity-RelationShop Diagram) Structure*
----------------------------

<img src="/githubimage/projectERD.png" width="850px" height="400px"></img><br/>

* <code>product(deco,livingroom,diningroom,bedroom,event)</code> : 상품 정보 테이블<br/>
<b>ImageIndex : 상품별 이미지 인덱스</b><br/>
<b>projectname : 상품 이름</b><br/>
<b>cate : 상품 대분류 컬럼</b><br/>
<b>cateEn : 상품 소분류 컬럼</b><br/>
<b>price : 상품 가격</b><br/>
<b>saveFileName : 상품이미지경로</b><br>

* <code>fumember</code> : <b>고객정보 테이블</b><br/>
<b>email : 고객이메일</b><br>
<b>pwd : 고객 패스워드</b><br>
<b>name : 고객이름</b><br>
<b>salt : SHA-1 암호화 키 컬럼</b><br>
<b>addr1,addr2,addr3 : 고객 주소</b><br>

* <code>fupayment</code> : <b>구매 정보 테이블</b>
<b>payid : 결제번호</b><br>
<b>email : 주문 고객 email</b><br>
<b>paytype : 결제타입(카드,실시간이체,무통장입금)</b><br>
<b>iamgePath : 구매한 상품 이미지 경로 </b><br>
<b>productInfo : 구매한 상품 정보</b><br>
<b>productEa : 구매한 제품 갯수</b><br>
<b>productPrice : 상품별 개수*가격 </b><br>
<b>delveryMessage : 배송시 메세지 내용</b><br>
<b>buydate : 결제 시간 </b><br>
<b>paydate : 결제 타입</b><br>

* <code>QABoard,Review</code> : <b>질문사항,상품 리뷰</b>
<b>id : 고객 ID </b><br>
<b>Name : 고객 Name</b><br>
<b>subject : 제목</b><br>
<b>content : 내용</b><br>
<b>ipaddr : 접속한 ip</b><br>
<b>created_at : 생성</b><br>
<b>photo : 제품 사진</b><br>
<br/>


*Project Site Structure*
----------------------------

<img src="/githubimage/projectSite.png" width="850px" height="400px"></img><br/><br/>

<li><b>Company</b> : 회사 소개</li>
<li><b>Product</b> : 제품 (Living,Dining,Bed,Deco)</li>
<li><b>Location</b> : 회사 위치</li>
<li><b>QnA</b> : 질문 답변 페이지</li>
<li><b>Event</b> : 회사 이벤트 제품 페이지</li>
<li><b>Member</b> : 회원가입,로그인 등 회원 관련 페이지</li>




