# Machine Learning : 엔드게임, BigQuery의 진화

본 문서는 삼성동 구글 캠퍼스 서울에서 실시한 [구글 빅데이터 쇼케이스 시즌8 (Google Big data Showcase season 8)]((https://www.campus.co/seoul/ko/events/ag1zfmd3ZWItY2FtcHVzckgLEgpDYW1wdXNOYW1lIgRSb290DAsSCkNhbXB1c05hbWUiBXNlb3VsDAsSB0V2ZW50VjIiEmEyaDNhMDAwMDAwQTFCYkFBSww#events)) 발표에 시연한 Tutorial Jupyter Notebook에 대해서 서술되어 있습니다.

발표 시간 : 2019년 5월 23일 오후 1:30 ~ 6:00  

발표 장소: [구글 캠퍼스 서울](https://www.campus.co/seoul/ko/)



## 사용 솔루션

- [Google BigQuery](https://cloud.google.com/bigquery/) : Google Cloud의 Data Warehouse and Anlysis tool
- [Jupyter Notebook](https://jupyter.org) : Python을 사용하는 Jupyter Notebook



## 준비 사항

- Machine Learning & Deep Learning 관련 지식
- 고등학교 이과 졸업 유리
  - 문송하게도 저는 문과입니다…
- **착한 마음씨**



## 사용 모델

- [선형 회귀 (Linear Regression)](https://developers.google.com/machine-learning/crash-course/descending-into-ml/linear-regression?hl=ko) : 종속 변수 y와 한 개 이상의 독립 변수 x와의 선형 상관 관계를 모델링하는 회귀 분석 기법 (출처: [위키피디아 선형 회귀](https://ko.wikipedia.org/wiki/%EC%84%A0%ED%98%95_%ED%9A%8C%EA%B7%80) )
- [로지스틱 회귀(Logistic Regression)](https://developers.google.com/machine-learning/crash-course/logistic-regression/calculating-a-probability?hl=ko) : 분류 문제에서 선형 예측에 Sigmoid 함수를 적용하여 가능한 각 불연속 라벨값에 대한 확률을 생성하는 모델 (출처: [구글 머신러닝 용어집](https://developers.google.com/machine-learning/glossary/?hl=ko))



## 튜토리얼 설명

- **[튜토리얼 01](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-01.ipynb)** : Google Analytics 데이터를 활용하여 웹사이트 방문자 거래 예측하기
  - 모델 : Binary Logistic Regression 사용
  - [데이터 과학자용 BigQuery ML 시작하기](https://cloud.google.com/bigquery/docs/bigqueryml-scientist-start?hl=ko)
- **[튜토리얼 02](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-02.ipynb)** : 농구 게임 스코어 예측하기
  - 모델 : Linear Regression 사용
  - [BigQuery ML을 사용하여 농구 결과 예측](https://cloud.google.com/bigquery/docs/bigqueryml-ncaa?hl=ko)
- **[튜토리얼 03](https://github.com/hajekim/endgame/blob/master/bqml-tutorial-03.ipynb)** : 출생 체중 예측하기
  - 모델 : Linear Regression 사용
  - [BigQuery ML을 사용하여 출생 시 체중 예측](https://cloud.google.com/bigquery/docs/bigqueryml-natality?hl=ko)



## 참고 문서 및 영상
- [Getting started with BigQuery ML using Cloud Datalab](https://cloud.google.com/bigquery-ml/docs/bigqueryml-notebook-start)
- [Using BigQuery ML to predict basketball outcomes](https://cloud.google.com/bigquery-ml/docs/bigqueryml-ncaa)
- [Google BigQuery ML tutorials](https://cloud.google.com/bigquery-ml/docs/tutorials)
- [BigQuery ML - Machine Learning using SQL in BigQuery](https://www.youtube.com/watch?v=BanOYQVl30I)
- [How to Do Predictive Analytics in BigQuery (Cloud Next ’18)](https://www.youtube.com/watch?v=Ml2aCTn7kFY)
- [What's New with BigQuery ML and Using it to Assess Data Quality (Cloud Next '19)](https://www.youtube.com/watch?v=DnlG4frLKmw)



### 제 소개

##### [김하제](http://www.linkedin.com/in/hajekim)

- **2017 - Present | Solutions Architect | 락플레이스**

  - [Google Cloud Platform](https://cloud.google.com/), [Amazon Web Services](https://aws.amazon.com/ko/) 아키텍쳐 및 구축
  - DevOps, CI/CD, Open Source 엔지니어링
  - ETL & Data Warehousing 엔지니어링

- **2013 - 2017 | Software Engineer | 유클릭**

  - Oracle Middleware 구축 및 기술 지원

    - [Oracle WebLogic Server](https://www.oracle.com/kr/middleware/weblogic/)
    - [Oracle iPlanet WebServer (SunOne WebServer)](https://en.wikipedia.org/wiki/Oracle_iPlanet_Web_Server)
    - [Oracle HTTP Server](https://www.oracle.com/technetwork/articles/index-091236.html)
    - [Oracle Coherence](https://www.oracle.com/kr/middleware/coherence/)
    - [Oracle Application Server](https://en.wikipedia.org/wiki/Oracle_Application_Server)

  - APM(Application performance Management) 구축 및 기술 지원

    - [다봄소프트 EnPharos Java]([http://www.dabomsoft.com/wordpress/enpharos-java/](http://www.dabomsoft.com/wordpress/enpharos-java/))

    