# 👋 정희원 | Backend-focused Fullstack Developer

> 기능 구현을 넘어 데이터 구조와 확장성을 함께 고려하는 개발을 지향합니다.
> Spring Boot 기반 REST API 설계, 실시간 시스템, AWS 배포 경험을 보유하고 있습니다.

---

## 🛠 기술 스택

**Backend**
Spring Boot · JPA · QueryDSL · MyBatis · Spring Security · JWT · WebSocket (STOMP)

**Frontend**
React · React Query · Zustand · Axios

**Database**
MySQL · Redis

**Infra**
AWS (EC2, RDS) · GCP · Docker · Nginx · GitHub Actions

---

## 📂 프로젝트

### 🏃 Route In — 운동 커뮤니티 웹 서비스 (팀 프로젝트)
> 3인 팀 팀장 · 2026.01 ~ 2026.02 (5주)

Kakao Map 기반 러닝코스 공유 + 실시간 채팅 커뮤니티 서비스

- WebSocket(STOMP) 실시간 채팅 · 알림 시스템 설계 및 구현
- `room_read_tb` 분리 설계로 읽음 상태와 메시지 생명주기 분리
- `create_dt + message_id` 복합 커서 기반 페이지네이션으로 성능 확보
- GitHub Actions + Docker 기반 GCP 배포

🔗 [배포 주소](https://routein.store) · [Backend](https://github.com/toma9512/route-in-backend) · [Frontend](https://github.com/toma9512/route-in-frontend) · [Notion](https://well-group-b12.notion.site/31f560d3713f8098b275d7074c98686e)

---

### 🎫 SeatSync — 공연 예약 시스템 (개인 프로젝트 · 바이브 코딩)
> 1인 개발 · 2026.04 (1일) · AI와의 바이브 코딩으로 설계부터 AWS 배포까지 완성

Redis 좌석 선점 동시성 제어와 QueryDSL 복합 필터 검색을 핵심으로 하는 공연 예약 서비스

- Redis `setIfAbsent(NX)` + TTL로 좌석 선점 동시성 구조적 차단
- QueryDSL `BooleanExpression`으로 장르 · 지역 · 키워드 복합 필터 검색 구현
- Spring Scheduler로 만료 예약 자동 취소 및 좌석 상태 복구
- GitHub Actions + AWS EC2/RDS + Nginx CI/CD 파이프라인 구성

🔗 [배포 주소](http://43.201.76.129) · [Backend](https://github.com/toma9512/seatsync-backend) · [Frontend](https://github.com/toma9512/seatsync-frontend)

---

## 🏆 자격증 · 수상

| 취득일 | 내용 | 발급기관 |
|---|---|---|
| 2025.12 | PCCP (Java) **Lv4** 최종합격 | (주)그렙 |
| 2026.01 | 제2회 KIT CODING CHALLENGE **2등** | 코리아IT아카데미 |
| 2026.02 | 정보처리기사 필기합격 | 한국산업인력공단 |
| 2025.12 | PCCE (Java) 최종합격 | (주)그렙 |

---

## 📚 관심 분야

- 실시간 시스템 설계
- 서비스 아키텍처 · 성능 최적화
- Backend API 설계
- CI/CD · 인프라 자동화

---

## 📎 Links

- 🧠 Notion Portfolio: https://well-group-b12.notion.site/31f560d3713f8098b275d7074c98686e
- 📧 gmldnjs985@gmail.com

---

감사합니다 🙂
