# Machine Learning : 엔드게임, BigQuery의 진화

본 문서는 삼성동 구글 캠퍼스 서울에서 실시한 [구글 빅데이터 쇼케이스 시즌8 (Google Big data Showcase season 8)]((https://www.campus.co/seoul/ko/events/ag1zfmd3ZWItY2FtcHVzckgLEgpDYW1wdXNOYW1lIgRSb290DAsSCkNhbXB1c05hbWUiBXNlb3VsDAsSB0V2ZW50VjIiEmEyaDNhMDAwMDAwQTFCYkFBSww#events)) 발표에 시연한 Tutorial Jupyter Notebook에 대해서 서술되어 있습니다.

Google Cloud의 국내 최초 프리미어 파트너인 클라우드/오픈소스 전문 기업 락플레이스가 개최하는 'Google Big data Showcase' 시리즈는 Cloud 또는 Big data를 도입, 활용하려는 기업이나 스타트업을 대상으로 Big data 및 Machine Learning에 대한 주요 트렌드 및 이슈, 최신 기술 등을 소개하고 직접 시연하며 Google Cloud의 도입 및 활용을 위한 최적의 솔루션을 제시합니다.  

발표 시간 : 2019년 5월 23일 오후 1:30 ~ 6:00  

발표 장소: [구글 캠퍼스 서울](https://www.campus.co/seoul/ko/)

발표자: [김하제](haje@g.skku.edu) (Solutions Architect)



### 튜토리얼 설명

- **[튜토리얼 01](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-01.ipynb)** : Google Analytics 데이터를 활용하여 웹사이트 방문자 거래 예측하기
  - 모델 : Binary Logistic Regression 사용
- **[튜토리얼 02](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-02.ipynb)** : 농구 게임 스코어 예측하기
  - 모델 : Linear Regression 사용
- **[튜토리얼 03](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-03.ipynb)** : 출생 체중 예측하기
  - 모델 : Linear Regression 사용



## 사용 솔루션 및 준비 사항

- [Google BigQuery](https://cloud.google.com/bigquery/) : Google Cloud의 Data Warehouse and Anlysis tool
- [Jupyter Notebook](https://jupyter.org) : Python을 사용하는 Jupyter Notebook
- Machine Learning & Deep Learning 알고리즘에 대한 이해
- **착한 마음씨**
- 고등학교 이과 졸업 유리



## 사용 모델

- [선형 회귀 (Linear Regression)](https://developers.google.com/machine-learning/crash-course/descending-into-ml/linear-regression?hl=ko) : 종속 변수 y와 한 개 이상의 독립 변수 x와의 선형 상관 관계를 모델링하는 회귀 분석 기법 (출처: [위키피디아 선형 회귀]([https://ko.wikipedia.org/wiki/%EC%84%A0%ED%98%95_%ED%9A%8C%EA%B7%80](https://ko.wikipedia.org/wiki/선형_회귀)))
- [로지스틱 회귀(Logistic Regression)](https://developers.google.com/machine-learning/crash-course/logistic-regression/calculating-a-probability?hl=ko) : 분류 문제에서 선형 예측에 Sigmoid 함수를 적용하여 가능한 각 불연속 라벨값에 대한 확률을 생성하는 모델 (출처: [구글 머신러닝 용어집](https://developers.google.com/machine-learning/glossary/?hl=ko))



## 참고 문서
[Getting started with BigQuery ML using Cloud Datalab](https://cloud.google.com/bigquery-ml/docs/bigqueryml-notebook-start)  
[Using BigQuery ML to predict basketball outcomes](https://cloud.google.com/bigquery-ml/docs/bigqueryml-ncaa)

[Google BigQuery ML tutorials](https://cloud.google.com/bigquery-ml/docs/tutorials)

[BigQuery ML - Machine Learning using SQL in BigQuery](https://www.youtube.com/watch?v=BanOYQVl30I)

[How to Do Predictive Analytics in BigQuery (Cloud Next ’18)](https://www.youtube.com/watch?v=Ml2aCTn7kFY)

[What's New with BigQuery ML and Using it to Assess Data Quality (Cloud Next '19)](https://www.youtube.com/watch?v=DnlG4frLKmw)