# DataAnalysys-2022WC
2022년도 지능형 프로그래밍 기말과제 (2022 월드컵 결과 예측하기)


## Data Preparation

1. 데이터 수집
   
    데이터 세트는 1872년부터 2022년까지의 44,341 경기의 국제 축구 결과와 1992년부터 2022년도 까지의 FIFA 세계 랭킹 두 가지 데이터 세트를 사용하였음.

2. 데이터 전처리
   
    결측치를 처리하였음.
   
## Features Engineering

![image](https://github.com/yoohwanihn/DataAnalysis-2022WC/assets/73772238/7bfb34c1-d66f-486f-85c9-451af7a94ed8)


1. 기대효과
   
   차원 감소, 특징 선택, 특징 추출 가능

2. 다층 신경망

   ![image](https://github.com/yoohwanihn/DataAnalysis-2022WC/assets/73772238/a3410acc-666e-460d-aa27-731ab8378ede)

   사이킷런 활용, 은닉층 3개
   
   
3. 모델 훈련
   
   로지스틱 회귀, MLP Classifier, Lgb, 랜덤 포레스 4가지 모델을 카파 계수, Roc Curve를 통해 비교하였고 로지스틱 회귀 모델이 정확도가 높았고 Running Time 성능이 가장 뛰어나 채택하였음.

   
## Data Analysis

![image](https://github.com/yoohwanihn/DataAnalysis-2022WC/assets/73772238/d7c4b11f-b311-4cb2-9e23-8870551c82ac)


기계학습을 토대로 하였을때 벨기에가 우승국으로 나왔음.

## 결론 

![image](https://github.com/yoohwanihn/DataAnalysis-2022WC/assets/73772238/ebb9d46d-7d3d-4679-a1b0-b9262584adaa)

기계학습으로 월드컵을 예측하기엔
축구 성적과 관련한 20여 개 남짓한 데이터로는 설명할 수 없는 복잡한 요인들과 돌발상황들이 존재한다.

경기 당일의 날씨나 응원 현황, 심판관련 정보, 출전국의 정치적 상황, 선수 개인의 정보 등 경기의 성패와 간접적으로 관련된 더 많은 데이터가 사용되었다면 더 정확한 예측을 할 수 있었을 지도 모릅니다.
축구는 22명의 선수가 90분간 그라운드에서 볼을 가지고 하는 스포츠입니다. 사람과 사람의 상호작용에 의한 경기이기 때문에 선수 개인의 심리적 상태는 물론 한 팀 선수들 간의 교감, 상대 팀 선수와의 사회적, 상황적 관계가 고려되야 합니다. 축구 성적과 관련한 20여 개 남짓한 데이터로서는 설명할 수 없는 복잡한 요인들과 돌발상황들이 존재하고 있습니다.

## 활용 가능한 분야

1. 선수 부상 예측
2. 스포츠 토토
3. AI 코칭
