# 비트코인 그래프 예측


### 개발 환경 : Jupiter notebook, tensor flow, pandas, matplotlib


### 목표 : 과거의 5분 단위 데이터를 비교해와서 학습 후 미래의 그래프 예측



### epoch의 수에 따른 로스 함수 그래프

<img width="312" alt="image" src="https://user-images.githubusercontent.com/79649052/159150050-af42e56a-80f0-43b5-92f6-912146b2cedb.png">



### 실제 값과 예측된 그래프 비교


<img width="312" alt="image" src="https://user-images.githubusercontent.com/79649052/159150057-dc1769d5-39c8-476e-b595-9a18e768900a.png">



### 현재 마지막 불러온 데이터까지의 예측만 가능하고, 후에 더 보완해 슬라이딩 윈도우 기술을 통하여 미래의 30분 동안의 그래프를 예측할 예정



