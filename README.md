# 시간에 따른 유동인구 예측 모델

서울 지역의 시간대별 인구 수 데이터를 이용하여 시간에 따른 인구를 예측하는 모델을 만들어보자

## 데이터분석
![image](https://github.com/user-attachments/assets/5ad51cf4-9874-4d6b-9431-ac526c423223)<br>
데이터의 종류는 여자와 남자의 시간대별 데이터로이름으로 데이터를 분석해봤을 때<br>
"날짜_성별_?_?_?_시간.csv"로 보인다.

또한 파일은 내용은<br>
![image](https://github.com/user-attachments/assets/101dba14-465e-4e12-8094-5dba161313a5)<br>
여러 수들로 빼곡히 채워져있는 것을 확인할 수 있었다.

이를 파이썬을 이용해 여러 파일 중 하나를 시각화해본 결과<br>
![image](https://github.com/user-attachments/assets/c672d5eb-05ef-4ffc-9a58-be40910a590a)
해당 사진처럼 이 데이터가 해당 시간대에 있는 유동인구 수를 나타내고 있다는 것을 확인할 수 있었다.

## 모델 생성을 위한 train, test 데이터 생성


