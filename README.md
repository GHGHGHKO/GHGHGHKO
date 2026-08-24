# Hi there, I'm 고형규 (Hyung-gyu Ko) 🍺

Backend Engineer at GS Retail, building scalable logistics and CRM systems serving millions of customers.  
Creator of **[RunMarket](http://about.runmarket.cc/)** — Real-time GPS Location Tracking & Live Spectating Platform.

---

GS Retail에서 수백만 고객을 대상으로 한 물류·CRM 시스템을 설계하고 운영하는 백엔드 엔지니어입니다.  
러너와 관전자를 위한 실시간 러닝 위치 공유 서비스 [런마켓](http://about.runmarket.cc/)을 개발 및 운영하고 있습니다.

---

## 🏃‍♂️ Featured Project / 대표 프로젝트

### **[RunMarket (런마켓)](http://about.runmarket.cc/)** — "달리는 사람과 함께 달리는 방법"
> 러너(RUNNER)와 관전자(WATCHER)가 같은 그룹 코드로 연결되어, 지도 위에서 실시간으로 위치·페이스·동선을 공유하고 응원하는 크로스플랫폼 모바일/웹 서비스

[![Landing Page](https://img.shields.io/badge/Landing_Page-about.runmarket.cc-ff9900?style=flat&logo=firefoxbrowser&logoColor=white)](http://about.runmarket.cc/)
[![App Store](https://img.shields.io/badge/App_Store-cc.runmarket.app-007AFF?style=flat&logo=apple&logoColor=white)](https://apps.apple.com/kr/app/%EB%9F%B0%EB%A7%88%EC%BC%93/id6779493827)
[![Google Play](https://img.shields.io/badge/Google_Play-준비중_Coming_Soon-34A853?style=flat&logo=googleplay&logoColor=white)](http://about.runmarket.cc/)
[![Web App](https://img.shields.io/badge/Web_App-runmarket.cc-232f3e?style=flat&logo=react&logoColor=white)](https://www.runmarket.cc)

- **EN**: Built a high-performance real-time location streaming backend with **Spring WebFlux + Reactive Redis WebSocket Broker**, integrated **iOS Live Activity (Dynamic Island)** & **Apple HealthKit**, and declared IaC infrastructure using **K3s Kubernetes Helm Charts**. (Achieved 0% error rate on k6 load test simulating 1,000 concurrent runners).
- **KR**: **Spring WebFlux + Reactive Redis WebSocket** 기반 고성능 위치 중계 서버 구축, **iOS Live Activity (Dynamic Island)** 및 **Apple HealthKit** 연동, **K3s Kubernetes Helm Chart**를 활용한 선언적 IaC 인프라 구성 (k6 1,000명 동시 접속 1초 주기 실시간 시뮬레이션 부하테스트 에러율 0% 달성).

---

## 🛠 Tech Stack

**Languages**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

**Backend**  
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring WebFlux](https://img.shields.io/badge/Spring_WebFlux-6DB33F?style=flat&logo=spring&logoColor=white)
![Spring Batch](https://img.shields.io/badge/Spring_Batch-6DB33F?style=flat&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)

**Mobile & Frontend**  
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000000?style=flat&logo=expo&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)

**Database & Cache**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat&logo=redis&logoColor=white)

**Infrastructure**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat&logo=datadog&logoColor=white)

---

## 🚀 Projects & Open Source / 프로젝트 및 오픈소스
| Project | Description | Tech |
|---------|-------------|------|
| 🏃‍♂️ **[runmarket](https://github.com/runmarket-cc)** | Real-time GPS location tracking & live spectating app | Expo, React Native, Spring WebFlux, K3s |
| 🦀 **[dalgona](https://github.com/GHGHGHKO/dalgona)** | Cross-platform GIF meme finder (Windows & macOS) | Tauri, Next.js, Rust |
| 🎬 **[klassic-quote-api](https://github.com/GHGHGHKO/klassic-quote-api)** | Korean classic movie quotes REST API | Rust, Axum, Docker |
| 🎬 **[klassic-quote](https://github.com/GHGHGHKO/klassic-quote)** | Korean movie quotes frontend | TypeScript |
| 🟢 **[upptime](https://github.com/GHGHGHKO/upptime)** | Self-hosted uptime monitoring | GitHub Actions |

---

## 💼 What I Do / 주요 업무

**EN**
- Designed a **delivery backend monorepo** serving 6 systems and 18,000+ field devices, secured with JWE + AWS KMS
- Migrated 5 logistics services from **IDC to AWS**, converting Oracle SQL to ANSI SQL with zero downtime
- Modernized batch architecture from `@Scheduled` to **Airflow + KubernetesPodOperator** for isolated, observable execution
- Built **Datadog logging standards** — CUD audit trails, PII segregation via Logback Marker, distributed request tracing
- Stabilizing a **20-million-user CRM platform** — recovering dead batches, fixing data sync bugs, building privacy-compliant APIs

**KR**
- 6개 시스템·전국 18,000대 현장 기기를 지원하는 **택배 백엔드 모노레포** 설계 (JWE + AWS KMS 보안)
- 5개 물류 서비스 **IDC → AWS 이관**, Oracle SQL → ANSI SQL 무중단 전환
- `@Scheduled` 배치를 **Airflow + KubernetesPodOperator** 구조로 개선 — 앱 재배포와 배치 실행 분리
- **Datadog 로그 수집 체계** 구축 — CUD 감사 로그, Logback Marker 기반 개인정보 분리, 분산 트레이싱
- **2,000만 회원 CRM 플랫폼** 안정화 — 장기 중단 배치 복구, 개인정보 동기화 버그 수정, 프라이버시 준수 API 개발

---

## 📫 Links

[![RunMarket Intro](https://img.shields.io/badge/RunMarket-about.runmarket.cc-ff9900?style=flat&logo=firefoxbrowser&logoColor=white)](http://about.runmarket.cc/)  
[![Portfolio](https://img.shields.io/badge/Portfolio-feelsgoodfrog-black?style=flat&logo=astro)](https://feelsgoodfrog-links.vercel.app/)  
[![Instagram](https://img.shields.io/badge/Instagram-hg____ko-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/hg____ko/)  
[![HackerRank](https://img.shields.io/badge/HackerRank-Problem_Solving_(Gold)-FFD700?style=flat&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/gudrb963)
