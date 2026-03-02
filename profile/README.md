# 0. Getting Started (시작하기)
```bash
백엔드: gradlew bootRun

앱(Flutter): flutter run
```


<br/>
<br/>

# 1. Project Overview (프로젝트 개요)
- 프로젝트 이름: TalkCoach
- 프로젝트 설명: 면접·발표·일상 대화를 녹음/영상 ****기반으로 분석해 말투·호흡·딕션·억양·표정/시선 안정도와 스크립트 개선안을 제공하는 AI 말하기 코칭 앱

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)
| 구자혁 | 지경태 | 조성빈 | 황요성 | 류호찬 |
|:------:|:------:|:------:|:------:|
| <img src="https://github.com/user-attachments/assets/c1c2b1e3-656d-4712-98ab-a15e91efa2da" alt="구자혁" width="150"> | <img src="https://github.com/user-attachments/assets/c770c42b-4722-4207-a274-e335cb7c2d8c" alt="지경태" width="150"> | <img src="https://github.com/user-attachments/assets/78ce1062-80a0-4edb-bf6b-5efac9dd992e" alt="조성빈" width="150"> | <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="황요성" width="150"> | <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="류호찬" width="150"> |
| BE | BE | BE | FE | FE |
| [GitHub](https://github.com/JaHyeok2002) | [GitHub](https://github.com/JiKyeongtae) | [GitHub](https://github.com/ryuhochan0406) | [GitHub](https://github.com/ryuhochan0406) | [GitHub](https://github.com/ryuhochan0406) |

<br/>
<br/>
_________________________________여기부터 재작성________________________________

<br/>
# 3. Key Features (주요 기능)
- **회원가입**:
  - 회원가입 시 DB에 유저정보가 등록됩니다.

- **로그인**:
  - 사용자 인증 정보를 통해 로그인합니다.

- **AI레시피 추천**:
  - AI를 통해 현재 냉장/냉동고 안에 있는 재료들로 만들 수 있는 간단한 요리를 추천해줍니다.

- **나의 냉장고**:
  - 냉장/냉동고에 재료를 추가합니다.
  - 재료에 대한 정보를 자세히 보여줍니다. (수량, 유통기한, 이미지)
 
- **장바구니**:
  - 마트에서 구입할 재료를 장바구니에 추가 할 수 있습니다.
  - 구매 완료 시 냉장/냉동고에 추가 할 수 있습니다.

- **주변 마트 찾기**:
  - GOOGLE 맵을 사용해 내 위치 주변 마트 위치를 확인할 수 있습니다.

<br/>
<br/>

# 4. Tasks & Responsibilities (작업 및 역할 분담)
|  |  |  |
|-----------------|-----------------|-----------------|
| 구자혁    |  <img src="https://github.com/user-attachments/assets/c1c2b1e3-656d-4712-98ab-a15e91efa2da" alt="구자혁" width="100"> | <ul><li>회원가입, 로그인 구현</li><li>냉장/냉동고 기능 구현</li><li>장바구니 기능 구현</li></ul>     |
| 지경태   |  <img src="https://github.com/user-attachments/assets/c770c42b-4722-4207-a274-e335cb7c2d8c" alt="지경태" width="100">| <ul><li>홈 화면 기능 구현</li><li>AI레시피 추천 기능 구현</li><li>마이페이지 기능 구현</li></ul> |
| 류호찬   |  <img src="https://github.com/user-attachments/assets/78ce1062-80a0-4edb-bf6b-5efac9dd992e" alt="류호찬" width="100">    |<ul><li>주요 화면 UI/UX 설계</li><li>화면별 UI 컴포넌트 개발</li><li>앱 디자인 시스템 구축</li><li>네비게이션 구조 및 사용자 흐름 설계</li><li>지도 화면 UI 개발 및 마커/경로 표시 기능 구현</li></ul>  |
| 허성재    |  <img src="https://github.com/user-attachments/assets/beea8c64-19de-4d91-955f-ed24b813a638" alt="허성재" width="100">    |<ul><li>주요 화면 UI/UX 설계</li><li>화면별 UI 컴포넌트 개발</li><li>앱 디자인 시스템 구축</li><li>네비게이션 구조 및 사용자 흐름 설계</li></ul>  |


<br/>

# 5. Technology Stack (기술 스택)
## 5.1 Language
|  |  |
|-----------------|-----------------|
| Java    |   <img src="https://github.com/user-attachments/assets/60140ded-2ac1-41d7-9db2-ae26fc9de43a" alt="JAVA" width="100">| 
| Dart    |   <img src="https://github.com/user-attachments/assets/cdd511f1-7bc1-494f-94da-906ac82dbc5c" alt="DART" width="100">|


<br/>


## 5.2 Frotend
| 기술 | 아이콘 | 용도 |
|------|--------|------|
| Flutter | <img width="100" alt="Flutter" src="https://github.com/user-attachments/assets/cf14255a-5701-4ecf-a3bc-ae22311cdd53" /> | 크로스 플랫폼 모바일 앱 개발 |
| Dart | <img width="100" alt="Dart" src="https://github.com/user-attachments/assets/744258af-f5cf-4b6e-b83f-b930ddadcb13" /> | Flutter 앱 개발 언어 |
| Google cloude console | <img width="100" alt="Google Cloud" src="https://github.com/user-attachments/assets/5b9ca576-bd4a-46f9-b11e-5a2fe7ad5118" /> | 사용자 인증 (이메일/구글 로그인) |
| kakao developer | <img width="100" alt="Kakao Login" src="https://github.com/user-attachments/assets/e5db5d07-6121-4900-abc8-19545c758dfb" /> | 사용자 인증 (이메일/카카오 로그인) |
| Google Maps Flutter | <img width="100" alt="Google Maps" src="https://github.com/user-attachments/assets/f69dbe66-bcbb-42d7-863a-182b8c2793c2" /> | 지도 표시 및 위치 기반 기능 |
<br/>




## 5.3 Backend
|  |  |  |
|-----------------|-----------------|-----------------|
| SpringBoot    |  <img src="https://github.com/user-attachments/assets/4937976f-8466-4a71-80c4-7e5bc21d5aff" alt="SpringBoot" width="100">    | 3.5.6    |
| SpringDataJPA    |  <img src="https://github.com/user-attachments/assets/c245860e-c53e-4595-8d38-3623db5055a7" alt="SpringDataJPA" width="100">    | 3.5.6    |
| SpringSecurity   |  <img src="https://github.com/user-attachments/assets/ef455654-d04b-4add-b77e-4a2f3fde8182" alt="SpringSecurity" width="100">    | 6.5.7    |
| H2 Database   |  <img src="https://github.com/user-attachments/assets/6598b89f-9e98-4898-96fe-b44b300528d5" alt="H2" width="100">    | 2.3.232    |
| Google Gemini API    |  <img src="https://github.com/user-attachments/assets/4c690fd4-721b-4303-af31-aa4dbcc641ea" alt="Google Gemini API" width="100">    | gemini-2.5-flash    |

<br/>

## 5.4 Cooperation
|  |  |
|-----------------|-----------------|
| Git    |  <img src="https://github.com/user-attachments/assets/483abc38-ed4d-487c-b43a-3963b33430e6" alt="git" width="100">    |
| Figma    |  <img src="https://github.com/user-attachments/assets/00eca926-1fb1-46ce-86e8-35119c519ce0" alt="figma" width="100">    |
| Notion    |  <img src="https://github.com/user-attachments/assets/34141eb9-deca-416a-a83f-ff9543cc2f9a" alt="Notion" width="100">    |

<br/>

# 6. API 명세서

<p>
  <img src="https://github.com/user-attachments/assets/893fc270-6a96-499f-b456-3f9e5b481120"
       alt="API 기본 명세서 (SmartFridge)"
       width="600" />
</p>

<p>
  🔗 <a href="https://soapy-margin-f62.notion.site/API-SmartFridge-2a79637693dc80b3834ef754fb8ee322?source=copy_link">
    자세한 내용은 Notion에서 보기
  </a>
</p>

# 6.1 프로젝트 구조 (프론트엔드)
```
smartfridge/
│
├── lib/
│   ├── main.dart                          # 앱 진입점 및 라우팅 설정
│   ├── env.dart                           # 환경 변수 및 API 설정
│   │
│   ├── Logindata/
│   │   ├── api_client.dart                # HTTP 요청을 처리하는 API 클라이언트
│   │   ├── auth_repository.dart           # 인증 관련 비즈니스 로직 (로그인, 회원가입)
│   │   └── auth_storage.dart              # 토큰 저장소 (Flutter Secure Storage)
│   │
│   ├── models/
│   │   ├── FridgeItem.dart                # 냉장고 식재료 모델
│   │   ├── CartItem.dart                  # 장바구니 상품 모델
│   │   ├── CartSummary.dart               # 장바구니 요약 정보 모델
│   │   └── RecipeItem.dart                # 레시피 정보 모델
│   │
│   ├── services/
│   │   ├── api_service.dart               # 모든 API 요청 관리 (냉장고, 장바구니, 레시피 등)
│   │   └── FavoriteService.dart           # 찜한 레시피 로컬 저장소 관리
│   │
│   ├── screens/
│   │   ├── LoginScreen/
│   │   │   ├── LoginScreen.dart           # 이메일/비밀번호 로그인 및 소셜 로그인 (카카오, 구글)
│   │   │   ├── SignupEmailScreen.dart     # 회원가입 - 이메일 입력 및 중복 확인
│   │   │   ├── SignupPasswordScreen.dart  # 회원가입 - 비밀번호 입력
│   │   │   ├── SignupPasswordConfirmScreen.dart  # 회원가입 - 비밀번호 확인
│   │   │   ├── SignupNicknameScreen.dart  # 회원가입 - 닉네임 입력
│   │   │   ├── SocialNicknameScreen.dart  # 소셜 로그인 후 닉네임 입력
│   │   │   └── validators.dart            # 입력 필드 유효성 검사 및 에러 메시지
│   │   │
│   │   ├── HomeScreen/
│   │   │   ├── HomeScreen.dart            # 홈 화면 - 냉장고/냉동고 요약 및 추천 레시피
│   │   │   └── RecomendRecipeScreen.dart  # 추천 레시피 상세 정보 화면
│   │   │
│   │   ├── RefrigeratorScreen/
│   │   │   ├── RefrigeratorScreen.dart    # 냉장고/냉동고 식재료 목록 및 관리
│   │   │   └── AddFridgeItemScreen.dart   # 냉장고에 식재료 추가하는 바텀시트
│   │   │
│   │   ├── CartScreen/
│   │   │   ├── CartScreen.dart            # 장바구니 목록 및 카테고리별 정렬
│   │   │   └── GoogleMapScreen.dart       # 근처 마트 찾기 (Google Maps API)
│   │   │
│   │   ├── RecipeScreen/
│   │   │   ├── RecipeScreen.dart          # 레시피 목록 및 AI 커스텀 추천
│   │   │   ├── RecipeDetailScreen.dart    # 레시피 상세 정보
│   │   │   ├── CookingGuideScreen.dart    # 단계별 조리 가이드
│   │   │   └── AIChatScreen.dart          # AI 요리 챗봇 (요리 팁 및 대화)
│   │   │
│   │   └── MypageScreen/
│   │       ├── MypageScreen.dart          # 마이페이지 - 프로필, 알림 설정, 정보
│   │       ├── EditProfileScreen.dart     # 프로필 수정 (닉네임, 전화번호, 자기소개)
│   │       └── FavoriteScreen.dart        # 찜한 레시피 목록
│   │
│   ├── Widget/
│   │   └── BottomIcon/
│── │       └── Bottom_Icon_Bar.dart       # 하단 네비게이션 바
```
<br/>

# 6.2 프로젝트 구조 (백엔드)
```plaintextapp/
app/
├── src/
│   ├── api/                   # 외부 API 호출
│   ├── config/                # 스프링 설정 (시큐리티, CORS 등)
│   ├── controller/            # REST 컨트롤러 (요청 받는 곳)
│   │     ├── auth/              # 로그인/회원 관련 API
│   │     ├── cart/              # 장바구니 API
│   │     ├── item/              # 냉장고 재료 API
│   │     └── mypage/            # 마이페이지 API
│   ├── domain/                # JPA 엔티티(테이블 매핑)
│   │     ├── cart/              # 장바구니 엔티티
│   │     ├── item/              # 재료/카탈로그 엔티티
│   │     └── user/              # 유저 엔티티
│   ├── dto/                   # 요청/응답 DTO 모음
│   │     ├── auth/              # 인증 DTO
│   │     ├── cart/              # 장바구니 DTO
│   │     ├── item/              # 재료 DTO
│   │     ├── mypage/            # 마이페이지 DTO
│   │     ├── GeminiRequest.java   # Gemini 요청 DTO
│   │     ├── GeminiResponse.java  # Gemini 응답 DTO
│   │     └── RecipeResponse.java  # 레시피 응답 DTO
│   ├── jwt/                   # JWT 토큰 관련 코드
│   ├── repository/            # DB 접근 (JPA Repository)
│   │     ├── cart/              # 장바구니 Repository
│   │     ├── item/              # 재료 Repository
│   │     └── user/              # 유저 Repository
│   ├── seed/                  # 초기 데이터 넣는 Seeder
│   ├── service/               # 비즈니스 로직
│   │     ├── auth/              # 인증 서비스
│   │     ├── cart/              # 장바구니 서비스
│   │     ├── item/              # 재료 서비스
│   │     ├── mypage/            # 마이페이지 서비스
│   │     ├── user/              # 유저 서비스
│   │     └── GemeniService.java   # Gemini 연동 서비스
│   ├── util/                  # 공용 유틸리티
└── SmartFridgeApplication.java    # 스프링 부트 메인 클래스

```

<br/>
<br/>

# 7. 실제 화면 구성

## 7.1 로그인 & 온보딩
<p align="center">
  <img src="https://github.com/user-attachments/assets/afcbc552-813f-4ea6-bf8f-d95aec1ffb9f" width="200">
  <img src="https://github.com/user-attachments/assets/4ab92837-9bac-438f-8cfe-f012a77cafca" width="200">
  <img src="https://github.com/user-attachments/assets/c8e30054-963c-4c05-b427-211cf0c1a5f9" width="200">
  <img src="https://github.com/user-attachments/assets/9555c159-9d66-4415-9b5a-678898a2c905" width="200">
</p>


<p align="center">
  <b>로그인 및 회원가입 화면</b><br/>
   이메일/비밀번호 및 소셜 로그인 지원
</p>

<br/><br/>

## 7.2 홈 화면 & 추천 레시피
<p align="center">
  <img src="https://github.com/user-attachments/assets/692ef07a-bc6d-4526-9da5-43fa71001a87" width="200">
  <img src="https://github.com/user-attachments/assets/ee2d1997-1690-425d-8ffd-14cffe0cb44f" width="200">
  <img src="https://github.com/user-attachments/assets/5f88ba0e-e93e-456d-9183-c151173e4a4f" width="200">
</p>




<p align="center">
  <b>홈 화면 및 AI 레시피 추천 기능</b><br/>
  현재 냉장고 속 재료를 기반으로 Gemini AI가 가능한 요리를 추천
</p>

<br/><br/>

## 7.3 레시피 & 요리하기
<p align="center">
  <img src="https://github.com/user-attachments/assets/0e9aa261-418e-4b44-8b82-d5f300912545" width="250">
  <img src="https://github.com/user-attachments/assets/f7d06e47-e112-48a4-8494-b9b87386eac9" width="250">
  <img src="https://github.com/user-attachments/assets/ec56d49e-fe89-4c55-9e3e-f131a1ecaf92" width="250">
</p>



<p align="center">
  <b>레시피 조회 및 요리 가이드 화면</b><br/>
  사용자는 레시피 목록에서 원하는 요리를 선택해 상세 정보를 확인할 수 있으며,<br/>
  조리 단계별 안내 화면을 통해 요리를 쉽게 따라 할 수 있습니다.
</p>


<br/><br/>

## 7.4 나의 냉장고
<p align="center">
  <img src="https://github.com/user-attachments/assets/e621f73a-b5b3-44b8-92be-d1f3285a26d7" width="250">
  <img src="https://github.com/user-attachments/assets/30fcc7ea-7779-416e-ac82-33aab101dd92" width="250">
</p>


<p align="center">
  <b>냉장/냉동고 재료 관리 기능</b><br/>
  재료 수량, 유통기한, 이미지 등 상세 정보 확인 가능
</p>

<br/><br/>

## 7.5 주변 마트 찾기 (Google Maps)
<p align="center">
  <img src="https://github.com/user-attachments/assets/aacfea1d-4456-4cf0-8c84-44edce4496ad" width="250">
</p>


<p align="center">
  <b>Google Maps 기반 주변 마트 검색</b><br/>
  현재 위치 주변 마트 확인 및 상세 정보 표시
</p>

<br/><br/>

## 7.6 장바구니
<p align="center">
  <img src="https://github.com/user-attachments/assets/d89d3b57-cd1e-47ad-923b-3c8dce87509f" width="250">
  <img src="이미지_경로/cart_to_fridge.png" width="250">
</p>


<p align="center">
  <b>장바구니 기능</b><br/>
  구매 예정 재료 저장 및 구매 완료 시 냉장고로 이동 가능
</p>

<br/><br/>

## 7.7 마이페이지
<p align="center">
  <img src="https://github.com/user-attachments/assets/da540416-2a4b-4566-98ef-30fb7309c99a" width="250">
  <img src="https://github.com/user-attachments/assets/701b651f-f70d-4d06-bea2-14a0b62c6510" width="250">
</p>

<p align="center">
  <b>사용자 프로필 및 찜목록 관리</b>
</p>


<br/><br/>




















