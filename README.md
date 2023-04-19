# Project-Mingle

Project Portfolio: 
https://taehyun-kim.notion.site/Project-Mingle-0686f82c8e4d4f9f85c7677b4b86cc92

App Store Link: 
https://apps.apple.com/kr/app/%EB%B0%8D%EA%B8%80-%EB%82%B4-%EC%9C%A0%ED%95%99%EC%83%9D%ED%99%9C%EC%9D%98-%EC%A2%85%EC%B0%A9%EC%A7%80/id1659655435

Play Store Link: 
https://play.google.com/store/apps/details?id=com.community.mingle&fbclid=PAAab5vGHeNvu2RxNSYQr_6NRwjOK71E5nK6IOZah5eIz5Gd_PI6c9cWWBZ_w

## 소개

> **2022년 12월에 출시한 한인 유학생들을 위한 커뮤니티 어플 프로젝트**
> 

![image](https://user-images.githubusercontent.com/93398875/219706462-708024d1-85e7-4afb-93e7-72cb62ef5094.png)


## 개발 환경

`JAVA` `Spring Boot` `Spring Security` `JPA` `Hibernate` `JWT` `AWS ECS` `AWS RDS` `AWS S3` 
`AWS ElastiCache (Redis)` `AWS Route53` `MySQL` `Gradle` `Swagger 3.0` `Firebase` `Git/GitHub` `GitHub Action` `Docker` `JSON`

## 개발 Timeline

**Vice President** | **Backend Lead** | **Project Manager**

| 2022.06 ~ 2022.08

- Backend 4명, ios 3명, Android 4명, 디자이너 1명으로 이루어진 개발팀을 만들어 프로젝트 진행
- 프로젝트 기획 및 Flow Chart, Wire Frame 설계
- 프로젝트 전반에 걸친 엔티티 설계 및 MySQL 데이터 베이스 테이블 설계
- 게시물 상세 페이지 구현 및 초기 **MVP 모델 대비 응답 속도 최소 500% 이상 감소**
    - 익명 기능 포함 댓글, 대댓글 로직 재설계로 **쿼리문 최소화**
- Spring Security 및 JWT를 이용한 로그인/로그아웃 및 유저 권한 별 접속 제한 기능 개발
    - **4번에 걸친 수정으로** 인증/인가 단계에서 Redis DB 캐싱과 Refresh Token 재발급 로직 변경으로 **토큰 탈취 시 위험성 최소화**
- 댓글 작성 페이지 및 익명 유저 넘버링 로직 개발
- 이메일 인증코드 전송 기능 구현
- AWS ECS와 GitHub Action을 활용한 **무중단 CI/CD 환경 구축**
- **Swagger를 통한 명세서 작성** 으로 프론트 개발자들과 **커뮤티케이션 효율성 증가**
- FCM (Firebase Cloud Messaging)을 이용한 알람 기능 개발
    - 총 12개에 걸친 case 문으로 이루어진 **로직을 개선하여 10줄 이하로 감소**
- 그 외 신고 알고리즘, 인기 글 조회, 마이페이지, 회원가입 기능 등 약 30개이상의 API 개발 및 60개 이상의 API 수정, 최적화
- 페어 코딩과 지속적인 팀원들 간의 미팅을 통한 코드 리뷰 및 피드백으로 전반적인 어플 최적화
