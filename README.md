# **통계분석실습 프로젝트 ** <br/>
## 1. 개요
- 프로젝트 소개 및 목표
  - 목표 : 은행에서 예금을 수신하기 위한 데이터 기반 상품홍보 전략수집
  - bank_customer.ipynb
  
## 2. 데이터
  - data_test.csv : test data set
  - data_test.csv : test data set

## 3. 프로젝트 설명
- 설명변수
  - 고객관련정보(Age, Job, Marital, Education, Default, Housing, Loan)
  - 현재 진행하고 있는 telemarketing 정보(Contact, Month, Day_of_week)
  - 기타 정보들(Campaign, Pdays, Previous, Poutcome)
  - 사회 경제적 변수들(emp var rate, cons.price.idx, cons.conf.idx)
- 반응변수
  - 고객이 광고홍보를 통해 은행에 예금을 예치했는지 여부(yes/no)

- 모델링
  - Logistic Regression
  - Random Forest
  - XGBoost
  
 - Custom Scroing 함수를 생성하여 평가지표로 활용

## 4. 결론
- 성능이 가장 높게 나온 튜닝한 Random Forest 모델 선택

## 5. 개발 환경
- Python
