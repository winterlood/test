# 1과목 - 소프트웨어 설계 Chapter 3. sw 아키텍쳐
## Section 27. 시스템 인터페이스 요구사항 구성
### 시스템 인터페이스 요구사항 구성

독립적으로 떨어져 있는 시스템들 끼리의 서로 연동하여 상호작요하기 위한 접속방법 또는 규칙을 의미함

- 개발을 목표하는시스템과 외부 시스템간의 인터페이스 요구사항 기술

- 이름, 연계대상, 범위 및 내용, 방식, 송신데이터, 주기, 기타가 존재한다

### 요구사항 분석

기능적, 비기능적으로 분류한다

조직화하여 요구사항 명세를 구체화하고 이를 이해관계자에게 전달한다.

- 요구사항명세란 시스템 인터페이스 요구사황과 관련된 자료를 이용하여 인터페이스 요구사항 명세서와 목록을 추가, 수정하는 작업을 의미한다

- 요구사항 분석은 기법이 있다

- 분해가 필요한 경우 분해한다

- 누락된것이나 제한조건을 추가한다

- 상대적 중요도를 평가 우선순위를 부여한다

### 요구사항 분석절차

1. 요구사항 목록에서 시스템 인터페이스와 관련된 요구사항만 뽑아서 목록을 만든다

2. 시스템 인터페이스와 관련된 요구사항 및 아키텍쳐 정의서 등등 자료를 준비한다

3. 명세서를 확인하여 기능적인것과 비기능적인것으로 분류한다

4. 요구사항 명세서와, 요구사항 목록 및 기타 관련자료를 비교하여 분석 및 내용추가 수정함

5. 공유한다

### 기출문제

1. 2
2. 3
3. 4
4. 1

## Section 28. 인터페이스 요구사항 검증
### 요구사항 검증

인터페이스 실제 구현 전에

사용자들의 요구사항이 명세서에 정확히 기술되었는지 검토, 개발범위의 기준인 **베이스라인**을 설계하는 것이다

- 오류가 나중에 발생하면 이것을 바로잡는데 비용이 많이들기 때문에 한다

- 검토계획수립 -> 검토 및 오류수정 -> 베이스라인 설정 

### 검토계획수립

1. 검토 기준 및 방법
2. 참여자
3. 체크리스트
4. 관련자료
5. 일정

위의 기준으로 검토계획을 수립한다

### 인터페이스 요구사항 검토 및 수정

항목에 따라 검토하여 수정한다

- 오류발생시 -> 오류수정을 위해 오류목록, 시정조치서를 작성

### 베이스라인 설정

- 프로젝트 관리자와 의사결정자가 공식적 승인을 한다
- 실제 구현을위하여 요구사항 명세서의 베이스라인을 설정한다

### 검증방법

- 요구사항 검토 : 오류확인, 표준준수, 결함 등등을 검토 
  - 동료검토 : 동료들에게 물어보기
  - 워크스루 : 검토회의전에 명세서를 미리 배포, 사전검토하고 짧은 검토회의를 통해 결함을 발견
  - 인스펙션 : 전문가 상담

- 프로토타이핑 : 요구사항을 정확히 식별하기위해 프로토타입을 만들어 최종결과물을 예측한다

- 테스트설계 : 요구사항을 테스트할 수 있도록 작성해야하며, 이를위해 Tc를 생성하여 이후 요구사항이 현실적으로 테스트 가능한지 검토

- CASE도구 활용 : 일관성 분석을통해 관리 한다

### 주요 검증 항목

- 완전성 : 모든 요구사항이 누락되지않고 완전하게 반영되었는지
  > 빼먹지 않았는가?

- 일관성 : 모순이나 충돌이 없는가

- 명확성 : 이해가능한가 ?

- 기능성 : 어떻게가 아닌 무엇을에 중점을 두었는가?

- 검증 가능성 : 사용자의 모든 요구를 만족, 개발된 소프트웨어가 요구내용과 일치한가

- 추적 가능성 : 추적가능?

- 변경용이성 : 변경하기 쉽도록 되었나?

### 기출문제

1. 3
2. 2
3. 1


## Section 29. 인터페이스 시스템 식별
### 개발 시스템 식별

인터페이스 관련 자료들을 기반으로 개발하고자하는 시스템의 상세 식별 정보를 정의하고 목록을 작성하는것이다.

### 내-외부 시스템 식별

개발할 시스템과 내부적 외부적으로 상호작용 할 시스템들의 상세식별정보를 정의, 목록을 작성하는것이다

### 내-외부 시스템 환경 및 관리주체 식별

연계 시스템에 접속에 필요한 IP 또는 URL 또는 PORT 정보 등 실제 운용환경을 의미한다

주체는 실제 하드웨어 관리 담당자이다

관련자료를 기반으로 확인한다

### 연결정보 식별

연결정보라는것은 시스템 로그인 및 DB정보를 의미한다

### 인터페이스 식별

개발할 시스템과 이와 연계할 내-외부 시스템간의 인터페이스를 식별하고 목록을 작성한다

### 인터페이스 시스템식별

인터페이스별로 인터페이스에 참여하는 시스템을 송신과 수신으로 구분하여 작성하는것이다

### 기출문제

1. 3
2. 2

## Section 33. 미들웨어 솔루션 명세
### 미들웨어란

운영체제, 응용프로그램 사이에서 OS가 지원하는 서비스 이외에 추가적인 서비스를 제공하는 SW이다.

- 표준화된 인터페이스를 제공한다
- 데이터 교환에 일관성을 보장한다
- 통신제공방법이나 기능에 따라 분류된다

### DB 
DB는 원격 DB와 연결하기 위한 미들웨어이다

- 이걸사용하면 2-Tier라고한다
- ODBC,GLue등이있다고 한다

### RPC 
Remote Procedure Call 원격 프로시저 호출
응용 프로그램의 프로시저를 이용하여, 원격 프로시저를 마치 로컬 프로시저처럼 쓰는것

### MOM
Message Oriented Middleware
메세지 지향 미들웨어, 메세지 기반의 비동기형 메시지를 전달한다

### TP-Monitor
트랜잭션을 모니터링한다
> 철도 예약및  항공기 티켓 발권? 등등...

빠른 응답을 요구한다

### ORB
Object Request Broker
...

### WAS
Web Application Server이다.
사용자의 요구에 따라 변화하는 동적 컨텐츠를 처리하기 위해 사용되는 미들웨어

### 미들웨어 솔루션 식별


## 문제은행

1. 2
2. 3
3. 2
4. 1
5. 4
6. 3
7. 1
8. 2
9. 4 
 10. 4 /
 11. 4 /
12. 3
13. 3
14. 1
15. 4
16. 4