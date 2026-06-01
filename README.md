# 🎨 Theme Market Platform (MONSTER)

이 프로젝트는 다양한 디자인 테마를 전시, 리뷰 및 구매할 수 있는 **테마 마켓 플랫폼**입니다. 사용자는 고품질의 테마를 탐색하고 상세 정보를 확인하며, 구매 및 리뷰를 남길 수 있는 통합 환경을 제공합니다.

## 🚀 주요 기능

- **테마 브라우징:** 다양한 카테고리의 테마 목록 확인 및 상세 정보 조회.
- **사용자 인증:** Spring Security와 JWT를 이용한 안전한 로그인 및 회원가입.
- **구매 및 라이선스:** 테마 구매 이력 관리 및 라이선스 키 발급.
- **리뷰 시스템:** 테마별 평점 및 후기 작성 기능.
- **반응형 프론트엔드:** React 기반의 현대적이고 직관적인 UI/UX.

## 🛠 기술 스택

### Backend
- **Framework:** Spring Boot 4.0.6 (Java 21)
- **Security:** Spring Security & JWT
- **Database:** MariaDB (Production), H2 (Local Development)
- **ORM:** Spring Data JPA (Hibernate)
- **API Documentation:** Springdoc-OpenAPI (Swagger)

### Frontend
- **Framework:** React 19 (TypeScript)
- **Build Tool:** Vite
- **Styling:** TailwindCSS 4.0
- **State Management:** Zustand
- **Routing:** React Router 7

## 🏃 시작하기

### 백엔드 실행
```bash
./gradlew bootRun
```
*서버 주소: http://localhost:8081*

### 프론트엔드 실행
```bash
cd frontend
npm install
npm run dev
```
*서버 주소: http://localhost:5173*

---
본 프로젝트는 **aaa123** 그룹의 일환으로 개발되었습니다.

그리고 유기된 웹 페이지입니다.

test