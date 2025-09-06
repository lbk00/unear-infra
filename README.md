# Unear - 위치 기반 멤버십 혜택 서비스

## 프로젝트 개요

### 프로젝트 목적

본 프로젝트는 **LG U+ 연계 팝업 스토어 중심의 지역 기반 이벤트**에 사용자가 참여하며, 인근 제휴처(소상공인 포함)를 추천받고 **이벤트 매장 결제를 통해 스탬프를 적립하는 참여형 혜택 플랫폼**입니다. 사용자는 지도 기반으로 주변 제휴처의 멤버십 혜택 및 할인 정보를 확인하며, **이벤트 정보를 통해 멤버십 바코드 제출 및 결제 인증을 통해 참여하는 것을 목표**로 합니다.

### 핵심 가치

- **위치 기반 이벤트 참여**: LG U+ 팝업 스토어와 연계한 지역 맞춤형 이벤트 제공
- **스탬프 적립 시스템**: 방문 인증을 통한 스탬프 적립 및 보상 시스템
- **소상공인 상생**: 지역 소상공인 제휴처 추천을 통한 상생 생태계 구축
- **실시간 위치 알림**: 제휴처 진입 시 자동 팝업을 통한 이벤트 안내
- **통합 멤버십 관리**: 멤버십 바코드 제출 및 결제 인증을 통한 간편한 혜택 이용

---


## 팀원 소개

<div align="center">

| ![@1seyoung](https://github.com/1seyoung.png) | ![@lbk00](https://github.com/lbk00.png) | ![@tjdqls3607](https://github.com/tjdqls3607.png) | ![@khwww](https://github.com/khwww.png) | ![@KimJunSeo289](https://github.com/KimJunSeo289.png) | ![@alex8396](https://github.com/alex8396.png) | ![@Hongjunior](https://github.com/Hongjunior.png) |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| **한세영** | **이본규** | **정성빈** | **김현우** | **김준서** | **임재찬** | **홍석준** |
| [@1seyoung](https://github.com/1seyoung) | [@lbk00](https://github.com/lbk00) | [@tjdqls3607](https://github.com/tjdqls3607) | [@khwww](https://github.com/khwww) | [@KimJunSeo289](https://github.com/KimJunSeo289) | [@alex8396](https://github.com/alex8396) | [@Hongjunior](https://github.com/Hongjunior) |
| ![BE 팀장](https://img.shields.io/badge/BE-팀장-FF6B6B?style=flat-square) | ![테크리더](https://img.shields.io/badge/테크-리더-4ECDC4?style=flat-square) | ![Backend](https://img.shields.io/badge/Backend-개발자-45B7D1?style=flat-square) | ![FE 팀장](https://img.shields.io/badge/FE-팀장-96CEB4?style=flat-square) | ![Frontend](https://img.shields.io/badge/Frontend-개발자-FFEAA7?style=flat-square) | ![Frontend](https://img.shields.io/badge/Frontend-개발자-FFEAA7?style=flat-square) | ![Frontend](https://img.shields.io/badge/Frontend-개발자-FFEAA7?style=flat-square) |

</div>

### 역할 분담

<div align="center">

| 팀 | 이름 | 역할 | 담당 업무 |
|:--:|:--:|:--:|:--|
| **🔧 Backend** | **한세영 (BE 팀장)** | DevOps & Backend Lead | • DevOps, 포스기 기능 개발<br>• 알림 시스템 구축, Airflow<br>• 포스기 프론트 개발, 데이터 샘플링<br>• RAG 추천 |
| **🔧 Backend** | **이본규 (테크리더)** | Tech Lead & Database | • ERD 설계, DB 관리<br>• OAuth 연동, 유저 서버 개발<br>• Log-consumer 구축, Airflow 설계<br>• 관리자 대시보드 시각화 |
| **🔧 Backend** | **정성빈** | QA & API Development | • QA 담당, 어드민 서버 개발<br>• 이번주니어 API 개발<br>• 대시보드 프론트 개발, 커뮤니케이션<br>• 소비스토리 및 제휴처 추천 API 개발 |
| **💻 Frontend** | **김현우 (FE 팀장)** | Frontend Lead & Architecture | • 공통 컴포넌트 개발<br>• 지도 페이지 개발<br>• PWA 구축, 검색 엔진 최적화 |
| **💻 Frontend** | **김준서** | Frontend Developer | • 공통 컴포넌트 개발<br>• 메인 페이지 개발, 마이 페이지 개발<br>• 알림 시스템 연동 |
| **💻 Frontend** | **임재찬** | Frontend Developer | • 공통 컴포넌트 개발<br>• 로그인/회원가입 페이지 개발<br>• 이번주니어 페이지 개발 |
| **💻 Frontend** | **홍석준** | Frontend Developer | • 공통 컴포넌트 개발<br>• 스토리 페이지 개발<br>• 온보딩/혜택 안내 페이지 개발 |

</div>

---


## 서비스 소개

**Unear**는 LG U+ 연계 팝업 스토어를 중심으로 한 지역 기반 참여형 혜택 플랫폼입니다. 사용자의 위치 정보를 활용하여 주변 제휴처의 이벤트 정보를 제공하고, 방문 인증을 통한 스탬프 적립 시스템으로 지역 상권 활성화를 도모합니다.

### 주요 특징

| 기능                          | 설명                                               |
| ----------------------------- | -------------------------------------------------- |
| **위치 및 소비 패턴 기반 제휴처 추천**         | 사용자의 현재 위치와 소비 패턴 데이터를 분석하여 맞춤형 제휴처 추천 리스트를 제공 |
| **스탬프 적립 시스템**     | 매장 방문 인증 또는 결제 인증을 통해 스탬프를 적립하고, 누적 스탬프에 따른 보상을 제공  |
| **멤버십 바코드 통합**     | 사용자가 간편하게 멤버십 바코드를 제시하여 제휴 혜택 및 할인 서비스를 이용 가능   |
| **소셜 로그인**            | Google, Kakao, Naver 간편 로그인 기능을 지원하여 회원가입 절차 간소화             |
| **사용자 통계 및 이용 내역**            | 개인별 이용 내역과 통계를 요약 및 상세 제공, 활동 분석을 통한 사용자 맞춤 서비스 지원      |
| **관리자 대시보드 연동**            | 관리자 전용 대시보드를 통해 사용자 행동 로그 및 통계 데이터를 기반으로 한 관리 기능 제공    |
---

## 시스템 아키텍쳐
<img width="1129" height="495" alt="스크린샷 2025-08-07 오후 8 56 23" src="https://github.com/user-attachments/assets/c24c1696-15b1-43b7-8d5f-81fb1c334c31" />

---

## ERD
<img width="1874" height="557" alt="스크린샷 2025-08-27 오후 3 31 13" src="https://github.com/user-attachments/assets/cf4d8c39-6ed8-471e-bc38-a43f4ba01655" />
<img width="1907" height="774" alt="스크린샷 2025-08-27 오후 3 37 08" src="https://github.com/user-attachments/assets/d419a062-5c53-4064-842c-78fe378ed0ea" />
<img width="1903" height="773" alt="스크린샷 2025-08-27 오후 3 37 26" src="https://github.com/user-attachments/assets/0b943548-9979-44d0-8f7a-fa788883b81a" />





---
## 기술 스택 

### Backend
  
| 구성 요소 | 기술 |
|-----------|------|
| Backend | Java, Spring Boot, JPA , OAuth2, JWT, Session , PostgreSQL, PostGIS, PGVector , Redis, Redis Stream, Apache Airflow|
| DevOps | AWS EC2, ELB, S3, CloudFront, Docker, Docker Hub, GitHub Actions|
| Tools | Swagger, Postman , DBeaver, Coderabbit|
| AI | OpenAI, RAG |

### Frontend

| 구성 요소 | 기술 |
|-----------|------|
| Frontend	| TypeScript, React, Next.js, Tailwind CSS, Styled-components, Framer Motion, Zustand, Recoil, Redux Toolkit, React Query (TanStack Query), Axios |
| Tools	| Vite, ESLint, Prettier, Storybook, Vitest, Jest, React Testing Library, Cypress, Vercel, GitHub Actions |

---
## 프로젝트 구조

<pre>
unear-infra/
├── unear-user-backend/          # 사용자 서비스 API 서버
├── unear-pos-backend/           # 가맹점 POS 연동 서버
├── unear-admin-backend/         # 관리자 웹 대시보드 백엔드
├── unear-log-consumer/          # Redis Stream 로그 컨슈머 (로그 적재)
├── unear-airflow-analysis/      # 사용자 행동 로그 요약 및 통계 분석 (Airflow DAG)
├── unear-frontend               # 사용자 서비스 프론트엔드
├── unear-admin-frontend         # 관리자 대시보드 프론트엔드
└── unear-pos-frontend           # 포스기 프론트엔드
</pre>

---

## 주요 기능 흐름

### 1. 메인 페이지 (MainPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/acf23b55-0d7b-48bc-ac95-ec1c3084c01d" alt="유니어_메인화면" height="400"/>
</div>

---

### 2. 지도 기반 매장 검색 (MapPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/8db915e7-7b34-4250-8c98-b77ef5f0d3f3" alt="지도_페이지_1" height="400" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/29374bf0-15a8-416e-8189-081785942a50" alt="지도_페이지_2" height="400"/>
</div>

---

### 3. 개인화 스토리 (StoryPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/0763ab0b-b952-4819-ada2-56346c4d2236" alt="스토리페이지" height="400"/>
</div>

---

### 4. 주니어 스탬프 이벤트 (JuniorPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/a6d0d086-3a7e-4893-b134-48fea65ab863" alt="이번주니어" height="400"/>
</div>

---

### 5. 마이페이지 (MyPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/7cb0f32d-148b-4525-a5a8-25f451c47c89" alt="마이페이지1" height="400" style="margin-right: 10px;"/>
  <img src="https://github.com/user-attachments/assets/a6323572-8484-48a4-b7a8-f5a871d3bc12" alt="마이페이지2" height="400"/>
</div>

---

### 6. 멤버십 시스템 (MembershipPage)

<div align="center">
  <img src="https://github.com/user-attachments/assets/8a765210-170b-4229-a5ef-ef6317a0a249" alt="유니어_맴버십혜택" height="400"/>
</div>

---

### 7. 인증 시스템 (Auth)

<div align="center">
  <img src="https://github.com/user-attachments/assets/4fc2a792-7822-488d-99f0-64ec3ad42bdd" alt="로그인 페이지" height="400"/>
</div>

---


## 관련 링크

<div align="center">

| 서비스               | 링크                                                                        |
| -------------------- | --------------------------------------------------------------------------- |
| **Frontend**      | [프론트엔드 저장소](https://github.com/ureca-poject-unear/unear-frontend)        |
| **Backend**       | [백엔드 저장소](https://github.com/ureca-poject-unear/unear-user-backend)             |
| **Documentation** | [프로젝트 노션](https://veiled-foe-fd5.notion.site/7-U-Near-22077da8c8038036aec4fe7527ca5a54?source=copy_link)                            |
| **Design**        | [Figma 디자인](https://www.figma.com/design/J8kcia6vzarmRddDKSBaEg/-%EC%9C%A0%EB%A0%88%EC%B9%B4-%EC%9C%B5%ED%95%A9%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8--7%ED%8C%80?node-id=400-217&t=GNpcf3g5JsLcFtcy-1)                              |
| **Video Link**        | [시연영상 링크](https://www.youtube.com/watch?v=6NjBhV3zJFI)              |

</div>

---

