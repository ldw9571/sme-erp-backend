# SME ERP Backend API

중소기업용 ERP 백엔드 API 프로젝트입니다.  
PHP 실무 2년 경험을 바탕으로 **Java Spring Boot 환경에서의 기업용 백엔드 구조**와  
**ERP 시스템의 데이터 흐름 및 데이터 정합성 처리 방식**을 학습·구현하는 것을 목표로 합니다.

본 프로젝트는 단순 CRUD 예제가 아닌,  
**실제 기업용 ERP 시스템을 가정한 도메인 설계, 트랜잭션 처리, 개발/운영 환경 분리**를 중심으로 설계합니다.

---

## 🎯 프로젝트 목표

- Java + Spring Boot 기반 백엔드 아키텍처 이해
- ERP 핵심 도메인 설계 경험
- 트랜잭션 기반 데이터 정합성 처리
- 실무에 가까운 REST API 설계
- 개발 환경과 서버 환경 분리 경험
- 서버 실행 및 배포 흐름 이해

---

## 🛠 기술 스택

- **Java 17**
- **Spring Boot 3.x**
- **Spring Data JPA**
- **MySQL**
- **Gradle**
- **IntelliJ IDEA**
- **Git / GitHub**
- Linux (Home Server)

---

## 📦 핵심 도메인 설계

| 도메인 | 설명 |
|------|------|
| Company | 회사 정보 관리 |
| User | 직원 계정 및 권한 관리 |
| Client | 거래처 관리 |
| Invoice | 매출 / 매입 관리 |
| InvoiceItem | 거래 상세 항목 |

> ERP 기본 구조인  
> **회사 → 거래처 → 매출/매입 → 정산** 흐름을 중심으로 설계합니다.

---

## 🖥 개발 & 실행 환경 구성

본 프로젝트는 실무 환경과 유사하게  
**개발 환경(Local PC)과 실행 환경(Server)을 분리**하여 구성했습니다.

### 📍 개발 환경 (Local PC)

- IntelliJ IDEA
- Java 17
- Spring Boot
- 코드 작성 및 디버깅
- Git 커밋 및 GitHub 푸시

### 📍 실행 환경 (Home Server)

- Linux 기반 홈서버
- Java 17
- MySQL
- Spring Boot 애플리케이션 실행
- 실제 서버 환경 기준 API 테스트

> 홈서버를 개발 서버로 사용하여  
> 로컬 환경과 분리된 상태에서 애플리케이션을 실행하고 검증합니다.

---

## 🔄 개발 & 배포 흐름

