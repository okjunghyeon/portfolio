# 옥정현 | Backend Developer
---


## About Me


### Java, Spring Boot 기반 백엔드 개발자 옥정현입니다.
#### 데이터 정합성과 운영 안정성을 고려한 구조 설계를 경험하며, 안정적인 백엔드 개발자로 성장하기 위해 노력하고 있습니다.

<br>


> **Redis 기반 수강 신청 동시성 제어 및 중복 요청 방지 구조 설계**
> 
> **Elasticsearch 기반 검색/추천 기능 구현 및 검색 응답 속도 개선**
>
> **AWS EC2, Docker, GitHub Actions 기반 배포 및 자동화 경험**
>
> **Sentry-Slack 연동으로 서버 오류를 빠르게 인지할 수 있는 운영 환경 구축**

---

## Tech Stack

### Backend
- Java
- Spring Boot
- Spring Data JPA
- Spring Security
- Spring Cloud
- JWT

### Data
- MySQL
- Redis
- Elasticsearch

### Infrastructure & DevOps
- AWS EC2
- Docker
- GitHub Actions
- Terraform
- Kafka

### Collaboration & Monitoring
- GitHub
- Slack
- Swagger UI
- Sentry
- Notion

---

## Projects

### 1. UniHub

> Redis 기반 동시성 제어와 AWS 배포 자동화를 적용한 대학교 통합 관리 서비스

- **기간**: 2025.05 ~ 2025.06
- **인원**: 백엔드 5명, 프론트엔드 1명
- **담당**: 수강신청 API, Redis 동시성 제어, AWS 인프라 및 배포 자동화
- **기술**: Java, Spring Boot, JPA, MySQL, Redis, Redisson, AWS EC2, Docker, GitHub Actions, Terraform

#### 주요 구현
- Redis INCR/DECR 기반 수강 인원 원자적 증감 처리
- AOP 분산락을 활용한 동일 학생의 중복 수강신청 방지
- 큐 기반 비동기 순차 처리로 DB 트랜잭션 집중 완화
- `REQUIRES_NEW` 트랜잭션 전파를 활용한 락 해제와 DB 커밋 순서 보완
- 스테이징·운영 환경 분리와 GitHub Actions 기반 CI/CD 구축
- 프론트엔드 연동 전 주요 기능과 예외 상황을 검증하는 배포 절차 마련

#### 성과
- 정원 30명 강의에 1,000건의 동시 요청이 발생하는 상황에서도 정합성 확보
- 중복 신청과 정원 초과 가능성을 줄이는 처리 구조 설계
- 반복 배포 자동화와 운영 반영 전 검증 절차 구축

[프로젝트 저장소](https://github.com/okjunghyeon/WEB4_5_GPT_BE)

---

### 2. 연근마켓

> MSA 기반 Kafka 이벤트 아키텍처와 Elasticsearch를 활용한 중고거래 플랫폼

- **기간**: 2025.11 ~ 2025.12
- **인원**: 백엔드 5명
- **담당**: 상품 도메인 API, Elasticsearch 기반 검색·추천 기능
- **기술**: Java, Spring Boot, JPA, Spring Cloud, MySQL, Redis, Elasticsearch, Kafka, AWS EC2, GitHub Actions

#### 주요 구현
- 상품 CRUD 및 거래 상태 관리 API 구현
- Redis Sorted Set 기반 최근 본 상품 관리
- 관심 상품 등록·취소 및 목록 조회 기능 구현
- Elasticsearch 복합 필터와 Nori 형태소 분석기를 활용한 통합 검색
- 유사 상품 및 인기 상품 추천 기능 구현
- Swagger UI 기반 요청·응답 및 성공·실패 케이스 문서화
- Sentry와 Slack을 연동한 배포 서버 오류 알림 시스템 구축

#### 성과
- Elasticsearch 도입으로 기존 RDB 검색 대비 응답 속도 약 70% 개선
- 서버 오류 인지 및 초기 대응 시간을 약 1시간에서 10분으로 단축
- API 명세를 단일 기준으로 관리해 프론트엔드 협업 과정의 반복 확인 감소

[프로젝트 저장소](https://github.com/okjunghyeon/beadv1_1_ctrlz_BE)

---

## Education

### 프로그래머스 백엔드 엔지니어링 데브코스
**2024.12 ~ 2025.06**

- Java, Spring Boot, JPA 기반 웹 백엔드 개발
- RESTful API 설계, 예외 처리, 인증·인가
- GitHub 기반 협업 및 프론트엔드 개발자와의 API 연동

### 프로그래머스 백엔드 단기 심화 데브코스
**2025.10 ~ 2025.12**

- Spring Cloud 기반 MSA 설계와 도메인 분리
- Kafka 기반 비동기 통신
- Elasticsearch 검색 엔진 구축과 조회 성능 개선

---

## Certifications

- **정보처리기사** | 2024.09
- **SQL개발자(SQLD)** | 2023.10

---

 [GitHub](https://github.com/okjunghyeon) · [기술 블로그](https://devoks.tistory.com)
