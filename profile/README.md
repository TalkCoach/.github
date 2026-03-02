# 0. Getting Started (시작하기)

```bash
# Backend
./gradlew bootRun

# AI Backend (Python)
# 구현 진행 중

# Frontend (Flutter)
# 구현 전
```

<br/>
<br/>

# 1. Project Overview (프로젝트 개요)

- **프로젝트 이름**: TalkCoach
- **프로젝트 설명**:  
  면접, 발표, 일상 대화를 녹음 및 영상 기반으로 분석하여  
  말투, 호흡, 딕션, 억양, 표정/시선 안정도와 스크립트 개선 피드백을 제공하는  
  **AI 말하기 코칭 애플리케이션**

<br/>
<br/>

# 2. Team Members (팀원 및 팀 소개)

| 구자혁 | 지경태 | 조성빈 | 황요성 | 류호찬 |
|:------:|:------:|:------:|:------:|:------:|
| <img src="https://via.placeholder.com/150?text=Profile" alt="구자혁" width="150"> | <img src="https://via.placeholder.com/150?text=Profile" alt="지경태" width="150"> | <img src="https://via.placeholder.com/150?text=Profile" alt="조성빈" width="150"> | <img src="https://via.placeholder.com/150?text=Profile" alt="황요성" width="150"> | <img src="https://via.placeholder.com/150?text=Profile" alt="류호찬" width="150"> |
| BE | BE | BE | FE | FE |
| [GitHub](https://github.com/JaHyeok2002) | [GitHub](https://github.com/JiKyeongtae) | GitHub | GitHub | [GitHub](https://github.com/ryuhochan0406) |

<br/>
<br/>

# 3. Current Status (현재 진행 상태)

- **BE_SpringBoot**
  - 프로젝트 초기 세팅 완료
  - 로그인 / 인증 기능 중심으로 구현 진행
  - JWT 기반 인증 구조 및 소셜 로그인 연동 구조 세팅
  - H2 DB 기반 개발 환경 구성

- **BE_AI (Python)**
  - AI 분석 서버 별도 구성 예정
  - 음성 / 텍스트 분석 및 피드백 생성 기능 구현 예정

- **Frontend (Flutter)**
  - 아직 본격 구현 전
  - 추후 로그인, 홈, 분석 결과, 마이페이지 화면 순차 개발 예정

<br/>
<br/>

# 4. Planned Features (예정 기능)

- **회원가입 / 로그인**
  - 이메일 회원가입 및 로그인
  - 소셜 로그인 (구글 / 카카오)

- **면접 모드**
  - 면접 질문 작성 또는 AI 질문 생성
  - 답변 녹음 / 영상 업로드
  - 답변 기반 분석 및 피드백 제공

- **발표 모드**
  - 발표 연습용 음성 / 영상 업로드
  - 발화 안정도, 전달력, 호흡, 딕션 분석

- **일상 대화 모드**
  - 일상 회화 녹음 후 말하기 습관 분석
  - 억양, 말속도, 발음 습관 피드백

- **AI 분석 리포트**
  - 총 점수 제공
  - 사용자 스크립트 / 개선 스크립트 비교
  - 호흡 안정도, 딕션 안정도, 억양 안정도 분석
  - 표정 / 시선 안정도 분석
  - 종합 피드백 제공

- **마이페이지**
  - 사용자 정보 조회 및 수정
  - 분석 기록 확인
  - 개인 맞춤 학습 이력 관리

<br/>
<br/>

# 5. Tasks & Responsibilities (작업 및 역할 분담)

| 이름 | 프로필 | 담당 업무 |
|------|------|------|
| 구자혁 | <img src="https://via.placeholder.com/100?text=Profile" alt="구자혁" width="100"> | <ul><li>백엔드 총괄</li><li>로그인 / 인증 기능 구현</li><li>프로젝트 구조 설계 및 통합</li></ul> |
| 지경태 | <img src="https://via.placeholder.com/100?text=Profile" alt="지경태" width="100"> | <ul><li>백엔드 기능 개발</li><li>AI 연동 구조 설계</li><li>분석 데이터 처리 로직 지원</li></ul> |
| 조성빈 | <img src="https://via.placeholder.com/100?text=Profile" alt="조성빈" width="100"> | <ul><li>백엔드 기능 개발</li><li>DB 및 API 구조 보조</li><li>기능 확장 대응</li></ul> |
| 황요성 | <img src="https://via.placeholder.com/100?text=Profile" alt="황요성" width="100"> | <ul><li>프론트엔드 UI/UX 설계 예정</li><li>앱 화면 구조 설계 예정</li><li>공통 컴포넌트 설계 예정</li></ul> |
| 류호찬 | <img src="https://via.placeholder.com/100?text=Profile" alt="류호찬" width="100"> | <ul><li>프론트엔드 개발 예정</li><li>화면 구현 및 네비게이션 구성 예정</li><li>분석 결과 화면 개발 예정</li></ul> |

<br/>

# 6. Repository Overview (레포지토리 구성)

## 6.1 BE_SpringBoot
- Spring Boot 기반 메인 백엔드 서버
- 현재 로그인 / 인증 기능 중심으로 구현 진행 중
- 향후 회원가입, 사용자 관리, 분석 결과 저장/조회 기능 확장 예정

## 6.2 BE_AI
- Python 기반 AI 분석 서버
- 음성/텍스트 분석 및 피드백 생성 로직 담당 예정
- 현재 구조 정리 및 기능 설계 단계

## 6.3 Frontend
- Flutter 기반 모바일 앱 예정
- 현재는 화면 및 기능 정의 단계
- 추후 로그인 / 홈 / 모드 선택 / 결과 리포트 / 마이페이지 구현 예정

<br/>

# 7. Technology Stack (기술 스택)

## 7.1 Backend
| 기술 | 설명 |
|------|------|
| Java | 백엔드 메인 언어 |
| Spring Boot | 백엔드 프레임워크 |
| Spring Security | 인증 / 인가 처리 |
| Spring Data JPA | ORM 및 데이터 접근 |
| OAuth2 Client | 구글 / 카카오 소셜 로그인 연동 |
| JWT | 토큰 기반 인증 |
| H2 Database | 개발용 DB |
| MySQL | 확장 가능한 운영 DB 대응 |

<br/>

## 7.2 AI
| 기술 | 설명 |
|------|------|
| Python | AI 서버 구현 언어 |
| AI Analysis Logic | 음성 / 텍스트 분석 및 피드백 생성 예정 |

<br/>

## 7.3 Frontend
| 기술 | 설명 |
|------|------|
| Flutter | 크로스 플랫폼 모바일 앱 개발 예정 |
| Dart | Flutter 앱 개발 언어 |

<br/>

## 7.4 Cooperation
| 기술 | 설명 |
|------|------|
| GitHub | 형상 관리 |
| Figma | 화면 설계 |
| Notion | 문서화 및 협업 |

<br/>

# 8. Project Structure (예정 구조)

## 8.1 Backend
```plaintext
BE_SpringBoot/
├── data/
├── gradle/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/talkcoach/
│   │   │       ├── config/
│   │   │       ├── controller/
│   │   │       ├── domain/
│   │   │       ├── dto/
│   │   │       ├── jwt/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       └── TalkCoachApplication.java
│   │   └── resources/
│   │       └── application.yml
│   └── test/
├── build.gradle
├── gradlew
├── gradlew.bat
└── settings.gradle
```

## 8.2 AI Backend
```plaintext
BE_AI/
└── talkcoach/
    ├── app/
    ├── analysis/
    ├── models/
    ├── services/
    └── main.py
```

## 8.3 Frontend
```plaintext
Frontend/
└── (구현 예정)
```

<br/>
<br/>

# 9. Screen Preview (예정 화면 구성)

## 9.1 로그인
<p align="center">
  <img src="https://via.placeholder.com/200x400?text=Login" width="200">
</p>

<p align="center">
  <b>로그인 화면</b><br/>
  이메일 로그인 및 소셜 로그인 지원 예정
</p>

<br/><br/>

## 9.2 홈 화면
<p align="center">
  <img src="https://via.placeholder.com/200x400?text=Home" width="200">
</p>

<p align="center">
  <b>홈 화면</b><br/>
  면접 / 발표 / 일상 대화 모드 선택 화면 예정
</p>

<br/><br/>

## 9.3 면접 / 발표 / 일상 대화 모드
<p align="center">
  <img src="https://via.placeholder.com/200x400?text=Interview" width="200">
  <img src="https://via.placeholder.com/200x400?text=Presentation" width="200">
  <img src="https://via.placeholder.com/200x400?text=Daily" width="200">
</p>

<p align="center">
  <b>연습 모드 화면</b><br/>
  모드별 녹음 / 영상 업로드 및 분석 요청 기능 예정
</p>

<br/><br/>

## 9.4 분석 결과 화면
<p align="center">
  <img src="https://via.placeholder.com/200x400?text=Result" width="200">
  <img src="https://via.placeholder.com/200x400?text=Feedback" width="200">
</p>

<p align="center">
  <b>분석 결과 리포트</b><br/>
  점수, 피드백, 개선 스크립트 제공 예정
</p>

<br/><br/>

## 9.5 마이페이지
<p align="center">
  <img src="https://via.placeholder.com/200x400?text=MyPage" width="200">
</p>

<p align="center">
  <b>마이페이지</b><br/>
  사용자 정보 및 분석 기록 관리 예정
</p>

<br/>
<br/>

# 10. Notes (비고)

- 현재 공개 레포지토리 기준으로는 **백엔드(Spring Boot) 초기 인증 기능 중심**으로 개발이 진행 중입니다.
- AI 서버 및 프론트엔드는 추후 구현 내용에 맞춰 README를 계속 업데이트할 예정입니다.
- 팀원 사진은 현재 기본 이미지로 적용했으며, 실제 개발 완료 후 교체 예정입니다.
