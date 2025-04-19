# 🌟 [Now, Here](https://www.now-here.site/login/MTAyOTM4NDY)

### 이벤트 기반 매칭 프로그램

![navBar](https://github.com/user-attachments/assets/8f5606ad-1206-4c55-bb47-e1f22538e273)

---

## ✨ 프로젝트 소개

### 🎯 목표
- **Now, Here**는 대학 축제 기간 동안 인기를 끈 무작위 번호팅 이벤트를 온라인으로 구현하는 프로젝트입니다.
- 이벤트 단위로 무작위 매칭을 진행하여, 유저들의 실시간 피드백을 반영하고 개선하는 과정을 거칩니다.
- 긍정적인 시장 반응을 기반으로, 내년 상반기에 결제 기능 등 추가적인 기능을 도입하여 실제 서비스로 출시할 예정입니다.

## 💻 기술적 목표

### 🛠 백엔드
- **유저 매칭 알고리즘**: 실시간 데이터 분석을 기반으로 한 매칭 알고리즘 개선 자동화 구현.
- **DB 성능 최적화**: 
  - 파티셔닝(event_id 기준)을 통한 대용량 데이터 관리로 처리 속도 개선
  - Caffeine 캐시 전략 도입으로 읽기 성능 향상 및 DB 부하 감소
  - 복합 인덱스 설계 및 쿼리 최적화를 통한 응답 시간 단축
- **고성능 및 확장 가능한 DB 아키텍처 구축**: 
  - Master-Slave DB 아키텍처 설계를 통해 로드 밸런싱 구현과 고가용성 보장
  - 트랜잭션 관리 최적화로 시스템 성능 향상
- **대규모 트래픽 대응 성능 테스트**: Postman과 pgAdmin4를 활용한 단계별 성능 모니터링 및 최적화

### 🎨 프론트엔드
- **사용자 경험(UX) 최적화**:
  - 사용자가 앱을 사용할 때 끊김 없는 경험 제공
  - 실시간 알림 & 오프라인 알림림
- **클린 아키텍처 기반 프로젝트 구조**:
  - 각 계층의 명확한 책임과 의존성 방향 정의
  - 의존성 분리를 통한 에러 처리 및 유지 보수성 강화
- **보안 강화**:
  - 라우트 보호를 통한 무단 접근 방지
- **성능 최적화**:
  - API 요청 최적화
  - 조건부 렌더링을 통한 불필요한 DOM 조작 최소화

## 📚 기술 스택

### 백엔드
| Category   | TechStack                                      |
|------------|------------------------------------------------|
| Framework  | SpringBoot, Java                               |
| DB & ORM   | PostgreSQL, JPA(Hibernate)                     |
| Testing    | Postman API Performance Testing, pgAdmin4      |
| API Docs   | SwaggerHub                                     |
| CI/CD      | GitHub Actions                                 |
| Infra      | OracleCloud, Cloudtype                         |
| Caching    | Caffeine                                       |
| DB Pool    | HikariCP                                       |

### 프론트엔드
| Category   | TechStack                                      |
|------------|------------------------------------------------|
| Framework | Vue.js 3, Vite |
| State Management | Pinia, pinia-plugin-persistedstate |
| Routing | Vue Router |
| HTTP Client | Axios |
| UI/UX | SCSS |
| Browser API | Service Worker, FCM |
| Development | Composition API |

### 🔗 링크
[Now, Here Link](https://www.now-here.site/login/MTAyOTM4NDY)

### 📑 노션 링크
[![Notion](https://img.shields.io/badge/Notion-Now_Here-%23000000?style=for-the-badge&logo=notion&logoColor=white)](https://heejohn.notion.site/Now-here-f93e5f11396f44cb8618d7be3d525b9c?pvs=4)

### 🤔 이슈 & PR
[PR & ISSUE](https://github.com/now-here-5/now-here/issues)

## 🚀 기술적 도전

### ⚙️ 백엔드
- **유저 매칭 알고리즘**: 실시간 데이터 기반 매칭 알고리즘 최적화: 동적 조정법 / DB 분석 자동화 [[더 알아보기](https://jun10920.tistory.com/38)]
- **DB 성능 최적화**:
  - **파티셔닝(event_id 기준)을 통한 대용량 데이터 관리**로 처리 속도 개선
  - **Caffeine 캐시 전략 도입**으로 배너 매칭 목록 조회 API 응답 시간 88.33% 향상
  - **복합 인덱스 설계**를 통해 매칭 현황 페이지 조회 속도 43.29% 개선
  - HikariCP 연결 풀 최적화로 연결 고갈 문제 해결 및 전체 성능 39.68% 향상
- **고성능 및 확장 가능한 DB 아키텍처 구축**:
  - Master-Slave DB 아키텍처 설계로 CUD/R 작업 분리 및 로드 밸런싱싱 구현
  - 트랜잭션 관리 최적화(@Transactional(readOnly = true) 적용)로 불필요한 락 방지
- **대규모 트래픽 대응 성능 테스트**:
  - Postman API Performance Testing과 pgAdmin4 Dashboard를 활용한 단계별 성능 모니터링
  - 3단계 최적화 접근법 적용: 1) HikariCP 설정 2) Caffeine 캐싱 3) 인덱싱 및 트랜잭션 최적화
  - 500명 사용자, 25만 매칭 데이터 처리 시나리오에서 평균 응답 시간 52.47%, 90번째 백분위 응답 시간 45.32% 개선

### 🎨 프론트엔드
- **실시간 알림 시스템 고도화**:
  - FCM과 브라우저 알림 API 통합을 통한 실시간 알림 시스템 구현
  - 서비스 워커를 활용한 백그라운드 알림 처리 및 오프라인 지원
  - 오프라인 상태에서의 알림
- **상태 관리 아키텍처 설계**:
  - Pinia와 pinia-plugin-persistedstate 통합으로 상태 지속성 구현
  - 스토어 모듈화를 통한 상태 구조 최적화 및 성능 개선
  - 선택적 상태 지속성으로 메모리 사용량 최적화
- **고급 라우팅 및 인증 시스템**:
  - Vue Router 네비게이션 가드를 활용한 동적 라우트 보호 구현
  - JWT 기반 토큰 관리 시스템 및 자동 로그인 기능 구현
  - 딥링크 처리 및 조건부 리다이렉션을 통한 사용자 경험 최적화
- **API 통신 아키텍처 최적화**:
  - Axios 인터셉터를 활용한 중앙화된 API 통신 시스템 구축
  - 에러 핸들링 및 응답 캐싱을 통한 성능 최적화

## 👨‍👩‍👧‍👦 팀원 소개
| 박준형 | 서희준 | 여인수 | 박신형 | 김혜윤 |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://github.com/jun10920.png" width="100"/> | <img src="https://github.com/HeeJohn.png" width="100"/> | <img src="https://github.com/insu12021202.png" width="100"/> | <img src="https://github.com/HolMoly.png" width="100"/> | <img src="https://github.com/haeyun0327.png" width="100"/> |
| **Backend** | **Backend** | **Frontend** | **Frontend** | **PM** |
| [@jun10920](https://github.com/jun10920) | [@HeeJohn](https://github.com/HeeJohn) | [@insu12021202](https://github.com/insu12021202) | [@HolyMoly](https://github.com/HolMoly) | [@haeyun0327](https://github.com/haeyun0327) |

---

## 🏛️ 서비스 구성

### 🧩 전체 아키텍처 
![now-here](https://github.com/user-attachments/assets/e45aefc8-4761-4e0d-9356-a9d7186d23ad)



### 🛠 배포 아키텍처
- server application 배포 과정 <br>
  ![be_deploy](https://github.com/user-attachments/assets/cfd7c2c0-de1e-4df4-919b-b5322511d5c5)

- client application 배포 과정 <br>
  ![fe_deploy](https://github.com/user-attachments/assets/349f1194-0dba-40e6-afff-8f5f86b26cf7)

### 🏗️ 서버 아키텍처
(서버 아키텍처 다이어그램을 여기에 추가하세요.)

### 🗄️ 데이터베이스 ERD
![db](https://github.com/user-attachments/assets/4f4240d8-888c-4480-8405-da27d6f02a1f)


