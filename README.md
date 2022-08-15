# 2020빅콘테스트 - 데이터분석분야(퓨처스리그)
#### KBO 정규시즌 팀별 승률, 타율 및 방어율(평균자책점) 예측  
<img src="https://user-images.githubusercontent.com/109687076/184568698-13e28f4e-6d42-4b62-b616-83b0b1766879.jpg" width="70%">


## 1. Duration
- 2020.07 - 2020.12
- Team project (5 members)


## 2. Skills
- Python, ML(LSTM)
- Jupyter notebook, tensorflow
- Data analysis, Data preprocessing, Visualization


## 3. Contents
- 2016~2020 KBO 데이터를 이용해 2020년 팀별 승률, 타율, 방어율 예측 모델 개발
- 제공 데이터: 각 팀별 세부 경기 정보 및 선수 정보
- 데이터 전처리 및 시각화를 통해 예측변수와 유의미한 변수 선별 및 세이버 매트릭스 지표 활용
- 최종 모델: XGBoost/Random Forest Ensemble

#### 1) EDA & Data Visualization

<img src="https://user-images.githubusercontent.com/109687076/184569660-4a1fda6c-3354-4ab6-8e83-e85e36f6cb3b.JPG" width = "50%"><img src ="https://user-images.githubusercontent.com/109687076/184569662-9b911301-bc73-4dc5-a306-2f2454248677.JPG" width="50%">
<img src ="https://user-images.githubusercontent.com/109687076/184569665-67d6c814-1cdc-4638-beab-e620d473146e.JPG"  width="50%"><img src="https://user-images.githubusercontent.com/109687076/184569668-feb5ec14-76e8-4ac8-8833-68f953fdab5b.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184569669-25e41f25-81fd-4838-8e74-204a3af092c6.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184569671-bf076888-612f-4667-99c9-5f62a8d858ec.JPG" width="50%">

#### 2) Data Preprocessing for Modeling

<img src="https://user-images.githubusercontent.com/109687076/184569949-6a7398c0-41e4-4fa5-8363-c0cc257e7432.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184569952-d850f7be-c654-4548-b15b-f7e0da055948.JPG" width="50%">
<img src="https://user-images.githubusercontent.com/109687076/184569941-95a8117c-b848-4575-992a-6a0087f87e60.JPG" width="50%"><img src="https://user-images.githubusercontent.com/109687076/184569947-f08ab6ab-e4a6-4bbe-be14-023057c2ab3c.JPG" width="50%">

#### 3) Modeling  
<img src="https://user-images.githubusercontent.com/109687076/184570198-4349e138-9748-4227-8cc8-0c2dee82fc70.JPG">

## 4. Results
- 2020 빅콘테스트 최우수상(스포츠투아이상) 수상


## 5. Git
#### 1) Data
- 최종 모델 학습 및 테스트에 사용된 데이터
#### 2) Data_Crawling
- 대회에서 제공되지 않은 2020 후반부 데이터를 수집하기 위한 데이터 크롤링 진행
#### 3) Data_Preprocessing
- LSTM모델 기준 학습을 위한 전처리 코드
#### 4) Model
- LSTM을 적용한 예측 모델 개발
