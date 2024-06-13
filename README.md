# 2024 Bank-PersonalData-Service

## 팀원
안윤성
이지영
임예은

## 개요
이 프로그램은 은행 계좌 관리 시스템입니다. 사용자는 다양한 계좌 정보를 입력하고, 이름, 계좌번호, 상품명 등을 기준으로 계좌를 검색할 수 있습니다. 또한 전체 계좌 목록을 출력할 수 있습니다.

## 기능
1. 계좌 정보 입력
2. 이름으로 계좌 검색
3. 계좌번호로 계좌 검색
4. 상품명으로 계좌 검색
5. 전체 계좌 정보 출력

## 사용 방법

### 1. 프로그램 실행
프로그램을 실행하면 먼저 계좌 정보를 입력할 수 있는 메뉴가 나타납니다. 예를 들어, 다음과 같은 정보를 입력합니다:
- 이름: 홍길동
- 계좌번호: 123456
- 계좌유형: 저축
- 상품명: 정기예금
- 잔액: 1000000
- 개설일자: 20210601
- 관리영업점: 대전지점
- 관리직원: 김철수

입력을 완료한 후 'end'를 입력하면 계좌 정보 입력이 종료됩니다.

### 2. 검색 메뉴
계좌 정보를 모두 입력한 후, 검색 메뉴가 나타납니다. 사용자는 다음과 같은 선택지를 선택할 수 있습니다:
1. 이름으로 검색: 이름을 입력하여 해당 이름으로 등록된 모든 계좌 정보를 검색합니다.
2. 계좌번호로 검색: 계좌번호를 입력하여 해당 계좌번호로 등록된 계좌 정보를 검색합니다.
3. 상품명으로 검색: 상품명을 입력하여 해당 상품명으로 등록된 모든 계좌 정보를 검색합니다. 또한 이용자 수를 출력합니다.
4. 전체 출력: 등록된 모든 계좌 정보를 출력합니다.
5. 종료: 프로그램을 종료합니다.

## 코드 구조
프로그램은 세 개의 주요 클래스로 구성됩니다: (------나중에 클래스 이름수정------)
1. **Account 클래스**: 계좌 정보를 저장하는 클래스입니다. 
2. **BankAccountManager 클래스**: 계좌 정보를 관리하고 검색하는 기능을 제공하는 클래스입니다.
3. **Main 클래스**: 프로그램의 메인 실행 클래스로, 사용자 입력을 받아 적절한 기능을 수행합니다.

## 예제 실행
프로그램을 실행하면 다음과 같은 흐름으로 진행됩니다:

1. 계좌 정보 입력
2. 검색 메뉴 선택 및 검색 수행
3. 결과 출력

```plaintext
계좌 정보를 입력하세요. 끝내려면 'end'를 입력하세요.
이름: 홍길동
계좌번호: 123456
계좌유형: 저축
상품명: 정기예금
잔액: 1000000
개설일자: 20210601
관리영업점: 대전지점
관리직원: 김철수
...

검색 메뉴: 1. 이름으로 검색 2. 계좌번호로 검색 3. 상품명으로 검색 4. 전체 출력 5. 종료
1
이름을 입력하세요: 홍길동
이름: 홍길동, 계좌번호: 123456, 계좌유형: 저축, 상품명: 정기예금, 잔액: 1000000, 개설일자: 20210601, 관리영업점: 대전지점, 관리직원: 김철수
...

검색 메뉴: 1. 이름으로 검색 2. 계좌번호로 검색 3. 상품명으로 검색 4. 전체 출력 5. 종료
5
