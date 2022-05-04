# 사이버불링 예측 프로젝트

### 프로젝트 기획 배경
코로나 19로 인해 사이버폭력이 증가하고 이로 인해 극단적인 선택을 하는 경우도 발생하고 있다. 사이버불링 예측 서비스를 통해 피해를 사전에 방지하고자 기획하게 되었다.

### 모델링 과정
- baseline model 로 `logistic regression` 설정
- 연속적인 데이터를 처리하기 위해 RNN 모델 중 `LSTM` 사용해 기울기 소실 문제 사전에 방지
- loss가 지속적으로 하락하는 시그모이드 옵티마이저 설정
- acc : 0.849, f1 score : 0.852
---
### 사용 기술
#### 데이터분석 & 시각화
- pandas
- numpy
- seaborn
- matplotlib
- 
#### 모델링
- tensorflow
- sklearn
- afinn # 감정사전 라이브러리
- nltk
- collections

