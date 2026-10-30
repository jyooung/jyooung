# 안녕하세요, 백엔드 개발자 박지영입니다 

**장애가 나도 데이터를 잃지 않는 백엔드**를 고민합니다.
AI 서비스를 실제로 운영되는 제품의 백엔드로 만드는 일을 하고 있습니다.

- 🏢 솔트룩스 ProductCenter 백엔드 개발 (2026.03 ~ 2026.09) — AI Agent 플랫폼 초기 제품화
- 🏆 코인 거래소 팀 프로젝트 「수강생이 뽑은 최고의 프로젝트」, 교내 SW 공모전 우수상
- 📫 cherish.yooung@gmail.com

<br>

## 🛠 Tech Stack

**Backend**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)

**Data · Messaging**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

<br>

## 📂 Projects

### 💼 AgentStudio — 엔터프라이즈 AI Agent 플랫폼 `실무 · 사내 비공개`
> 2026.03 ~ 2026.09 · 제품 개발팀 4명 · Python, Flask, PostgreSQL, Elasticsearch, Redis, Celery

- 사내 공통 Agent 실행 엔진과 제품을 잇는 **HTTP/SSE 원격 실행 구조** 구축
- 첨부파일 **비동기 색인·재색인 파이프라인** (Celery 파일별 작업, 상태·Lock 관리, 중단 작업 복구)
- 기술 계층 중심 구조를 **도메인 중심 모듈**로 개편, 순환 참조 해소

### 🪙 코인 거래소 — MSA 기반 거래 플랫폼 · [exchange](https://github.com/jyooung/exchange)
> 2025.04 ~ 2025.05 · 4인 팀 · Java, Spring Boot, Spring Cloud, Kafka, Redis, MySQL, Cassandra

- **담당:** 인증(JWT)·자산(잔액)·주문 취소·체결 조회·Gateway
- 잔액 차감 실패를 **잔액 부족 큐와 DLQ로 분리**하고 DLQ 처리 표준화
- 🏆 수강생이 뽑은 최고의 프로젝트

### 🎯 FitMe — LLM 기반 의미 매칭 채용·광고 플랫폼 · [fitme](https://github.com/jyooung/fitme)
> 2026.01 ~ 2026.02 · 6인 팀 · Spring Boot, PostgreSQL(pgvector), Redis, OpenAI

- **담당:** 매칭 알고리즘, 광고 서빙 아키텍처
- pgvector 검색 실행 계획 분석으로 HNSW 인덱스 활성화 → **응답 13초 → 0.1초**
- Redis 선차감 + RDB 후정산, TTL 키로 **중복 클릭 과금 방지**

### 🚚 물류·배송 MSA 플랫폼 · [logistics-delivery-msa](https://github.com/jyooung/logistics-delivery-msa)
> 2025.03 · 4인 팀 · Java, Spring Boot, Spring Cloud, Kafka, Redis

- 재고 동시성 제어(비관적 락)와 Redis 캐싱 → **TPS 3745 → 5573 (49% 개선)**, 재고 오류 0%

### 📺 유튜브 영상 개인화 추천 서비스 · [personal-follower](https://github.com/jyooung/personal-follower) `개인`
> Spring Boot, MongoDB, Qdrant, OpenAI, RAG

- 시청 기록에서 관심 키워드를 뽑아 LLM으로 확장하고, 벡터 검색으로 세부 카테고리 추천
- 🏆 교내 SW 공모전 우수상

<br>

## 📜 Certificates · Education
- 정보처리기사 필기 합격 (2025.09)
- AI 고객응대 프로젝트 기반 풀스택 AI 개발자 양성과정 수료 · 우수학습자 (2025.09 ~ 2026.02)
- AI를 활용한 백엔드 아키텍처 심화 과정 수료 (2025.02 ~ 2025.05)
- 배화여자대학교 컴퓨터공학과 학사 (2026.02 졸업)
