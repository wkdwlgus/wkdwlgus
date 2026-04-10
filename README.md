# 안녕하세요, 장지현입니다. 👋

AI 모델을 실제 서비스에 안정적으로 연결하는 백엔드 개발자를 지향합니다.  
RAG, AI 에이전트 워크플로우, 실시간 트래픽 방어, 관측 가능한 시스템 설계에 관심이 많습니다.

## 🛠️ Tech Stack

### 🚀 Programming & AI
`Python` `Java` `TypeScript` `Dart` `PyTorch` `TensorFlow` `OpenCV` `NumPy` `Pandas` `scikit-learn` `Keras` `LangChain` `LangGraph` `OpenAI API`

### 🌐 Backend & Cloud
`FastAPI` `Spring Boot` `Spring Cloud Gateway` `Redis` `PostgreSQL` `Supabase` `Firebase` `AWS` `Cloudflare` `GitHub Actions` `Docker`

### 🖥️ Frontend & Platform
`React` `Next.js` `Vite` `Tailwind CSS` `Zustand` `Playwright` `OpenTelemetry`

### 📱 Mobile & IoT
`Flutter` `Dart` `Android` `React Native` `Expo` `Firebase` `ESP32-CAM`

### 🤝 Collaboration & Tools
`Git` `GitHub` `GitHub Actions` `Jira` `Docker` `Swagger`

## 📚 Learning & Interests

- 현재 **KT Cloud TECH-UP Backend Program 1기**에 참여하며 백엔드 아키텍처와 클라우드 네이티브 개발을 학습하고 있습니다.
- **Java Spring Framework**, **Spring Boot**, **Kotlin**을 중심으로 서비스 설계 역량을 확장하고 있습니다.
- 컴퓨터 비전 배경을 바탕으로, 실시간 AI 추론과 백엔드 시스템을 연결하는 **AI 서비스 개발자**로 성장하는 것을 목표로 하고 있습니다.

## 🚀 핵심 프로젝트

### 1. Kids Chatbot Service Refactor | 가족 나들이 추천 AI 챗봇

- 기간: `2025.11 ~ 2025.12`
- 역할: `AI 파트 담당 · RAG 파이프라인 설계 · 프롬프트 엔지니어링 · 챗봇 대화 흐름 설계 · AI 기술 스택 선정`
- 핵심 기술: `FastAPI` `LangChain` `ChromaDB` `OpenAI Embeddings` `Qwen` `React` `Vite` `Expo` `Kakao Map API`
- 주요 내용:
  - 가족 나들이 추천 시나리오에 맞춘 **RAG 검색 파이프라인**을 설계하고, 시설/프로그램 데이터를 기반으로 한 추천 응답 흐름을 구현했습니다.
  - **프롬프트 엔지니어링**과 대화 상태 관리를 통해 후속 질문이 자연스럽게 이어지는 챗봇 경험을 설계했습니다.
  - 날씨, 웹 검색, 지도 연동과 함께 **평가 스크립트 및 임베딩 진단 도구**를 포함해 AI 응답 품질을 점검할 수 있는 구조를 정리했습니다.
- GitHub: [kids-chatbot-service-refactor](https://github.com/wkdwlgus/kids-chatbot-service-refactor)

---

### 2. CRM Message Generator | 초개인화 CRM 메시지 생성 시스템

- 기간: `2025.12 ~ 2026.01`
- 역할: `팀장 · 이너/아우터 아키텍처 설계 및 AI 워크플로우 총괄`
- 핵심 기술: `FastAPI` `LangGraph` `OpenAI` `Supabase` `React` `TypeScript` `Tailwind CSS` `PyTorch`
- 주요 내용:
  - **페르소나 기반 고객 추출 → 추천 상품 조회 → 메시지 생성 → 법규 준수 검수**까지 이어지는 AI 에이전트 워크플로우를 설계했습니다.
  - Supabase CRM 데이터와 추천 시스템을 연결해 **초개인화 CRM 메시지**와 타겟 고객군을 자동 생성하는 구조를 구현했습니다.
  - Frontend / Backend / RecSys를 분리한 모노레포 구조로 운영하며, 실제 마케팅 실무 흐름에 맞는 **AI CRM 어시스턴트** 형태로 정리했습니다.
- GitHub: [crm-message-generator](https://github.com/wkdwlgus/crm-message-generator)

---

### 3. goormgb Traffic Master | 예매 트래픽 방어 시스템

- 기간: `2026.01 ~ 진행 중`
- 역할: `팀장 · AI 파트 담당 · 이너/아우터 아키텍처 설계 · AI Defense/Attack 워크플로우 총괄`
- 핵심 기술: `Python` `FastAPI` `LangGraph` `Playwright` `Next.js` `Spring Boot` `Redis` `PostgreSQL` `OpenTelemetry` `Docker` `Envoy`
- 주요 내용:
  - **AI Defense Runtime**에서 `/evaluate` 기반 위험도 산출, 티어링, 챌린지, 차단 액션이 연결되는 방어 의사결정 파이프라인을 설계했습니다.
  - **Playwright 기반 공격 에이전트 스웜**과 VQA 보안 챌린지를 구현해 정상 사용자와 봇 트래픽을 검증하는 실험 환경을 구축했습니다.
  - **Next.js 프론트엔드 + Spring Boot 마이크로서비스 + Python AI 런타임**을 연결하고, OpenTelemetry 기반 관측 경로와 운영 로그 구조를 정리했습니다.
- GitHub: [101-goormgb-frontend](https://github.com/goorm-gongbang/101-goormgb-frontend) | Private Modules: `201-goormgb-ai`, `203-goormgb-ai-attack`, `102-goormgb-backend`
