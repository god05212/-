# Hotel Reservations
## 고객이 호텔예약을 취소할지 예측하기
프로젝트 기간: 2021/06/29(화) ~ 2021/07/02(금)  
온라인 호텔 예약 채널은 예약 가능성과 고객의 행동을 극적으로 변화시켰습니다. 취소나 노쇼로 상당수 호텔 예약이 취소되고 있는데 대표적인 취소 사유로는 계획 변경, 일정 충돌 등이 있습니다. 이는 종종 호텔이 처리해야 할 수익 감소 요인이 될 수 있습니다.  
데이터는 36275개의 값과 19개의 열을 가지고 있는데 여기서 우리는 "Hotel Reservation.csv" 데이터베이스를 사용할 것이며, 우리의 목표를 달성하기 위한 데이터 분석, 그 데이터의 처리 및 기계 학습 분류 모델의 사용을 볼 것입니다.
## 개요
고객이 호텔예약을 취소할지 예측하는 모델을 만드는 프로젝트입니다. 온라인 호텔 예약 채널은 예약 가능성과 고객의 행동을 극적으로 변화시켰습니다. 그러나 취소나 노쇼로 상당수 호텔 예약이 취소되고 있는데 대표적인 취소 사유로는 계획 변경, 일정 충돌 등이 있습니다. 이는 종종 호텔이 처리해야 할 수익 감소 요인이 될 수 있습니다. 따라서, 취소나 노쇼로 상당수 호텔 예약이 취소될 가능성을 미리 파악함으로써 수익 감소 요인을 줄일 수 있는 모델을 만들고자 하였습니다.
## 사용한 데이터셋
Hotel Reservations Dataset:Can you predict if customer is going to cancel the reservation?  
위 데이터셋은 예약일과 도착일 사이의 일수, 예약 당일 평균 가격, 고객이 요청한 총 특별 요청 수, 도착한 달 등 호텔에 예약했던 고객에 대한 데이터를 가지고 있습니다.
## 프로젝트 수행 과정
1. Importing Dataset
2. Data Analysis  
categorical Variables  
continous Variables  
Analysis  
3. Model Building  
- Label Encoder  
- Balancing Classes  
- StandardScaler  
Naive Bayes - Gaussian Model  
Decision Tree  
Random Forest  
Extra Trees  
K Means  
K Neighbors  
Logistic Regression  
AdaBoost  
Gradient Boosting  
Neural Network  
- 주요 변수 확인
- 결과 확인
4. Conclusion
## 모델의 dataset에 대한 f1 score (소숫점 다섯 째 자리에서 반올림)
| Model | accuracy |
|:----------------------------------------|:---------|
| Gaussian Model                          | 0.5663 |
| Decision Tree                           | 0.8665 |
| Random Forest                           | 0.8714 |
| Extra Trees                             | 0.9341 |
| K Means                                 | 0.6756 |
| K Neighbors                             | 0.8734 |
| Logistic Regression                     | 0.7795 |
| AdaBoost                                | 0.8207 |
| Gradient Boosting                       | 0.8838 |
| Neural Network                          | 0.8719 |
## 최종 모델
dataset에 대한 결과(Extra Trees)
- accuracy: 약 0.9341
## 배운 점
"주어진 상황에서 선택할 수 있는 최선의 방법을 찾아야 한다."  
프로젝트 기간이 일주일로 매우 짧았습니다. 따라서, 최신 기술만을 고집하기보다는 해결해야 할 문제를 분석하고 그에 맞는 방법을 찾고자 노력하였고, 그 덕분에 기간 내에 결과물을 도출할 수 있었습니다. 이를 통해서 최신 기술이 항상 최선의 방법인 것은 아니라는 것, 그리고 주어진 상황을 빠르게 파악하고 그에 맞는 방법을 찾는 게 중요하다는 것을 배울 수 있었습니다.
