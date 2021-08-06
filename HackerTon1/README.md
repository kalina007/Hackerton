# Hackerton 1 레스토랑 방문자 수 예측하기

[팀원]
- [송찬용](https://github.com/thdcksdyd98)
- [김현지](https://github.com/aacara)
- [김우렬](https://github.com/wooryeol)
- 이유정

[jupyter notebook 목차]
- EDA
  - 날짜별 방문자 수 확인
  - 요일별 방문자 수 확인
- Feature Engineering & preprocessing¶
  - F1) 날짜별 공휴일
  - F2) 같은 지역별 store 갯수
  - F3) 남은 예약방문 일수와 시간
  - F4) 날짜별 요일 공휴일. 해당 날짜 방문자수 통계
  - F5) 머신러닝 학습을 위한 인코딩
- model 학습과 예측
  - xgboost를 이용하여 학습 후 예측
- xgboost tunning
  - 성능 개선을 위한 xgboost 튜닝

[회고]   
아... 상금이 너무 탐이 났으나, 혼자 힘으로 역부족인 것을 느꼈으며....    
여태까지 공부한 내용을 겉핡기식으로 배우면서 세세한 코드를 작성하지 못하는 나 자신을 보면서 반성했다....   
상금이 너무 탐난다....상금..... 약 $25,000 =========== 한화로 28,582,000

### 링크
[Kaggle](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting)   
[데이터 소스](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting/data)   
[참고한 자료](https://github.com/ligz08/Kaggle-Recruit-Restaurant-Visitor-Forecasting)

[jupyter notebook](https://github.com/kalina007/Hackerton/blob/main/HackerTon1/hackerton_1-version1.ipynb)
