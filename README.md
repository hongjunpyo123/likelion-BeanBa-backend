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
**식자재 전문 거래 플랫폼 BeanBa**는 자취생, 1인 가구를 대상으로 구매후 남은 식자재를 판매하거나 필요한 만큼 식자재를 거래할 수 있는 플랫폼 입니다.
CLEARPLATE 는 아래와 같은 목적으로 시작하였습니다:

- 남기고, 버리고, 잊는 것이 너무 자연스러워진 우리의 식습관! 이것을 바꿔볼 수는 없을까?
- 음식을 남김없이 먹는 것에 '재미' 와 '보상' 을 더해 지속 가능한 행동을 유도할 수 있지 않을까?
- 어떻게 하면 음식을 판매하는 소상공인들을 우리 서비스에 끌어들일 수 있을까?

이러한 문제점들을 해결하기 위해, CLEARPLATE는 외식 상황에서 완식률을 AI로 분석하여 환경 실천을 리워드로 보상하는 플랫폼을 제공합니다.
사용자는 식사 전후 사진을 업로드하고 AI 기반 완식률을 분석하여 도장 및 포인트 적립을 통해 환경 보호를 실천할 수 있습니다
또한 완식을 달성한 매장에서는 도장이 부여되며 이를 통해 쿠폰을 교환하고 해당 매장의 재방문률을 높이는 결과를 얻을 수 있습니다


---
## 주요 기능
CLEARPLATE는 다음과 같은 주요 기능을 제공합니다:
1. QR 기반 식당 인증 - QR 코드를 통해 제휴 매장을 확인하고 위치를 인증합니다. 이용자가 해당 매장에 방문하였는지 확인하는 기능입니다.(악용 방지 장치)
2. AI 기반 완식률 분석 - 식사 전후 사진을 서비스에 업로드하면 AI가 완식률을 계산하고 퍼센트로 알려줍니다. 먹기 전과 먹은 후의 사진을 대조하여 악용을 방지하고 정확도를 올리는 방식으로 동작합니다.
3. 리워드 시스템 - 80% 이상 완식 시 도장과 포인트를 지급합니다. 도장 5개 수집 시 매장 할인 쿠폰을 제공하여 재방문을 유도하고, 포인트로는 환경 단체 기부나 CLP 굿즈 구매가 가능합니다.
4. 기록 및 분석 - 개인별 완식률, 주간 분석 등을 제공하여 사용자의 환경 실천 현황을 시각화합니다. 지속적인 동기부여를 위한 개인 맞춤형 피드백을 제공합니다.
5. 사회적 가치 연결 - 개인의 작은 실천이 환경 보호와 경제 활성화로 연결되는 구조를 통해 사회적 가치를 실현합니다.


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

### 로컬 환경에서 실행
1. 레포지토리 클론
```bash

```

2. application.yml 설정
```bash

```

3. 프로젝트 빌드 및 실행
```bash

```

---

현재 서비스는 해커톤 이후로 중단되었습니다.

### 스크린샷
| 기능 | 화면 |
|------|------|
| **앱 아이콘 & 로그인** | <img width="2048" height="2048" alt="BeanBa_logo" src="https://github.com/user-attachments/assets/1f3a9d81-c514-47b1-89c4-595dc2a39efa" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 17 39" src="https://github.com/user-attachments/assets/f11aee5a-8f07-4f1a-8ea7-c5c763ff4b0f" /> |
| **메인 화면** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 18 31" src="https://github.com/user-attachments/assets/6f5ffcad-2e38-421a-b551-a7f6d1383880" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 19 25" src="https://github.com/user-attachments/assets/be52900b-9e7c-4a52-9e8d-b5e204da79a0" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 20 39" src="https://github.com/user-attachments/assets/9216bfe3-d13f-45a7-9db3-2412620c13ea" />|
| **상품 보기** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 21 34" src="https://github.com/user-attachments/assets/59918d27-6a97-4caa-8d44-4b84bcd71b8a" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 25 05" src="https://github.com/user-attachments/assets/3a7ce4ee-d424-46e4-a3ed-9bf0f77ec29b" /> <img width="1468" height="322" alt="스크린샷 2025-07-28 오전 10 24 09" src="https://github.com/user-attachments/assets/d826f1b9-a185-4f9d-b85f-1eab85a8e8b9" />|
| **상품 등록하기(판매하기)** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 26 06" src="https://github.com/user-attachments/assets/c1e45940-ae02-40fe-b86a-6642a9e0c523" /> <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 26 52" src="https://github.com/user-attachments/assets/10777dec-67ce-4ed1-b820-6186886e86eb" /> <img width="1468" height="689" alt="스크린샷 2025-07-28 오전 10 27 35" src="https://github.com/user-attachments/assets/a07904d0-e65f-4739-ac62-38d40b0cbb6e" />|
| **식재료 검색** | <img width="1468" height="725" alt="스크린샷 2025-07-28 오전 10 29 07" src="https://github.com/user-attachments/assets/a3071420-104f-44f7-8e3b-67fc89328574" /> <img width="1468" height="633" alt="스크린샷 2025-07-28 오전 10 30 16" src="https://github.com/user-attachments/assets/b6c2d9d7-9483-4f62-bb4b-0a1a33d9ab97" /> |
| **사진 업로드 (완료)** | <img src="https://github.com/user-attachments/assets/7f6b2518-01fc-4f09-9d32-506616527dda" width="150"> |
| **완식률 분석** | <img src="https://github.com/user-attachments/assets/d33d2f56-0367-451b-aff4-f82faaf93655" width="150"> <img src="https://github.com/user-attachments/assets/3eb6df21-c4c5-4425-adbe-cb79e9951568" width="150"> |
| **마이페이지 & 쿠폰함** | <img src="https://github.com/user-attachments/assets/30673109-2c9b-4358-bfe2-710e433c2656" width="150"> <img src="https://github.com/user-attachments/assets/0ccaf618-86d4-40ea-b8cb-f26da449f70" width="150"> |
| **쿠폰 상세 & 포인트 내역** | <img src="https://github.com/user-attachments/assets/b727fe20-f82c-4e4d-8029-9f0e6d2e69b0" width="150"> <img src="https://github.com/user-attachments/assets/d8fd9128-ee26-4c3f-8e18-7314a56eb7b1" width="150"> |
| **포인트 사용 (1)** | <img src="https://github.com/user-attachments/assets/6cf704af-5594-4356-8a57-e05a05c9256f" width="150"> <img src="https://github.com/user-attachments/assets/cd4b0598-e722-437a-b0c5-e0ea1efe3307" width="150"> |
| **포인트 사용 (2)** | <img src="https://github.com/user-attachments/assets/38d0fc06-48f2-45b4-a720-55e6e2006f89" width="150"> <img src="https://github.com/user-attachments/assets/ef756a59-0f16-4d78-82f0-c2de8246a5ba" width="150"> |






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
