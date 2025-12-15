# Featured Projects

## Quick Summary
- **Gemini Cook**: Gemini API 기반 레시피 추천 웹 앱 (Streamlit) + 이미지 자동 수급
- **Auto Blog Posting (Private/Commercial)**: LLM 자동 포스팅 솔루션 (크몽 판매) + exe 배포
- **House Of Furniture**: React/Spring 풀스택 + AWS CI/CD + 모니터링
- **FaceReader**: 얼굴 지표 정량화 + GPT/Gemini 해석

---

## Gemini Cook
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/seunghwan94/Gemini_cook)

**AI 기반 맞춤형 레시피 추천 웹 앱**  
- **Tech:** `Python` `Streamlit` `Google Gemini API` `Google Custom Search API`
- **Highlights:** 사용자 입력 기반 레시피 생성 + 요리 이미지(썸네일) 자동 수급
- **Purpose:** Gemini API 개발자 대회 제출 프로젝트

<details>
  <summary><b>More</b></summary>

- 사용자 입력(재료/취향) 기반 맞춤형 레시피 생성  
- Google Custom Search API로 요리 이미지 자동 표시 (실패 시 기본 이미지 fallback)

</details>

---

## Auto Blog Posting (Private / Commercial)
**Source code is private (commercial project)**  
Demo repository or demo video available upon request

**LLM 기반 블로그 자동 생성·등록 솔루션 (크몽 판매/배포 경험)**  
- **Tech:** `Python` `Streamlit` `GPT API` `Gemini API` `Selenium` `Playwright` `PyInstaller`
- **Highlights:** Naver/Tistory 자동 포스팅 + Unsplash/Pexels 이미지 자동 수급 + exe 배포

<details>
  <summary><b>More</b></summary>

- **Auth:** Google Sheets 기반 화이트리스트 로그인  
- **Settings/UI:** Streamlit 설정 저장 및 UI 구성  
- **Content:** GPT/Gemini 선택형 글 자동 생성 + 프롬프트 템플릿 관리  
- **Images:** Unsplash / Pexels 자동 수급 및 통합  
- **Posting:** Naver / Tistory 자동 업로드 (Selenium, Playwright)  
- **Reliability:** 포스팅 실패 예외 처리  
- **Distribution:** PyInstaller exe 빌드 + 코드 난독화  

</details>

---

## House Of Furniture (가구의집)
[![Frontend](https://img.shields.io/badge/GitHub-Frontend-blue?logo=github)](https://github.com/seunghwan94/hof-front)
[![Backend](https://img.shields.io/badge/GitHub-Backend-green?logo=github)](https://github.com/seunghwan94/hof-back)

**풀스택 인테리어 커머스 플랫폼** (소품 판매 · 시공업체 소개 · 커뮤니티 · 결제)  
- **Tech:** `React` `Spring Boot` `MariaDB(RDS)` `MongoDB(EC2)` `AWS` `Docker` `GitHub Actions` `Prometheus` `Grafana`
- **Highlights:** CI/CD + 모니터링 + 배포 알림까지 포함한 운영형 프로젝트

<details>
  <summary><b>More</b></summary>

### Frontend
- `React` `Yarn` `Bootstrap SCSS` `Axios` (Debounce 최적화)

### Backend
- `Spring Boot` `JPA` `MyBatis` `Spring Security OAuth2`
- `Swagger` `Jacoco` `WebClient` `WebSocket`
- Google Vision API, Selenium

### Data / Payment
- `MariaDB (AWS RDS)` `MongoDB (EC2)`
- IAMPORT 결제 연동

### Infra & DevOps
- **CI/CD:** GitHub Actions + Docker + AWS(EC2, S3, RDS)
- **Web:** Nginx Reverse Proxy + SSL + Cloudflare
- **Monitoring:** Prometheus + Grafana
- **Notification:** Discord 배포 알림

</details>

---

## FaceReader (관상 - 내가 왕이될 상인가)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/seunghwan94/FaceReader)

**얼굴 랜드마크 기반 정량 분석 + LLM 해석 구조**  
- **Tech:** `Python` `dlib` `face_recognition` `Pillow` `GPT API` `Gemini API`
- **Highlights:** 정량 지표 계산/시각화 → JSON 출력 → GPT/Gemini 해석

<details>
  <summary><b>More</b></summary>

- 거리/각도/비율/대칭성 등 정량 지표(metrics) 추출  
- 선(Line) 시각화 및 결과 JSON 출력  
- 정량 지표를 기반으로 LLM 해석을 요청해 일관성/비용 측면 고려  
- **Note:** Windows 환경 dlib 빌드 필요 (`CMake` + `Visual C++ Build Tools`)

</details>
