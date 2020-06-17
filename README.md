# 프로젝트 놀먹자(Project_NMJ)

## 주제
  놀고 먹고 자는 매장 정보, 예약, 후기 등 다양한 컨텐츠 공유 플랫폼 제작
  
  A platform for leisure activities' whereabouts, reservation, and review forum.
  
## 기획의도
  '시간을 때우는 사람들'의 고민 놀고 먹고 자는 매장들의 정보를 소비자들에게 제공한다.<br>
  매장은 손쉽게 자신의 정보와 매장의 컨텐츠를 설정 할 수 있는 공간 제공한다.
  
## 사용 기술
 Java, 
 Javascript, 
 Spring MVC, 
 Ajax, 
 API ([Kakao Map](https://apis.map.kakao.com/web), [Daum Postcode](http://postcode.map.daum.net/guide)) , 
 MariaDB, 
 MyBatis, 
 Github, 
 Security, 
 Bootstrap
 
## 역할
 
 - Model, View, Controller전부가 분리되어있는 Spring MVC2모델로 다양한 웹페이지 제작
 - 데이터베이스 설계, 구축(Query작성) 및 시연용 데이터 추가
 - 메인 페이지 Kakao Map Api와 Ajax를 활용하여 현재 위치에서 반경 500m 내 매장 위치 표시
 - 매장회원 가입 / 매장회원 정보 수정 페이지 Daum Postcode Api활용한 주소 및 경위도(xy좌표) 등록
 - Bootstrap html템플릿 활용하여 View페이지 제작
