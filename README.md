# [프로젝트 놀먹자(Project_NMJ)](https://github.com/chriswpark00/Portfolio_Project_NMJ/issues/1#issue-640304379)

## 주제
  놀고 먹고 자는 매장 정보, 예약, 후기 등 다양한 컨텐츠 공유 플랫폼 제작
  
  A platform for leisure activities' whereabouts, reservation, and review forum.
  
## 기획의도
  '시간을 때우는 사람들'의 고민 놀고 먹고 자는 매장들의 정보를 소비자들에게 제공한다.<br>
  손쉽게 매장의 정보와 매장의 컨텐츠를 설정 할 수 있는 공간을 매장들에게 제공한다.
  
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
 - Kakao Map Api와 Ajax를 활용하여 현재 위치에서 반경 500m 내 매장 위치 표시 (메인 페이지)
 - Daum Postcode Api활용한 주소 및 경위도(xy좌표) 등록 (매장회원 가입 / 매장회원 정보 수정 페이지)
 - 매장회원이 직접 등록한 음식과 방 사진을 Ajax기술로 메뉴 펼치기/접기 와 방사진 보기/접기 구현 (매장 상세 정보 페이지)
 - 이미지파일 입출력 확장자 검증 후 DB저장(.jpg .jpeg .png .gif) (모든 페이지)
 - 매장회원에게 주어진 대부분의 권한 페이지 제작(회원정보 수적, 매장 정보 수정 및 요청, 음식 메뉴 관리)
    - 회원정보 수정
    - 매장정보 수정 및 요청
    - 음식 메뉴 관리 추가/수정/삭제 페이지 제작
    - 각각의 알맞는 정규표현식으로 검증 (이메일, 전화번호, 가격, 사진 등)
 - Bootstrap html템플릿 활용하여 View페이지 제작
