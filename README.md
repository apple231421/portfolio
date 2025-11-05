# 👨‍💻 김창규 포트폴리오  
> **“사용자 경험을 중심으로 문제를 해결하는 개발자”**  
> Java & Spring 기반 백엔드/풀스택 개발자로,  
> 웹 플랫폼(예약·게시판)과 챗봇 서비스(OpenAI 연동) 개발 경험이 있습니다.

---

## 🛠 Tech Stack
![Java](https://img.shields.io/badge/Java-17+-orange)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![JPA](https://img.shields.io/badge/JPA-Hibernate-blue)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf--informational)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple)
![AWS](https://img.shields.io/badge/AWS-EC2%20%7C%20RDS%20%7C%20S3-black)

---

## 📌 Projects

### 🏷 HobbyMe — 취미 공유 플랫폼
> **혼자서 백엔드 핵심 기능 전체를 설계하고 구현한 4인 팀 프로젝트**

🔗 **GitHub:** [HobbyMe Repository](https://github.com/apple231421/hobbyMe)

#### 🎯 프로젝트 개요  
사용자가 취미 클래스를 등록하고, 다른 사용자가 예약·댓글·좋아요로 상호작용할 수 있는 취미 공유 플랫폼입니다.

#### 🧩 역할 (Backend Developer)
- **게시판 핵심 기능**
  - 좋아요, 댓글, 카테고리, 태그, 마감일(D-day) 설계 및 구현
  - 게시글 정렬 (최신순 / 좋아요순 / 댓글순) 기능 구현
  - 입력값 검증을 통한 SQL Injection·XSS 사전 차단

- **파일 업로드**
  - 썸네일·본문 이미지 업로드 및 기본 이미지 자동 등록
  - 파일 확장자·사이즈 검증으로 악성 파일 업로드 방지  
  - 디렉토리 접근 제한을 통한 보안 강화

- **지도 연동**
  - Kakao 지도 API를 이용한 위치 선택 및 지도 표시 기능 구현
  - API Key 보안을 위해 환경 변수 관리 적용

- **예약/결제 흐름 지원**
  - 예약 인원 제한 및 모집 마감 처리 로직 구현  
  - 중복 예약 차단 및 비인가 결제 요청 방어 로직 적용  
  - 예외 처리 및 트랜잭션 관리로 데이터 무결성 확보

#### 🧠 기술 스택  
Java Servlet/JSP · Spring Boot · MySQL · Bootstrap · Kakao Maps API

#### 📈 성과
- 게시판 + 지도 + 파일 업로드 등 실제 플랫폼 수준의 CRUD 설계 경험  
- 보안·유효성 검증 로직 직접 구현  
- 팀 내 코드 리뷰 및 협업 경험을 통한 프로젝트 관리 능력 향상  

---

### 🏥 Final Project — 병원 웹 애플리케이션
> **Spring Boot 기반 종합 웹 서비스 (예약 + 챗봇 + 게시판 + OAuth 로그인)**

🔗 **GitHub:** [더조은 의료재단 Repository](https://github.com/apple231421/final-project)

#### 🎯 프로젝트 개요  
병원 예약·의료진 관리·AI 챗봇 기능을 통합한 의료 웹 서비스입니다.  
사용자(환자/의사/관리자) 역할별로 접근 제어가 구분되며, OAuth2 기반 로그인과 AI 챗봇(OpenAI, Kakao API) 연동이 가능합니다.

#### 🧩 역할 (Backend Developer)
- **예약 시스템**
  - 의사 프로필·스케줄·예약·취소·가능 시간 조회 기능 설계 및 구현  
  - JPA + 트랜잭션 관리 기반 예약 로직 구성

- **AI 챗봇 연동**
  - OpenAI API 기반 챗봇 설계 및 구현  
  - DeepL / Kakao API 연동, 다국어 응답 처리 로직 개발  
  - API Key 보안 및 호출 캡슐화 처리

- **OAuth2 로그인**
  - Google / Kakao 로그인 연동
  - 사용자 권한(Role)에 따른 접근 제어 적용

- **기타 기능**
  - 게시판(공지/뉴스/Q&A) CRUD  
  - 자원봉사 신청 관리, Gmail SMTP 이메일 발송, PDF 진단서 출력

#### 🧠 기술 스택  
Spring Boot · JPA · Thymeleaf · MySQL · OAuth2 · OpenAI API · Bootstrap

#### 📈 성과
- 실제 병원 예약 프로세스를 반영한 시스템 설계 및 구현  
- OpenAI 챗봇 기능을 직접 백엔드에 통합  
- OAuth 기반 로그인 및 Role별 접근 제어 로직 구현  

---

## 🤝 Collaboration
- GitHub Flow 기반 브랜치 전략 사용 (feature / fix / main)
- 코드 리뷰 주도 및 공통 코드 스타일·로그 규칙 합의
- 협업 시 API 명세서 문서화 및 팀 단위 트러블슈팅 담당

---

## 🎓 Education
**신안산대학교 컴퓨터정보과 (2020–2024)**  
- 전공: 소프트웨어 개발 / 웹 애플리케이션 구조  
- 주요 프로젝트: 웹 플랫폼, 챗봇, 데이터베이스 설계  

---

## 📬 Contact
📧 **Email:** [cyh6280@naver.com](mailto:cyh6280@naver.com)  
🐙 **GitHub:** [@apple231421](https://github.com/apple231421)

---
