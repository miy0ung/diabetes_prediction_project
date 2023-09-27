# Diabetes_Prediction_Project
- Member: 김미영, 이주은, 조강국, 하수연

![image](https://github.com/miy0ung/diabetes_prediction_project/assets/101385210/d8455940-853c-4917-9a6b-c82eda3cd735)

### <요약>
본 프로젝트에서는 당뇨병 예측 데이터를 활용하여 다양한 전처리 기법을 적용한 뒤 그 차이를 비교해 보았다. 이후 Logistic Regression, Random Forest, SVM 모델의 예측 성능을 비교해 보았는데, 그 결과 Random Forest 모델이 가장 우수하였다. 모델을 비교하는 지표로는 AUC를 이용하였다. 또한, 가장 성능이 높은Random Forest 모델을 통해 추정해 본 결과, 당뇨병에 영향을 미치는 위험요인들의 중요도 순위는 당화혈
색소(HbA1c_level), 혈당 수치(blood_glucose_level), 나이(age)순이었다.


### <서론>
최근 비만, 부종, 인구 고령화 등의 요인으로 인해 당뇨병 유병률이 세계적으로 급증하고 있다. 당뇨병은 만성적 질환이기에 관리하지 않을 경우 중증의 합병증을 유발할 수 있다는 점에서 사회적으로 주목을 받고 있기도 하다. 대한당뇨병학회의 당뇨병 팩트 시트 논문(Diabetes Fact Sheet in Korea 2021)에 따르면, 2020년의 당뇨병 환자 수는 600만 명으로, 2010년에 비해 2배 증가한 바 있다. 이에 반해 당뇨병의 발생을 감하기 위해서는 당뇨병에 영향을 미치는 위험 요인을 파악하고, 사전에 예방할 필요가 있다.

머신러닝(machine learning)이란 인공지능의 한 분야로, 최근 데이터의 중요성이 증대되며 그 양과 질이 개선됨에 따라 크게 주목받고 있다. 의학 분야에서도 이미지 인식, 질병의 발병 예측 등으로 적극 활용되고 있다(조상아 외, 2021). 본 연구에서는 당뇨병에 영향을 미치는 요인을 알아보기 위하여 Random Forest를 활용한다. Random Forest의 경우, 타 모델과의 비교를 통해 해당 모델의 선정 이유를 서술한다.

### <모델>
- Logistic Regression
- Random Forest
- SVM


### <제언>
본 연구는 의료 데이터를 적극적으로 이용하여 질병의 예방과 치료에 큰 도움을 줄 수 있음을 보여준다. 머신러닝을 활용하여 각종 질병에 영향을 미치는 주요 요인을 식별함으로써, 환자와 의료진은 질병을 예방할 수 있게 된다. 이는 더 나아가 보건 정책 수립에도 활용될 수 있으며, 전세계 국민의 건강 유지에 크게 기여할 것으로 전망된다. 이렇듯 의료 데이터의 종합적인 분석과 머신러닝의 적용은 당뇨병을 비롯한 다양한 질병의 관리에 대한 새로운 가능성을 보여준다.

## Dataset
- Kaggle: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

## 참고 논문
- https://file.notion.so/f/s/9e110b63-c761-4dde-a978-79d6954f525b/KBB_SCHOLAR_kyobo_10532344.pdf?id=a53a41d8-b2ce-4888-8872-84e04409a0f6&table=block&spaceId=ac90e89d-d931-47d8-87d8-f44362b72eeb&expirationTimestamp=1685368764824&signature=9KudeTZbDjfA-f87varYE9F1pio5muSrprfe5ZBdteA&downloadName=KBB_SCHOLAR_kyobo_10532344.pdf
