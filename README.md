# 장지현입니다. 👋

LLM·RAG 기반 AI 시스템과 에이전트 아키텍처를 중심으로, 서비스를 AI 기반으로 재구성하는 방향으로 역량을 확장하고 있는 엔지니어입니다.

학부 시절에는 공정 데이터 분석과 시계열 예측 문제를 연구하며 `LSTM`, `Transformer` 기반 모델을 직접 구현했습니다. 이후 서비스 기획·개발·운영 전반을 경험하며, 단순 모델 구현을 넘어 AI 기능을 실제 제품 구조에 녹여내는 일에 더 큰 관심을 갖게 되었습니다.

현재는 `LangGraph`, `RAG`, `Vector DB`, `AI Agent Workflow`를 활용해 실제 서비스에서 동작하는 AI 구조를 설계하고, 모바일 앱·웹 프론트엔드·클라우드 인프라까지 연결하는 방식으로 문제를 풀고 있습니다.

## 핵심 역량

- `LangGraph` / `RAG` 기반 AI 에이전트 설계와 검색 파이프라인 구성
- `LSTM` 시계열 예측 연구를 바탕으로 한 데이터 모델링 및 엔지니어링 사고
- `AWS` / `Azure` / `Kubernetes` / `BaaS` 기반 서비스 인프라 확장 경험
- 모바일 앱, 웹, AI 백엔드, 운영 구조를 아우르는 `0 to 1` 서비스 구축 경험

## 기술

### AI · Data
`Python` `PyTorch` `TensorFlow` `OpenCV` `NumPy` `Pandas` `scikit-learn` `Keras` `LangChain` `LangGraph` `OpenAI API`

### Application
`React Native` `React` `Next.js` `TypeScript` `Flutter` `Dart` `Vite` `Tailwind CSS`

### Infra · Platform
`FastAPI` `Spring Boot` `Spring Cloud Gateway` `Supabase` `Firebase` `Redis` `PostgreSQL` `AWS` `Azure` `Cloudflare` `Docker` `Kubernetes` `GitHub Actions` `OpenTelemetry`

## 현재 확장 중인 영역

- 공공 데이터 기반 추천, CRM 자동화, 대규모 트래픽 방어처럼 서로 다른 문제를 **AI 시스템 설계 관점**으로 풀어내는 일
- 모델 성능 자체보다, 실제 서비스에서 작동하는 **AI 워크플로우와 운영 구조**를 설계하는 일
- 사용자 경험, 데이터 흐름, 인프라 제약까지 함께 고려하는 **서비스형 AI 엔지니어링**

## 핵심 프로젝트

### 1. Kids Chatbot Service Refactor

- 기간: `2025.10 ~ 2025.11`
- 역할: `AI 파트 담당`
- 핵심 기술: `FastAPI` `LangChain` `ChromaDB` `OpenAI Embeddings` `Qwen` `React` `Vite` `Expo` `Kakao Map API`
- 주요 내용:
  - 공공 데이터와 외부 검색을 결합한 **키즈 액티비티 추천 챗봇**의 RAG 검색 구조를 설계했습니다.
  - 프롬프트 엔지니어링, 대화 상태 관리, 검색 결과 후속 질문 흐름을 정리해 챗봇 응답 경험을 개선했습니다.
  - 임베딩 진단과 평가 스크립트까지 포함해 AI 응답 품질을 점검할 수 있는 구조를 함께 구축했습니다.
- GitHub: [kids-chatbot-service-refactor](https://github.com/wkdwlgus/kids-chatbot-service-refactor)

### 2. CRM Message Generator

- 기간: `2025.11 ~ 2026.01`
- 역할: `팀장 · 이너/아우터 아키텍처 설계 및 AI 워크플로우 총괄`
- 핵심 기술: `FastAPI` `LangGraph` `OpenAI` `Supabase` `React` `TypeScript` `Tailwind CSS` `PyTorch`
- 주요 내용:
  - 페르소나 기반 고객 추출부터 추천 상품 조회, 메시지 생성, 법규 준수 검수까지 이어지는 **멀티 에이전트 CRM 흐름**을 설계했습니다.
  - CRM 데이터와 추천 시스템을 연결해 개인화 메시지를 생성하는 **실무형 AI 자동화 구조**를 구현했습니다.
  - Frontend / Backend / RecSys를 분리한 모노레포 구조로 운영하며, 서비스 구조 관점에서 AI 기능을 통합했습니다.
- GitHub: [crm-message-generator](https://github.com/wkdwlgus/crm-message-generator)

### 3. goormgb Traffic Master

- 기간: `2026.01 ~ 2026.04`
- 역할: `팀장 · AI 파트 담당`
- 핵심 기술: `Python` `FastAPI` `LangGraph` `Playwright` `Next.js` `Spring Boot` `Redis` `PostgreSQL` `Docker` `Envoy` `OpenTelemetry`
- 주요 내용:
  - AI Defense Runtime에서 위험도 산출, 티어링, 챌린지, 차단 액션이 연결되는 **방어 의사결정 파이프라인**을 설계했습니다.
  - Playwright 기반 공격 에이전트 스웜과 VQA 보안 챌린지를 구현해 **정상 사용자와 봇 트래픽을 검증하는 실험 환경**을 구축했습니다.
  - Next.js 프론트엔드, Spring Boot 기반 서비스, Python AI 런타임을 연결하고 운영 로그와 관측 구조를 정리했습니다.
- GitHub: [101-goormgb-frontend](https://github.com/goorm-gongbang/101-goormgb-frontend)
