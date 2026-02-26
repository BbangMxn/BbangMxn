<div align="center">

# BbangMxn

**Backend & Systems Developer**

Building high-performance backends and IoT platforms with Rust, Go, and Java

[![Email](https://img.shields.io/badge/Email-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white)](mailto:BbangMxn6484@outlook.kr)
[![Portfolio](https://img.shields.io/badge/Portfolio-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/BbangMxn)

</div>

---

## Tech Stack

<div align="center">

### Languages
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### Backend Frameworks
![Axum](https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=go&logoColor=white)

### Frontend & Mobile
![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

### Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=for-the-badge&logo=timescale&logoColor=black)

### IoT & AI
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![OPC UA](https://img.shields.io/badge/OPC_UA-0066CC?style=for-the-badge)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

</div>

---

## Featured Projects

### Worker — AI-Powered Work Automation Platform
> AI 기반 이메일/캘린더/연락처 통합 워크스페이스 (Superhuman 스타일)

**Monorepo: Go Backend + Next.js Frontend**

| Component | Tech Stack |
|-----------|-----------|
| Backend API | ![Go](https://img.shields.io/badge/Go_1.24-00ADD8?style=flat&logo=go&logoColor=white) ![Fiber](https://img.shields.io/badge/Fiber_v2-00ACD7?style=flat) Hexagonal Architecture |
| Frontend | ![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| AI/LLM | ![OpenAI](https://img.shields.io/badge/GPT--4o--mini-412991?style=flat&logo=openai&logoColor=white) pgvector RAG, 7-Stage Classification |
| Database | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) Neo4j |

**Key Features**
- AI Agent: 자연어 명령으로 이메일 전송/캘린더 생성 (Proposal 기반 안전 실행)
- 7-Stage Classification Pipeline: RFC 헤더 분석으로 LLM API 비용 ~75% 절감
- Gmail Pub/Sub 실시간 동기화 + SSE 브로드캐스트
- RAG 개인화: 사용자 문체 학습 기반 답장 생성
- Worker Pool: Redis Streams, 자동 스케일링 (2~20 goroutines)

[Repository](https://github.com/BbangMxn/worker)

---

### BagInCoffee — Coffee Community Platform
> 커피 애호가를 위한 종합 커뮤니티 플랫폼

**Full-Stack Multi-Platform Service**

| Component | Tech Stack |
|-----------|-----------|
| 📱 Mobile App | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white) Riverpod |
| Web Client | ![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat&logo=svelte&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| Backend API | ![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white) ![Axum](https://img.shields.io/badge/Axum-000000?style=flat) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) Redis |

**Key Features**
- 소셜 피드 & 중첩 댓글 시스템
- 커피 장비 데이터베이스 (다국어 JSONB)
- 중고거래 마켓플레이스
- 매거진 & 가이드 콘텐츠

[BagInCoffee Web](https://github.com/jixso6484/BagInCoffee) · [BagIn API](https://github.com/BbangMxnUser/BagInDB)

---

### Nazgul — Hobby-based Social Matching
> 취미 기반 소셜 매칭 플랫폼

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat)

**Architecture**
- Frontend: React + TypeScript + Supabase Auth
- Backend: Spring Boot + JPA + PostgreSQL
- Real-time updates with WebSocket

[Repository](https://github.com/BbangMxn/Nazgul)

---

### Backend_Type_A — Hexagonal Architecture Backend
> 헥사고날 아키텍처 기반 소셜 플랫폼 백엔드

![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Architecture Highlights**
- Domain-Driven Design (DDD)
- Ports & Adapters Pattern
- Clean separation of concerns
- Test-friendly architecture

[Repository](https://github.com/jixso6484/Backend_Type_A)

---

### Deuktaem — Real-time Discount Tracking
> 실시간 할인 추적 시스템

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Axum](https://img.shields.io/badge/Axum-000000?style=flat)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Performance Optimization**
- Redis caching → **70% faster API response**
- 30+ RESTful endpoints
- 상품/브랜드/매장 구독 시스템
- 실시간 쿠폰 & 할인 모니터링

[Repository](https://github.com/jixso6484/deuktaem)

---

### Forge — Terminal AI Coding Agent
> Rust 기반 터미널 AI 코딩 에이전트

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Monorepo](https://img.shields.io/badge/Monorepo-7C3AED?style=flat)

**Monorepo Architecture** (7 Crates)
- CLI interface with Ratatui TUI
- Code analysis & generation
- Multi-LLM integration
- Workspace management

[Repository](https://github.com/jixso6484/forge)

---

### Sexy Crawling System — AI-Powered Stealth Crawler
> AI 기반 지능형 웹 크롤러

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![Qwen](https://img.shields.io/badge/Qwen_3-FF6B6B?style=flat)

**AI-Driven Features**
- Qwen3 1.7B LLM integration (ONNX)
- Bot detection evasion system
- Real-time price tracking
- Automatic pattern learning

[Repository](https://github.com/jixso6484/sexy-crawling-system)

---

### SmartFactory — IoT Monitoring Platform
> 스마트팩토리 IoT 모니터링 플랫폼

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat&logo=timescale&logoColor=black)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat)
![OPC UA](https://img.shields.io/badge/OPC_UA-0066CC?style=flat)

**System Architecture**
```
센서 → Data Collector → Pipeline → TimescaleDB → WebSocket → Dashboard
         (MQTT/OPC-UA)              (Go)                        (React)
```

**Features**
- Multi-protocol data collection (MQTT, OPC-UA)
- Time-series data pipeline
- Real-time OEE (Overall Equipment Effectiveness) analysis
- WebSocket-based live dashboard

[Repository](https://github.com/BbangMxn/smartfactory)

---

### SmartPack — Smart Factory Production System
> 스마트팩토리 IoT 생산 시스템

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat)

**Production-Ready IoT Platform**
- OPC UA / MQTT data collection
- Real-time OEE analytics
- Multi-channel alerting (Email, Slack, SMS)
- WebSocket dashboard

---

## Research & Study Projects

### Cache Research — Cache Replacement Algorithm Benchmark
> 캐시 교체 알고리즘 구현 및 벤치마크 연구

![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)

**Research Achievements**
- ✅ **20+ cache algorithms** implemented (LRU, ARC, LIRS, TinyLFU, W-TinyLFU, etc.)
- ✅ **8 hybrid algorithms** designed and tested
- ✅ **40+ workload scenarios** benchmarked
- ✅ **3 language implementations** (C, Java, Go) for performance comparison

**Algorithms Covered**
- Classic: LRU, LFU, FIFO, Random, Clock
- Advanced: ARC, CAR, LIRS, 2Q
- Modern: TinyLFU, W-TinyLFU, S3-FIFO
- Custom hybrids: LRU-LFU, ARC-LFU variants

[Repository](https://github.com/BbangMxn/Cache_Research)

---

## All Projects

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| [Worker](https://github.com/BbangMxn/worker) | AI 이메일/캘린더 자동화 플랫폼 | Go, Next.js, OpenAI, pgvector | Active |
| [BagInCoffee](https://github.com/jixso6484/BagInCoffee) | 커피 커뮤니티 플랫폼 | Flutter, SvelteKit, Rust | Active |
| [Nazgul](https://github.com/BbangMxn/Nazgul) | 취미 기반 소셜 매칭 | React, Spring Boot | Active |
| [Backend_Type_A](https://github.com/jixso6484/Backend_Type_A) | 헥사고날 아키텍처 백엔드 | Java, Spring Boot | Complete |
| [Deuktaem](https://github.com/jixso6484/deuktaem) | 실시간 할인 추적 | Rust, Axum, Redis | Active |
| [Forge](https://github.com/jixso6484/forge) | 터미널 AI 코딩 에이전트 | Rust (Monorepo) | Active |
| [Sexy Crawling](https://github.com/jixso6484/sexy-crawling-system) | AI 웹 크롤러 | Rust, ONNX, Qwen3 | Active |
| [SmartFactory](https://github.com/BbangMxn/smartfactory) | IoT 모니터링 플랫폼 | Go, TimescaleDB | Active |
| [SmartPack](https://github.com/jixso6484/smartpack) | 스마트팩토리 생산 시스템 | Go, MQTT, OPC-UA | In Dev |
| [Cache Research](https://github.com/BbangMxn/Cache_Research) | 캐시 알고리즘 연구 | C, Java, Go | Complete |

---

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=BbangMxn&show_icons=true&theme=graywhite&hide_border=true&hide_title=true&hide_rank=true)

</div>
