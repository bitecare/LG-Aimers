### Team 치킨마요 덮밥 Solution 요약


```python
├── DAT
│     ├── train  
│     ├── sales
│     ├── day_info
│     ├── melt_data60
│     ├── chrate
│     ├── chrate_base
├── OUT
├── WEI
│     ├── LSTM_weights.pth
├── PSC
│     ├── make_day_info.ipynb  
│     ├── make_meltdata.ipynb
│     ├── make_chrate.ipynb
│     ├── RF.ipynb
│     ├── XGB.ipynb
│     ├── Extra.ipynb
│     ├── LSTM.ipynb
│     ├── Ensemblef.ipynb
└── Readme.md
```

- DAT : 분석에 필요한 데이터셋이 있는 폴더입니다.
 - train, sales, sample_submission : 데이콘으로부터 제공받은 데이터입니다.
 - day_info : 일자별 월, 일, 요일, 주말, 공휴일, 휴일 여부를 일자별로 생성한 데이터셋입니다.
 - melt_data60 : 머신러닝 코드에 맞추어 ID별, 날짜별 정보로 전환한 데이터셋입니다.
 - chrate : 판매 변동량의 역수를 train 데이터셋 형태에 맞게 생성한 데이터셋입니다.
 - chrate_base : 판매 변동량/판매량 합 변수를 train 데이터셋 형태에 맞게 생성한 데이터셋입니다.
- OUT : 코드 실행 결과로부터 산출된 결과물이 들어 있는 폴더입니다. 
- WEI : LSTM 모델링의 결과로 산출된 모델의 가중치가 저장된 폴더입니다.
 - LSTM_weights : LSTM 모델링의 결과로 산출된 모델의 가중치가 저장된 파일입니다.
- PSC : 실행 코드들이 담긴 폴더입니다.
 - make_day_info.ipynb : day_info 데이터셋을 만드는 코드입니다.
 - make_meltdata.ipynb : melt_data60 데이터셋을 만드는 코드입니다.
 - make_chrate.ipynb : chrate, chrate_base 데이터셋을 만드는 코드입니다.
 - RF, XGB, Extra, LSTM : 각 모델들에 대해 학습과 예측을 수행하는 코드입니다.
 - Ensemblef.ipynb : 모델 예측 수행의 결과를 앙상블하는 코드입니다.


### 실행 순서
- 처음 제공받은 데이터만 존재하는 상태에서 실행하는 경우
 - 1. make_day_info을 실행합니다.
 - 2. make_meltdata, make_chrate을 실행합니다.
 - 3. RF, XGB, Extra, LSTM을 실행합니다. 
 - 4. Ensemblef을 실행합니다.
 - 5. 최종 제출물 Please를 얻을 수 있습니다.
- 새로운 데이터셋(day_info, melt_data60, chrate, chrate_base)이 있다고 가정하고 실행하는 경우
 - 1. RF, XGB, Extra, LSTM을 실행합니다.
 - 2. Ensemblef을 실행합니다.
 - 3. 최종 제출물 Please을 얻을 수 있습니다.
  


```python

```


```python

```
