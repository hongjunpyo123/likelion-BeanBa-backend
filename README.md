<img width="657" height="378" alt="스크린샷 2025-07-23 오전 11 25 37" src="https://github.com/user-attachments/assets/70f47569-f40d-43a6-81e7-e356af1ab8dc" /><br>
# 식자재 전문 거래 플랫폼 BeanBa
본 레포지토리는 2025.07.02 ~  2025.07.23 멋쟁이사자처럼 프로젝트 입니다.
## Index

  - [프로젝트 소개](#프로젝트-소개)
  - [주요 기능](#주요-기능)
  - [기술 스택](#기술-스택)
  - [실행 방법](#실행-방법)
  - [데모](#데모)
  - [팀원 소개](#팀원-소개)
  - [프로젝트 구조](#프로젝트-구조)
  - [infra](#infra)
  - [회고](#회고)
---
## 프로젝트 소개
**식자재 전문 거래 플랫폼 BeanBa는 자취생, 1인 가구를 대상으로 구매 후 남은 식자재를 판매하거나 필요한 만큼 식자재를 거래할 수 있는 C2C(개인 간 거래) 중심의 플랫폼입니다.**
BeanBa는 아래와 같은 목적으로 시작하였습니다:

- 대량 구매로 인해 남는 식자재를 판매할 수는 없을까?
- 신선한 식자재를 소량으로 필요한 만큼만 구매할 수 있는 방법은 없을까?
- 개인 간 직접 거래를 통해 중간 유통업체를 거치지 않고 더 합리적인 가격으로 거래할 수 있지 않을까?
- 전문 농가뿐만 아니라 일반 개인도 쉽게 식자재를 판매할 수 있는 플랫폼은 만들 수 없을까?

이러한 문제점들을 해결하기 위해, BeanBa는 개인 간 거래(C2C)를 중심으로 하되 전문 생산자도 참여할 수 있는 열린 식자재 거래 플랫폼을 제공합니다. 
일반 사용자는 남은 식자재를 간편하게 판매하고 필요한 식자재를 소량으로 구매할 수 있으며, 전문 농가나 생산자도 직접 소비자와 거래할 수 있습니다. 
실시간 농산물 가격 정보를 통해 합리적인 거래가 가능합니다.


---
## 주요 기능
BeanBa는 다음과 같은 주요 기능을 제공합니다:
1. 지역 기반 식자재 거래 - GPS 위치 정보를 활용하여 사용자 주변 2km 내 거래 가능한 식자재를 실시간으로 확인할 수 있습니다. 지도 인터페이스를 통해 직관적으로 거래 현황을 파악하고 신선한 식자재의 빠른 거래를 지원합니다.
2. 개인 간 거래(C2C) 중심의 유연한 거래 시스템 - 마트에서 대량 구매한 식자재, 요리 후 남은 재료, 선물받은 식품 등을 개인이 직접 판매할 수 있어 음식물 쓰레기를 줄이고 경제적 효과를 얻을 수 있습니다. 동시에 전문 생산자도 참여하여 다양한 선택권을 제공합니다.
3. 실시간 농산물 가격 정보 제공 - KAMIS(농산물유통정보) API를 연동하여 전국 주요 농산물의 실시간 도매가격을 제공합니다. 개인 판매자와 구매자 모두 시장 가격을 기준으로 합리적인 가격 책정과 구매 결정을 할 수 있어 투명한 거래가 가능합니다.
4. 빠른 게시물 탐색 - ElasticSearch 를 사용하여 빠른 게시물 탐색이 가능합니다.
5. 실시간 채팅 거래 시스템 - WebSocket 기반 실시간 채팅을 통해 판매자와 구매자 간 즉시 소통이 가능합니다.
6. 소셜 로그인 및 신뢰도 시스템 - 카카오, 구글 OAuth2를 통한 간편 로그인과 사용자 신뢰도 평가 시스템을 제공합니다. 거래 후기, 평점, 신고 기능 등을 통해 안전한 거래 환경을 조성하고 신뢰할 수 있는 거래 파트너를 확인할 수 있습니다.


---
## 기술 스택

### 백엔드
- ![Java](https://img.shields.io/badge/Java-17-orange)
- ![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.7.0-green)
- ![JPA](https://img.shields.io/badge/JPA-Hibernate-brightgreen)
- ![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)

### 인프라
- ![AWS](https://img.shields.io/badge/AWS-EC2-orange)
- ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
- ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### 개발 도구
- ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2024.1-purple)
- ![Postman](https://img.shields.io/badge/Postman-API_Testing-orange)

### 협업 툴
- ![Git](https://img.shields.io/badge/Git-2.36-red)
- ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

### 문서화
- ![Swagger](https://img.shields.io/badge/Swagger-API_Docs-green)
- ![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)

  
---
## 실행 방법

### 사전 요구사항
- JDK 17
- Gradle 8.x+
- MySQL 8.0+
- Spring Boot 3.5.3

## 배포된 서비스 접속
현재 BeanBa 프로젝트는 2025.07.28 을 기점으로 배포가 중단되었습니다. ( https://beanba.store )

## 로컬 환경에서 실행
본 프로젝트는 AWS 클라우드 서비스, 외부 api와 밀접하게 연결되어 있어 로컬 실행이 제한적입니다.

필요한 클라우드 서비스:

AWS RDS (MySQL 데이터베이스)
AWS S3 (파일 저장소)
AWS Elasticsearch Service
KAMIS API 키
OAuth2 클라이언트 설정 (카카오, 구글)

---

### 스크린샷
| 기능 | 화면 |
|------|------|
| **앱 아이콘 & 로그인** | <img width="2048" height="2048" alt="BeanBa_logo" src="https://github.com/user-attachments/assets/1f3a9d81-c514-47b1-89c4-595dc2a39efa" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 17 39" src="https://github.com/user-attachments/assets/f11aee5a-8f07-4f1a-8ea7-c5c763ff4b0f" /> |
| **메인 화면** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 18 31" src="https://github.com/user-attachments/assets/6f5ffcad-2e38-421a-b551-a7f6d1383880" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 19 25" src="https://github.com/user-attachments/assets/be52900b-9e7c-4a52-9e8d-b5e204da79a0" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 20 39" src="https://github.com/user-attachments/assets/9216bfe3-d13f-45a7-9db3-2412620c13ea" />|
| **상품 보기** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 21 34" src="https://github.com/user-attachments/assets/59918d27-6a97-4caa-8d44-4b84bcd71b8a" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 25 05" src="https://github.com/user-attachments/assets/3a7ce4ee-d424-46e4-a3ed-9bf0f77ec29b" /> <img width="1468" height="322" alt="스크린샷 2025-07-28 오전 10 24 09" src="https://github.com/user-attachments/assets/d826f1b9-a185-4f9d-b85f-1eab85a8e8b9" />|
| **상품 등록하기(판매하기)** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 26 06" src="https://github.com/user-attachments/assets/c1e45940-ae02-40fe-b86a-6642a9e0c523" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 26 52" src="https://github.com/user-attachments/assets/10777dec-67ce-4ed1-b820-6186886e86eb" /> <img width="1468" height="689" alt="스크린샷 2025-07-28 오전 10 27 35" src="https://github.com/user-attachments/assets/a07904d0-e65f-4739-ac62-38d40b0cbb6e" />|
| **식재료 검색** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 29 07" src="https://github.com/user-attachments/assets/a3071420-104f-44f7-8e3b-67fc89328574" /> <img width="1468" height="633" alt="스크린샷 2025-07-28 오전 10 30 16" src="https://github.com/user-attachments/assets/b6c2d9d7-9483-4f62-bb4b-0a1a33d9ab97" /> |
| **마이페이지** | <img width="1470" height="724" alt="스크린샷 2025-07-28 오전 11 11 13" src="https://github.com/user-attachments/assets/8fbaf8e4-773c-49be-92a3-69e52d44cc80" /> |
| **마이페이지(찜한상품)** | <img width="1470" height="618" alt="스크린샷 2025-07-28 오전 11 12 05" src="https://github.com/user-attachments/assets/116485ee-107d-4e75-8ac5-602a6cde7611" /> |
| **마이페이지(개인정보수정)** | <img width="1470" height="651" alt="스크린샷 2025-07-28 오전 11 13 05" src="https://github.com/user-attachments/assets/ff29d618-0e15-4ecd-9a3a-6c85cdc9b1f6" /> <img width="1470" height="407" alt="스크린샷 2025-07-28 오전 11 13 47" src="https://github.com/user-attachments/assets/cfe4c759-a842-49c3-82bc-3592ce2d2a85" />|
| **마이페이지(내 게시글 보기)** | <img width="1466" height="721" alt="스크린샷 2025-07-28 오전 11 16 43" src="https://github.com/user-attachments/assets/05bc39fc-74e8-4e40-8e88-39cef18066c1" /> |


---
## 팀원 소개

### Frontend Developer
<img src="https://avatars.githubusercontent.com/u/88922405?v=4" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@sm010422](https://github.com/sm010422)
---
### Backend Developer
<img src="https://avatars.githubusercontent.com/u/53433244?v=4" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@hwichoi0317](https://github.com/hwichoi0317)

<img src="https://github.com/hongjunpyo123.png" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@hongjunpyo123](https://github.com/hongjunpyo123)

<img src="https://avatars.githubusercontent.com/u/90876202?v=4" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@kimse2771](https://github.com/kimse2771)

<img src="https://avatars.githubusercontent.com/u/97264463?v=4" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@KwanjungKim](https://github.com/KwanjungKim)

<img src="https://avatars.githubusercontent.com/u/71905358?v=4" width="100" height="100" style="border-radius: 50%;" />

- GitHub: [@Nam-I](https://github.com/Nam-I)


---
## 프로젝트 구조
```bash
beanBa-backend/
├── build/
│   ├── classes/
│   ├── generated/
│   ├── reports/
│   ├── resources/
│   ├── test-results/
│   └── tmp/
├── gradle/
│   └── wrapper/
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── src/
│   ├── main/
│   │   ├── java/likelion/beanBa/backendProject/
│   │   │   ├── BackendProjectApplication.java
│   │   │   ├── admin/
│   │   │   │   ├── category/
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── AdminCategoryController.java
│   │   │   │   │   └── service/
│   │   │   │   │       ├── AdminCategoryService.java
│   │   │   │   │       └── AdminCategoryServiceImpl.java
│   │   │   │   ├── dashboard/
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── AdminDashboardController.java
│   │   │   │   │   └── service/
│   │   │   │   │       ├── AdminDashboardService.java
│   │   │   │   │       └── AdminDashboardServiceImpl.java
│   │   │   │   ├── member/
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── AdminMemberController.java
│   │   │   │   │   └── service/
│   │   │   │   │       ├── AdminMemberService.java
│   │   │   │   │       └── AdminMemberServiceImpl.java
│   │   │   │   └── product/
│   │   │   │       ├── controller/
│   │   │   │       │   └── AdminSalePostController.java
│   │   │   │       └── service/
│   │   │   │           ├── AdminSalePostService.java
│   │   │   │           └── AdminSalePostServiceImpl.java
│   │   │   ├── chatting/
│   │   │   │   ├── config/
│   │   │   │   │   └── JacksonConfig.java
│   │   │   │   ├── controller/
│   │   │   │   │   └── ChattingController.java
│   │   │   │   ├── dto/
│   │   │   │   │   ├── ChattingMessageResponse.java
│   │   │   │   │   ├── ChattingRequest.java
│   │   │   │   │   └── ChattingRoomListResponse.java
│   │   │   │   ├── entity/
│   │   │   │   │   ├── ChattingMessage.java
│   │   │   │   │   └── ChattingRoom.java
│   │   │   │   ├── handler/
│   │   │   │   │   ├── CustomHandshakeHandler.java
│   │   │   │   │   └── StompPrincipal.java
│   │   │   │   ├── repository/
│   │   │   │   │   ├── ChattingMessageRepository.java
│   │   │   │   │   ├── ChattingRoomCustom.java
│   │   │   │   │   ├── ChattingRoomRepository.java
│   │   │   │   │   └── impl/
│   │   │   │   │       └── ChattingRoomCustomImpl.java
│   │   │   │   ├── service/
│   │   │   │   │   └── ChattingService.java
│   │   │   │   └── websocket/
│   │   │   │       └── config/
│   │   │   │           └── WebSocketConfig.java
│   │   │   ├── deploy_health/
│   │   │   │   └── HealthCheckController.java
│   │   │   ├── global/
│   │   │   │   ├── config/
│   │   │   │   │   └── RestTemplateConfig.java
│   │   │   │   ├── exception/
│   │   │   │   │   ├── GlobalExceptionHandler.java
│   │   │   │   │   └── UnauthenticatedException.java
│   │   │   │   └── util/
│   │   │   │       ├── AuthUtils.java
│   │   │   │       ├── FileValidator.java
│   │   │   │       ├── InputValidator.java
│   │   │   │       └── SalePostResponseUtils.java
│   │   │   ├── infra/
│   │   │   │   ├── controller/
│   │   │   │   ├── dto/
│   │   │   │   ├── entity/
│   │   │   │   ├── repository/
│   │   │   │   └── service/
│   │   │   ├── like/
│   │   │   │   ├── controller/
│   │   │   │   │   ├── SalePostLikeController.java
│   │   │   │   │   └── TestSalePostLikeController.java
│   │   │   │   ├── entity/
│   │   │   │   │   └── SalePostLike.java
│   │   │   │   ├── repository/
│   │   │   │   │   └── SalePostLikeRepository.java
│   │   │   │   └── service/
│   │   │   │       ├── SalePostLikeService.java
│   │   │   │       └── SalePostLikeServiceImpl.java
│   │   │   ├── log/
│   │   │   │   ├── entity/
│   │   │   │   │   ├── LoginLog.java
│   │   │   │   │   └── UpdateLog.java
│   │   │   │   ├── repository/
│   │   │   │   │   ├── LoginLogRepository.java
│   │   │   │   │   └── UpdateLogRepository.java
│   │   │   │   ├── service/
│   │   │   │   │   └── LogService.java
│   │   │   │   └── util/
│   │   │   │       └── IpUtil.java
│   │   │   ├── member/
│   │   │   │   ├── Entity/
│   │   │   │   │   └── Member.java
│   │   │   │   ├── auth/
│   │   │   │   │   ├── Entity/
│   │   │   │   │   │   └── Auth.java
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── AuthController.java
│   │   │   │   │   ├── dto/
│   │   │   │   │   │   ├── JwtToken.java
│   │   │   │   │   │   ├── LoginRequest.java
│   │   │   │   │   │   ├── LoginResponse.java
│   │   │   │   │   │   └── RefreshTokenRequest.java
│   │   │   │   │   ├── repository/
│   │   │   │   │   │   └── AuthRepository.java
│   │   │   │   │   └── service/
│   │   │   │   │       └── AuthService.java
│   │   │   │   ├── controller/
│   │   │   │   │   └── MemberController.java
│   │   │   │   ├── dto/
│   │   │   │   │   ├── AdminMemberDTO.java
│   │   │   │   │   ├── MemberRequest.java
│   │   │   │   │   ├── MemberResponse.java
│   │   │   │   │   └── SignupRequest.java
│   │   │   │   ├── email/
│   │   │   │   │   └── service/
│   │   │   │   │       ├── EmailAuthService.java
│   │   │   │   │       └── EmailService.java
│   │   │   │   ├── jwt/
│   │   │   │   │   └── JwtTokenProvider.java
│   │   │   │   ├── repository/
│   │   │   │   │   └── MemberRepository.java
│   │   │   │   ├── security/
│   │   │   │   │   ├── annotation/
│   │   │   │   │   │   └── CurrentUser.java
│   │   │   │   │   ├── config/
│   │   │   │   │   │   └── SecurityConfig.java
│   │   │   │   │   ├── filter/
│   │   │   │   │   │   └── JwtAuthenticationFilter.java
│   │   │   │   │   ├── oauth/
│   │   │   │   │   │   ├── CustomOAuth2User.java
│   │   │   │   │   │   ├── CustomOAuth2UserService.java
│   │   │   │   │   │   └── OAuth2LoginSuccessHandler.java
│   │   │   │   │   └── service/
│   │   │   │   │       ├── CustomUserDetails.java
│   │   │   │   │       └── CustomUserDetailsService.java
│   │   │   │   └── service/
│   │   │   │       └── MemberService.java
│   │   │   ├── mypage/
│   │   │   │   ├── controller/
│   │   │   │   │   ├── MyPageController.java
│   │   │   │   │   └── MyPageTestController.java
│   │   │   │   └── service/
│   │   │   │       ├── MyPageService.java
│   │   │   │       └── MyPageServiceImpl.java
│   │   │   ├── product/
│   │   │   │   ├── S3/
│   │   │   │   │   ├── config/
│   │   │   │   │   │   └── S3Config.java
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── S3Controller.java
│   │   │   │   │   └── service/
│   │   │   │   │       └── S3Service.java
│   │   │   │   ├── controller/
│   │   │   │   │   ├── SalePostController.java
│   │   │   │   │   └── TestSalePostController.java
│   │   │   │   ├── dto/
│   │   │   │   │   ├── AdminSalePostDetailResponse.java
│   │   │   │   │   ├── AdminSalePostSummaryResponse.java
│   │   │   │   │   ├── CategoryRequest.java
│   │   │   │   │   ├── CategoryResponse.java
│   │   │   │   │   ├── PageResponse.java
│   │   │   │   │   ├── SalePostCreateRequest.java
│   │   │   │   │   ├── SalePostDetailResponse.java
│   │   │   │   │   ├── SalePostRequest.java
│   │   │   │   │   ├── SalePostSummaryResponse.java
│   │   │   │   │   └── TopPostSummaryProjection.java
│   │   │   │   ├── elasticsearch/
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   ├── SalePostEsController.java
│   │   │   │   │   │   └── TestSalePostEsController.java
│   │   │   │   │   ├── dto/
│   │   │   │   │   │   ├── ElasticInsertRequestDTO.java
│   │   │   │   │   │   ├── SalePostEsDocument.java
│   │   │   │   │   │   └── SearchRequestDTO.java
│   │   │   │   │   ├── entity/
│   │   │   │   │   ├── repository/
│   │   │   │   │   │   └── SalePostEsRepository.java
│   │   │   │   │   └── service/
│   │   │   │   │       ├── SalePostEsService.java
│   │   │   │   │       └── SalePostEsServiceImpl.java
│   │   │   │   ├── entity/
│   │   │   │   │   ├── Category.java
│   │   │   │   │   ├── SaleCompleteRequest.java
│   │   │   │   │   ├── SalePost.java
│   │   │   │   │   └── SalePostImage.java
│   │   │   │   ├── kamis/
│   │   │   │   │   ├── KamisClient.java
│   │   │   │   │   ├── controller/
│   │   │   │   │   │   └── KamisController.java
│   │   │   │   │   ├── dto/
│   │   │   │   │   │   ├── request/
│   │   │   │   │   │   │   └── KamisSearchRequestDTO.java
│   │   │   │   │   │   └── response/
│   │   │   │   │   │       ├── KamisCodeResponseDTO.java
│   │   │   │   │   │       ├── KamisGetAllResponseDTO.java
│   │   │   │   │   │       └── KamisSearchResponseDTO.java
│   │   │   │   │   ├── entity/
│   │   │   │   │   │   └── Kamis.java
│   │   │   │   │   ├── repository/
│   │   │   │   │   │   └── KamisRespotiroy.java
│   │   │   │   │   └── service/
│   │   │   │   │       └── KamisService.java
│   │   │   │   ├── product_enum/
│   │   │   │   │   ├── SaleStatement.java
│   │   │   │   │   └── Yn.java
│   │   │   │   ├── repository/
│   │   │   │   │   ├── CategoryRepository.java
│   │   │   │   │   ├── SalePostImageRepository.java
│   │   │   │   │   └── SalePostRepository.java
│   │   │   │   └── service/
│   │   │   │       ├── SalePostService.java
│   │   │   │       └── SalePostServiceImpl.java
│   │   │   ├── redis/
│   │   │   │   ├── RedisConfig.java
│   │   │   │   ├── RedisPublisher.java
│   │   │   │   └── RedisSubscriber.java
│   │   │   └── report/
│   │   │       ├── controller/
│   │   │       │   └── ReportController.java
│   │   │       ├── dto/
│   │   │       │   └── ReportRequest.java
│   │   │       ├── entity/
│   │   │       │   ├── Report.java
│   │   │       │   └── ReportKind.java
│   │   │       ├── repository/
│   │   │       │   └── ReportRepository.java
│   │   │       └── service/
│   │   │           └── ReportService.java
│   │   └── resources/
│   │       ├── application-dev.properties
│   │       ├── application-prod.properties
│   │       ├── application.properties
│   │       └── static/
│   │           ├── admin/
│   │           │   ├── adminCategories.html
│   │           │   ├── adminMain.html
│   │           │   ├── adminMember.html
│   │           │   ├── adminReport.html
│   │           │   ├── adminSalePost.html
│   │           │   └── adminSalePostDetail.html
│   │           ├── createPost.html
│   │           ├── getAll.html
│   │           ├── index.html
│   │           ├── js/
│   │           │   └── fetchWithAuth.js
│   │           ├── myPage.html
│   │           ├── pageGetAll.html
│   │           ├── test-sale-post.html
│   │           └── websocket.html
│   └── test/
│       └── java/likelion/
│           ├── beanBa/backendProject/product/kamis/
│           │   └── KamisClientTest.java
│           └── sikjajaeDeal/backendProject/
│               └── BackendProjectApplicationTests.java
├── build.gradle
├── gradlew
├── gradlew.bat
└── settings.gradle
```


---
## infra
<img width="954" height="506" alt="멋사-beanba-인프라" src="https://github.com/user-attachments/assets/43a3e4ae-06f7-49a2-a51f-e66e69491095" />
* Github Action 을 통한 CI/CD 파이프라인을 구축하였습니다.
* Nginx 를 통해 CI/CD 가 동작할 때 마다 Spring (Blue / Green) 서버를 스왑하는 방식으로 무중단 배포를 구축하였습니다.


---
## 회고

### 느낀 점
- 

### 개선할 점
- 
---
<img width="1051" height="592" alt="스크린샷 2025-07-28 오전 10 13 44" src="https://github.com/user-attachments/assets/8fe1973e-fa64-4169-ba70-b6dd5e23b7d9" />
<img width="1051" height="592" alt="스크린샷 2025-07-28 오전 10 14 10" src="https://github.com/user-attachments/assets/180ee191-c637-4b39-b087-927625c1c001" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 50 41" src="https://github.com/user-attachments/assets/405fa701-5121-434d-9fe7-1b274cd04363" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 51 00" src="https://github.com/user-attachments/assets/ffe43a63-793a-4caa-b023-e04427ffaa1a" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 51 16" src="https://github.com/user-attachments/assets/0dc3e87f-46f4-408a-93c7-a8c5f7e93ab1" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 51 30" src="https://github.com/user-attachments/assets/a8cc7568-1496-4b8f-8a48-edaae4b7e421" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 51 45" src="https://github.com/user-attachments/assets/e6058046-2592-40ce-886a-9193b36f250c" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 51 59" src="https://github.com/user-attachments/assets/f6ea12ba-7d10-425a-8025-313dc71ddcf6" />
<img width="1054" height="594" alt="스크린샷 2025-07-28 오전 10 52 12" src="https://github.com/user-attachments/assets/601b9122-29c6-47b6-bd11-9dd00a4893f9" />


