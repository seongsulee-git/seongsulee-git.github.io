---
layout: post
title:  "Introduction"
date:   2021-04-09 18:00:00 +0900
categories: Portfolio
order: 1
---

---
# About Me
## Introduction
- 안녕하세요. 2년차 개발자 이성수입니다.
- 성장의 기쁨과 중요성을 아는 개발자입니다.
- 동료와 의견을 나누고 협업의 즐거움을 아는 개발자입니다.

## Contact & Channel
- Email   : dev.leeseongsu@gmail.com

- Github  : [https://github.com/seongsulee-git][seongsu-git]

---
# Skills
## Backend
- Java
- __Spring Boot2__, BX Framework
- __Spring Data JPA__, Querydsl, __MyBatis__
- __Spring Cloud(MSA)__
    * Spring Cloud Config(JDBC Backend)
    * Spring Cloud Netflix (Eureka, Zuul, Hystrix)
    * Spring Cloud Bus
- Junit4, Junit5
- Gradle, Maven
- IntelliJ, Eclipse(STS), Visual Studio Code
- Git, Sourcetree, Serena Dimension

## Frontend
- HTML5, __JS(ES6)__, jQuery
- __Vue.js__
- Vuex
- Canvasjs(Chart Lib)

## DevOps
- __MySQL, MariaDB, Oracle__
- Jenkins
- Tomcat
- __k8s, Docker__


---
# Work Experience & Projects

## Company 1 : Growth (2019.08.01. ~ 2020.11.13.)
- 회사 소개 : 성남시 분당구 소재 SI 및 인프라 구축 전문 기업 (2021.03. 서원정보로 인수합병)

### Project 1 : 제조지능화통합플랫폼 프로젝트 IAM 모듈 개발 (2019.08.01. ~ 2019.12.31.)
- 프로젝트 개요 : 제조공정에 대한 실시간 모니터링 및 통계 데이터 기반 시각화 기능 제공

- Spring Boot 2 기반 Java Restful API 개발

- Vue.js 기반 UI 기능 개발

- MyBatis > Spring Data JPA 전환

- Jira, Bitucket, Jenkins를 통한 티켓 관리 및 배포 

- 주요 구현 기능
1. 회원 관리 및 JWT 기반 인증
2. 그룹 기반 권한 기능
3. 사이트 관리, 공지사항

### Project 2 : 제조지능화통합플랫폼 프로젝트 차트 성능 개선 (2020.02.01. ~ 2020.06.30.)
- 프로젝트 개요 : 제조공정에 대한 실시간 모니터링 및 통계 데이터 기반 시각화 기능 제공

- 성능 이슈 분석 (차트 라이브러리 리서치)
    * 대용량 데이터 작업시 SVG 기반 대비 Canvas 기반 라이브러리 성능 분석
    * Vue.js 반응형 속성에 대한 메모리 소모 분석

- 성능 이슈 트러블 슈팅
    1. Select 태그 대체 (대용량 데이터 페이지에서는 성능 저하 발생)
    2. Canvas 기반 신규 컴포넌트 개발
        * 기존 : SVG 기반 Wijmo 차트 이용 커스텀 차트 컴포넌트
        * 변경 : Canvas 기반 Canvasja 차트 이용 커스텀 차트 컴포넌트
    3. Vue.js 반응형 속성을 제거하기 위한 Object.freeze() 작업 진행 (대용량, 읽기 전용)

- 성능 개선 결과 
  * 10만건 기준 JSHeapSize 개선 : __3.0GB -> 500MB__
  * 15만건 기준 Out of Memory -> __100만건 기준 2.8GB JSHeapSize 개선__

- Jira, Bitucket, Jenkins를 통한 티켓 관리 및 배포 자동화

### Project 3 : 클라우드 플랫폼 프로젝트 MSA 환경 세팅, IAM, Config 모듈 개발(2020.04.01. ~ 2020.11.13.)
- 프로젝트 개요 : Nutanix 서버 기반 클라우드 자동화 플랫폼 개발

- Spring Cloud Netflix 기반 __MSA 개발환경 세팅__

- Spring Cloud Config(JDBC Backend) 기반 __무중단 Config 변경 기능__ 세팅

- 담당 모듈 기획

- Spring Boot 2 기반 Java Restful API 개발

- Vue.js 기반 UI 개발

- Jacoco, SonarQube 이용 코드 최적화, 코드 커버리지 90% 이상 달성

- Junit5 기반 테스트 코드 작성

- Redmine, Gitlab, Jenkins를 통한 티켓 관리 및 배포 자동화

- Docker, k8s 환경에서 개발 경험 (Pod 정상 유무 확인, 로그 확인 등)
  * 각 모듈별 Docker File 테스트 및 설정 가이드 작성 

- IAM 모듈 주요 기능
  * JWT 기반 인증 기능
  * 회원 관리 (AD 연동 포함) 및 로그인
  * 권한 관리 및 확인
  * 프로젝트 관리 (클라우드 신청 단위)
  * 프로젝트 정보 변경 시 RabbitMQ 이용 다른 모듈 Flag 전송

- Config 모듈 주요 기능
  * 프로젝트 초기 설정 기능
  * 프로젝트 공통 설정 기능

## Company 2 : Cyber Logitec (2020.11.16 ~ )
- 회사 소개 : 마포구 상암동 소재 해운 물류 솔루션 개발 및 운영 기업

### 제품 ITO
- 담당 업무 1 : ALLEGRO Web Service
  * 선사의 고객들이 서비스 신청을 위한 사이트 기능 제공
  * 주요 기능 : 서비스 신청, 화물 추적, 요금 계산, 메일링 서비스

- 담당 업무 2 : ALLEGRO E-Booking
  * 담당 업무 1에 대한 제품 인터페이스 기능 (선사 사용)
  * 다양한 모듈과 연관되어 있어 해당 모듈 담당자와 연계하여 업무 진행

### Project 1 : 신규 고객사 1 프로젝트 (2020.11.16. ~ 2021.01.15.)
- ALLEGRO 기능에 대한 신규 고객사 맞춤 기능 개발 및 수정

### Project 2 : 신규 고객사 2 프로젝트 (2021.01.18. ~ )
- ALLEGRO 기능에 대한 신규 고객사 맞춤 기능 개발 및 수정

- 한국형 비즈니스 모델에 대한 기능 도입

- Web Service Renewal 작업 병행

- Web Service 형상 관리 담당 (Gitlab, Nexus, Jenkins)

---
# Education
## 학점은행제 (2009.03. ~ 2011.02.)
  - 컴퓨터공학 학사 취득
  - CS 과목 수강

## 한양대학교 편입학 (2012.03. ~ 2018.02.)
  - 컴퓨터전공 학사 취득
  - CS 과목 수강
  - 졸업 프로젝트 중위작 수료 (2017.03. ~ 2017.11.)
    * 프로젝트 개요 : 라즈베리파이 기반 강의/교육용 플랫폼 개발
    * 담당 : Express.js 기반 강의용 서버 및 클라이언트 개발 

## 국비지원교육 수료 : 스마트 디바이스 기반 IoT 응용SW 개발자 양성 (2018.07.16. ~ 2019.01.15.)
  - Java, Javascript, Html, CSS, Jquery
  - Spring Framework
  - Android, Arduino
  - 최종 프로젝트 우수작 수료 (2018.12. ~ 2019.01.)
    * 원격 유아 수면 상태 확인 프로젝트 (Arduino(센서), Android, PC 이용)
    * 담당 업무 : 프로젝트 리더, Backend 개발

## 온라인 강의 수강
  - 수료
    * 예제로 배우는 스프링 입문(개정판) - 백기선
    * 스프링 프레임워크 핵심 기술 - 백기선
    * Vue.js 시작하기 - Age of Vue.js - 캡틴판교
    * Vue.js 완벽 가이드 - 실습과 리팩토링으로 패우는 실전 개념 - 캡틴판교
  - 진행
    * 스프링 부트 개념과 활용 - 백기선

---
# Certificate
## Cos Pro C 1급 - 2019.04.21. 취득
## 정보처리기사 - 2018.11.16. 취득
## 컴퓨터운용사 - 2010.08.18. 취득

---
# ETC
## 독서
### 최근 읽고 있는 책
- Test-Driven Development : By Example (켄트 벡 지음)

### 과거 읽은 책
- 동료를 뒷목 잡게 만드는 나쁜 프로그래밍 습관 (칼 비쳐 지음)
- 모던 자바 인 액션 (라울 외 공동 지음)
- 리팩터링 2판 (켄트 벡 지음)
- 그 외 다수

### 앞으로 읽을 책
- 클린코드 (로버트 C 마틴 지음)

## 군 경력 - 학사장교 복무 (2012.07.01. ~ 2015.06.30.)
- 정보통신병과
- 사관후보생 (2012.03.05. ~ 2012.06.30.) : 군사기초훈련
- 정보통신학교 (2012.07.01. ~ 2012.10.31.) : 정보통신교육
  * 네트워크 관련 교육 수강
- 야전
  * 통신단 예하대대 본부중대장 (2012.11. ~ 2013.11.)
  * 통신단 예하대대 노드소대장 (2013.12. ~ 2015.06.)
    * 최전방 노드 통신소 파견(8주) 2회 (2014.04. , 2014.09.)


[seongsu-git]: https://github.com/seongsulee-git