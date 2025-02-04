## 🧑‍💻 About Me  
안녕하세요! **Java 백엔드 개발자 변영우**입니다.  
Spring 생태계를 중심으로 **백엔드 아키텍처 설계 및 최적화**에 관심이 많으며,  
다양한 프로젝트에서 데이터 모델링, API 설계 및 성능 개선을 경험했습니다.  

---

## 🛠 Tech Stack  
**Frontend:** JSP, JavaScript, Vue.js  
**Backend:** Java, SpringBoot, SpringBatch, JPA, QueryDSL  
**Database:** MySQL, PostgreSQL, MongoDB, Redis  
**Tools:** Git, Jenkins, RabbitMQ  

---


### 🚀 랠리즈 PLUS - 학원 관리 시스템 고도화 (2024.09 ~ 2024.12)
📍 **회사:** 배컴  

**✔ 프로젝트 개요**  
- 대형 학원을 대상으로 한 학원 관리 기능이 고도화된 서비스 제작

**✔ 내가 한 일**  
- **데이터 모델링:** ERD 설계 및 크레딧 도메인 구조 설계  
- **결제 시스템 구축:** TOSS 결제 모듈 및 NICE PG 연동 코드 리팩토링  
- **API 개발:** 주요 학원 관리 기능 개발 및 크레딧 API 구현  

🏆 **프로젝트 기여도:** **40.2%**  

**🔄 개선 사항**  
- **결제 모듈 추상화:** 파편화된 기존 결제 모듈 연동 코드 추상화 작업으로 **코드 사용성 개선**  

**🖥 Tech Stack**   
`SpringBoot` `SpringBatch` `JPA` `QueryDSL` `MySQL` `MongoDB`

---

### 🚀 회원 연결구조 개선 (2024.02 ~ 2024.08)
📍 **회사:** 배컴  

**✔ 프로젝트 개요**  
- 기존 회원 구조의 문제점 개선 및 가족 연결 방식 변경  
- 초대 코드 기반의 데이터 정합성 향상  

**✔ 내가 한 일**  
- **DB 개선:** 테이블 정규화 및 데이터 정합성 향상  
- **코드 컨벤션 적용:** API 명세 정리 및 코드 컨벤션 정의  
- **기능 개발:** 난수 기반 초대장 시스템 구현  
- **서비스 연동:** Sendbird 데이터 보존 코드 수정  
- **기능 분리:** 가족 초대장 & 학원 초대장 시스템 분리

🏆 **프로젝트 기여도:** **47.2%**

**🔄 개선 사항**  
- **미사용 코드 제거 및 개선:** 사용되지 않는 코드 제거 및 중복 코드 리팩토링을 통한 **리소스 개선**
- **회원 연결 보안 강화:** 초대장 난수를 통해 가족 연결되므로 **임의의 연결 방지**  
- **데이터 정합성 향상:** 회원 연결 시, **트랜잭션 적용하여 일관성 유지**  

**🖥 Tech Stack**   
`SpringBoot` `SpringBatch` `JPA` `QueryDSL` `MySQL` `MongoDB`

---

### 🚀 미확인 게시물 PUSH 발송 (2023.12 ~ 2024.01)
📍 **회사:** 배컴

**✔ 프로젝트 개요**  
- 앱 내 피드 대상자 중 2일 동안 확인하지 않은 게시물에 대해 자동 푸시 발송  

**✔ 내가 한 일**  
- **알림 시스템 구축:** 2일 이상 확인되지 않은 게시물 자동 푸시 발송  
- **Firebase 연동:** 공용 라이브러리 개발 및 푸시 발송 기능 추가  
- **자동화:** 스케줄러 기반 푸시 발송 로직 구현 

🏆 **프로젝트 기여도:** **100% (단독 개발)**  

**🔄 개선 사항**  
- **푸시 발송 성능 개선:** 개별 발송에서 **비동기 Bulk Push 전송 방식**으로 변경하여 API 호출 비용 90% 절감  
- **리소스 확보:** 해당 작업을 위해 기획자의 1MD가 소요되지만 자동화 작업으로 **일일 5천건 발송에 약 10초 소요**  

**🖥 Tech Stack**   
`SpringBoot` `SpringBatch` `JPA` `QueryDSL` `MySQL` `MongoDB`  

---

### 🚀 현장강의 무한패스 (2023.03 ~ 2023.07)
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 학원 현장 강의 영상 다시보기 서비스 구축  
- Kollus 솔루션 활용한 동영상 관리 시스템  

**✔ 내가 한 일**  
- **DB 설계:** ERD 설계 및 데이터 모델링  
- **API 개발:** 강의 조회 및 영상 관리 API 구현  
- **서비스 최적화:** 서비스 품질 개선을 위한 기획 참여  
- **자동화:** 제공 기간 만료 영상 자동 처리 시스템 개발 

🏆 **프로젝트 기여도:** **43.7%**  

**🔄 개선 사항**  
- **강의 데이터 조회 속도 40% 개선:** JPA Fetch Join 활용하여 **N+1 문제 해결**  
- **영상 관리 최적화:** 비효율적인 파일 관리 로직을 개선하여 **파일 접근 시간 30% 단축**  

**🖥 Tech Stack**   
`Java` `SpringBoot` `SpringBatch` `JPA` `QueryDSL` `Mybatis` `PostgreSQL` `JSP` `JQuery` `Vue.js` 

---

### 🚀 모지 결제 시스템 구축 ( 2022.10 ~ 2022.11 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 신규 서비스인 모지의 결제 시스템 구축

**✔ 내가 한 일**  
- **로그 시스템 구축:** 통합 로그 설계 및 데이터 추적 기능 구현  
- **회원 인증 연동:** 통합회원 시스템과 결제 모듈 연동  
- **API 개발:** 포인트 도메인 API 설계 및 개발  

🏆 **프로젝트 기여도:** **33.4%**  

**🖥 Tech Stack**   
`Java` `Spring` `Mybatis` `MySQL` `Redis`

---

### 🚀 플랫폼 통합회원 연동 ( 2022.05 ~ 2022.10 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 이투스 소속 자회사에 각 서비스들의 회원들을 하나의 회원으로 통합하는 작업

**✔ 내가 한 일**  
- **프로젝트 매니징:** Project Manager 역할 수행  
- **회원 인증 방식 개선:** Cookie 인증 → JWT 토큰 기반 API 변경  
- **통합 회원 API 개발:** 여러 플랫폼의 회원을 하나의 계정으로 통합하는 시스템 구축

🏆 **프로젝트 기여도:** **88.5% (리드 개발)**  

**🔄 개선 사항**  
- **API 응답 속도 35% 개선:** JWT 기반 인증 캐싱하여 **토큰 검증 시간 단축** 
- **데이터 정합성 개선:** 통합 회원 데이터 동기화 문제 해결
  
**🖥 Tech Stack**   
`Java` `Spring` `SpringBoot` `JPA` `QueryDSL` `Mybatis` `PostgreSql` `JSP` `JQuery` `Vue.js`

---

### 🚀 네오 원격지점 신설 및 강의 다시보기 서비스 ( 2022.01 ~ 2022.03 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 메타버스 학습 앱 “엘리펀”에 대응되는 지점 신설
- 원격 지점 재원생에게 강의 다시보기 서비스 기능 제공

**✔ 내가 한 일**  
- **DB 설계:** 강의 다시보기 시스템을 위한 ERD 설계  
- **API 개발:** 강의 조회 및 학습 데이터 관리 API 구현  
- **프론트엔드 작업:** 학습 UI 및 강의 리스트 화면 작업 

🏆 **프로젝트 기여도:** **100% (단독 개발)**  

**🔄 개선 사항**  
- **강의 조회 속도 최적화:** SQL 인덱싱 추가 및 **QueryDSL 최적화로 성능 30% 개선**  
- **메타버스 플랫폼 연동 최적화:** API 호출 수 줄이고 **데이터 요청 최소화**  
- **강의 접근 권한 강화:** Redis 기반 인증 캐싱으로 **불필요한 DB 조회 최소화**  

**🖥 Tech Stack**   
`Java` `Spring` `SpringBoot` `JPA` `QueryDSL` `Mybatis` `PostgreSQL` `Redis` `Vue.js`

---

### 🚀 강남앤써 지점이관 및 네오 게이트 신설 ( 2021.10 ~ 2021.12 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 강남 앤써 학원이 강남 네오 학원으로 변경 및 네오 게이트 신설

**✔ 내가 한 일**  
- **데이터 마이그레이션:** 신규 지점 데이터 생성 및 기존 데이터 수정 작업  
- **프론트엔드 작업:** 신규 학원 페이지 및 사용자 화면 개발  

🏆 **프로젝트 기여도:** **100% (단독 개발)**  

**🔄 개선 사항**  
- **지점 변경에 따른 API 최적화:** 기존 학원 API 구조를 **모듈화하여 유지보수 용이성 증가**  

**🖥 Tech Stack**   
`Java` `Spring` `SpringBoot` `JPA` `QueryDSL` `Mybatis` `PostgreSQL` `GraphQL` `Node.js` `Handlebars.js`

---

### 🚀 이투스네오 FB 분리 ( 2021.03 ~ 2021.09 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- Client-Server Architecture로 전환

**✔ 내가 한 일**  
- **프레임워크 전환:** Spring + JSP 기반 시스템을 Frontend & Backend 구조로 분리  
- **백엔드 개발:** SpringBoot & JPA 기반의 입력 API 서버 구축  
- **GraphQL API 설계:** Express.js 기반의 조회 전용 GraphQL API 개발  
- **코드 리팩토링:** 신규 프레임워크 환경에 적합한 코드로 개선  

🏆 **프로젝트 기여도:** **70% (핵심 기여자)**  

**🔄 개선 사항**  
- **API 응답 속도 45% 개선:** REST API에서 **GraphQL 기반으로 변경하여 데이터 요청 최적화**  
- **SPA 환경 최적화:** 기존 JSP 페이지 로드 방식에서 **Node.js 기반 SSR(Server Side Rendering) 적용**

**🖥 Tech Stack**   
`Java` `Spring` `SpringBoot` `JPA` `QueryDSL` `Mybatis` `PostgreSQL` `GraphQL` `Node.js` `Handlebars.js`

---

### 🚀 LMS&클래스룸 고도화 ( 2020.09 ~ 2020.12 )
📍 **회사:** 이투스교육

**✔ 프로젝트 개요**  
- 정해져 있는 시간표가 아닌 학생들이 강좌를 선택해 자신만의 시간표를 만들어 수강 신청이 가능하게 만들고 오프라인 재원생의 강좌 출결 기능 제공

**✔ 내가 한 일**  
- **강좌 관리 시스템 개선:** 수강신청 인원 변화에 따른 상태 업데이트 로직 개발  
- **대기열 시스템 구축:** 수강 제한 인원 초과 시 대기번호 발급 알고리즘 설계  
- **출석 관리:** 학생 출결 데이터 관리 및 출석부 UI 개발  

🏆 **프로젝트 기여도:** **30%**  

**🔄 개선 사항**  
- **수강 신청 속도 30% 개선:** 수강 신청 시 **비동기 처리 도입하여 트랜잭션 지연 문제 해결**  
- **대기열 로직 최적화:** 기존 선착순 방식에서 **Priority Queue(우선순위 큐) 기반 대기열 시스템 적용**  
  
**🖥 Tech Stack**   
`Java` `Spring` `SpringBoot` `Mybatis` `PostgreSQL` `JSP` `JQuery`

---

## 🔗 Contact  
📫 **Email:** byw1666@gmail.com  
