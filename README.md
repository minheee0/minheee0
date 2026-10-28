### 안녕하세요, 박민희입니다 👋

**고객이 실제로 쓰는 서비스를 끝까지 만들어 내는 개발자**를 목표로 하고 있습니다.
화면에서 서버, DB, 결제, 배포까지 기능 하나를 처음부터 끝까지 책임지는 일을 좋아합니다.

- 🏡 지금은 오픈을 앞둔 **독채 한옥 펜션의 예약·결제 시스템**을 혼자 만들고 있어요
- 🔐 동시성, 결제 정합성, 인증처럼 **틀리면 안 되는 부분**을 테스트로 증명하는 걸 중요하게 생각합니다
- 🤖 AI 개발 도구(Claude Code)로 새 기술을 빠르게 익히고, 핵심 설계는 직접 판단해 코드와 테스트로 남깁니다

<br/>

## 🛠 Tech Stack

**Frontend**
<br/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>

**Backend**
<br/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>

**Database · Infra**
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_EC2_·_RDS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

<br/>

## 📂 Projects

### 🏡 [만복 — 독채 한옥 펜션 예약·결제 서비스](https://github.com/minheee0/pension)
`1인 개발` `2026.09 ~ 진행 중` · **[🔗 배포 사이트](https://manbok-pension.vercel.app)**

오픈을 앞둔 펜션의 홈페이지 겸 예약·결제·운영 시스템. 손님 예약부터 사장님 관리자 화면까지 혼자 설계·개발·배포했습니다.

- **중복 예약 방지** — 날짜 행을 정해진 순서로 잠가 데드락 없이 "같은 날짜는 한 팀만", 30건 동시 요청 테스트로 검증
- **결제 정합성** — 토스페이먼츠 카드·가상계좌, 승인 응답 유실·늦은 웹훅·환불 실패까지 자동 복구
- **개인정보** — 전화번호 AES-GCM 암호화, 보유기간 경과 시 자동 파기

`Next.js 16` `React 19` `TypeScript` `PostgreSQL` `Toss Payments` `Vercel` `Neon`

---

### 🌱 [Sprout — IoT 스마트 식물 관리 앱](https://github.com/minheee0/SPROUT_Project_2025)
`팀 프로젝트 (6명) · 백엔드` `2025.03 ~ 2025.11` · 🏆 **교내 소프트웨어 경진대회 장려상**

IoT 센서로 실내 식물 환경을 모니터링하고 제어하는 앱의 백엔드에서 인증과 추천을 맡았습니다.

- **JWT 인증/인가** — Spring Security 필터 체인, 만료·위조 토큰 401 처리
- **맞춤 식물 추천** — 농촌진흥청 농사로 Open API(XML)를 설문 조건으로 조회해 3종 추천

`Java` `Spring Boot` `Spring Security` `JPA` `MySQL` `AWS EC2·RDS`

<br/>

## 📫 Contact

<a href="mailto:alsgml0125@gachon.ac.kr"><img src="https://img.shields.io/badge/Email-alsgml0125@gachon.ac.kr-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
