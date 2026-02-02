<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=3178C6&center=true&vCenter=true&width=500&lines=Hi+%F0%9F%91%8B+I'm+BbangMxn;Backend+Developer;Rust+%7C+Go+%7C+Java" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Backend Developer</strong><br>
  <em>실시간 데이터 처리 · API 설계 · 시스템 최적화</em>
</p>

<p align="center">
  <a href="mailto:BbangMxn6484@outlook.kr">
    <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white" />
  </a>
</p>

---

## About Me

```yaml
Name: BbangMxn
Role: Backend Developer
Location: Seoul, Korea

Interests:
  - 고성능 API 설계 및 최적화
  - 실시간 데이터 파이프라인
  - 캐시 시스템 연구
  - 스마트팩토리 IoT

Currently:
  - SmartFactory IoT 플랫폼 개발 중
  - 캐시 교체 알고리즘 연구 진행
```

---

## Tech Stack

### Languages & Frameworks

| 분류 | 기술 |
|-----|------|
| **Backend** | Rust (Axum), Go (Gin), Java (Spring Boot) |
| **Frontend** | SvelteKit, React, Flutter |
| **Database** | PostgreSQL, Redis, TimescaleDB |
| **IoT** | OPC UA, MQTT |

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,go,java,ts,svelte,flutter,react,postgres,redis,docker&theme=dark" />
</p>

---

## Projects

### Cache Research - 캐시 알고리즘 연구

> **20+ 캐시 교체 알고리즘 구현 및 벤치마크** | [GitHub](https://github.com/BbangMxn/Cache_Research)

| 항목 | 내용 |
|-----|------|
| **기술** | C, Java, Go |
| **규모** | 20+ 알고리즘, 40+ 워크로드 시나리오 |

**구현 알고리즘**
- 기본: LRU, LFU, FIFO, CLOCK
- 고급: ARC, 2Q, LIRS, W-TinyLFU, S3-FIFO
- 하이브리드: ARC+TinyLFU, SLRU+Hyperbolic

**연구 결과**
| 워크로드 | 최적 알고리즘 | 적중률 |
|---------|-------------|:------:|
| Zipf (α=1.0) | W-TinyLFU | 75.2% |
| Sequential Scan | S3-FIFO | 52.1% |
| Mixed | ARC | 64.2% |

---

### SmartFactory - IoT 모니터링 플랫폼

> **제조 현장 실시간 데이터 수집 및 분석** | [GitHub](https://github.com/BbangMxn/smartfactory)

| 항목 | 내용 |
|-----|------|
| **기술** | Go, TimescaleDB, Redis, MQTT, OPC UA |
| **구조** | research (연구 문서) + smartpack (구현체) |

```
[PLC/센서] → [OPC UA/MQTT] → [Pipeline] → [TimescaleDB]
                                  ↓              ↓
                             [WebSocket] ← [Redis Cache]
                                  ↓
                             [Dashboard]     [Alert] → Slack
```

**주요 기능**
- OPC UA / MQTT 다중 프로토콜 데이터 수집
- 실시간 OEE (가용성 × 성능 × 품질) 자동 계산
- WebSocket 기반 실시간 대시보드
- 이상 감지 및 알림 시스템

---

### BagInCoffee - 커피 커뮤니티 플랫폼

> **풀스택 소셜 플랫폼** | [GitHub](https://github.com/BbangMxn/BagInCoffee)

| 프로젝트 | 기술 |
|---------|------|
| **BagInCoffee-App** | Flutter, Riverpod |
| **BagInCoffee-Web** | SvelteKit, TypeScript |
| **[BagInDB](https://github.com/BbangMxn/BaginDB)** | Rust, Axum, PostgreSQL |

**주요 기능**
- 커피 장비 리뷰 및 레시피 공유
- JSONB 기반 다국어 지원 (한/영/일)
- Cloudflare R2 이미지 업로드
- Redis 캐싱 + 자동 무효화

---

### Nazgul - 소셜 매칭 플랫폼

> **취미 기반 소셜 매칭** | [GitHub](https://github.com/BbangMxn/Nazgul)

| 프로젝트 | 기술 |
|---------|------|
| **client** | React 18, TypeScript, Tailwind CSS |
| **server** | Spring Boot 3, JPA, PostgreSQL |

**주요 기능**
- 44개 취미, 9개 카테고리 기반 매칭
- JWT 인증, 팔로우/팔로워 시스템
- Threads 스타일 미니멀 UI

---

### Deuktaem - 스마트 쇼핑

> **실시간 할인 추적 & 알림** | [GitHub](https://github.com/BbangMxn/deuktaem)

| 항목 | 내용 |
|-----|------|
| **기술** | Rust, Axum, Supabase, Redis |
| **성과** | API 응답 속도 70% 개선 (150ms → 45ms) |

**주요 기능**
- RESTful API 30+ 엔드포인트
- 다중 플랫폼 상품 데이터 통합
- 구독 기반 실시간 알림

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=BbangMxn&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BbangMxn&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" height="165" />
</p>

---

## Core Competencies

| 역량 | 내용 |
|-----|------|
| **API 설계** | RESTful API, 버전 관리, 문서화 |
| **성능 최적화** | Redis 캐싱, 쿼리 최적화, 비동기 처리 |
| **시스템 연구** | 캐시 알고리즘 20+ 구현 및 벤치마크 |
| **IoT 파이프라인** | OPC UA, MQTT, TimescaleDB |

---

## Repository Overview

| 저장소 | 설명 | 기술 |
|--------|------|------|
| [Cache_Research](https://github.com/BbangMxn/Cache_Research) | 캐시 알고리즘 연구 | C, Java, Go |
| [smartfactory](https://github.com/BbangMxn/smartfactory) | 스마트팩토리 IoT | Go, TimescaleDB |
| [BagInCoffee](https://github.com/BbangMxn/BagInCoffee) | 커피 커뮤니티 | Flutter, SvelteKit |
| [BaginDB](https://github.com/BbangMxn/BaginDB) | BagIn API 서버 | Rust, Axum |
| [Nazgul](https://github.com/BbangMxn/Nazgul) | 소셜 매칭 | React, Spring Boot |
| [deuktaem](https://github.com/BbangMxn/deuktaem) | 할인 추적 | Rust, Axum |

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=BbangMxn&color=blueviolet&style=flat-square" />
</p>
