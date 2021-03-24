공공 데이터 활용 온도 추정 AI 경진대회
=======================================

안전한 원자력발전을 위해 한국수력원자력에서 제공한 모의 운전 및 실제 데이터를 기반으로 하는 AI 알고리즘 개발 대회
대회 링크:
https://www.dacon.io/competitions/official/235551/overview/description/

Dataset
==================
이 저장소에 데이터셋은 제외되어 있습니다.  
데이터셋 출처: 
https://www.dacon.io/competitions/official/235551/data/

Structure
==================
```setup
.
└── main.py
└── load_dataset.py
└── data_loader.py
```
* main.py: feature extraction부터 modeling까지의 main문
* load_dataset.py: 데이터셋 크기를 줄이기 위한 처리 파일
* data_loader.py: load_dataset.py에 필요한 함수가 들어있는 파일

Results
==================
* 평가지표: Log Loss
* Log Loss 결과: 0.63
* private rank: 12/188