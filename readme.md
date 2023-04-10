<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=2ndMiniProject&fontSize=90" />

### 2차 미니프로젝트

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white"/> <img src="https://img.shields.io/badge/Kakao-FFCD00?style=flat&logo=Kakao&logoColor=white"/>
---

1. 이미지 데이터 전처리(Image Data Preprocessing)
 
 + 이미지 수집 과정에서 numpy 형식으로 저장.
 
 + 딕셔너리 안에 데이터 저장.
 
 + 차량 내부, 외부 분류 by YOLOV3
 
 + 이미지 데이터 증강 by Image Data Generator

<br>

2. 데이터셋 수정

 + 학습을 위한 차량 이미지 데이터가 깔끔하고 명확하지 않아서 데이터셋을 수정하기로 결정.

 + 추가로 각 차량 모델의 홈페이지에서 데이터를 확보.

 + 한 차량 모델에 대해 모델링 된 차량 이미지 120장, 크롤링을 통한 차량 이미지 180장으로 총 300장으로 재구성.

<br>

3. 모델 선정

 + 하이퍼 파라미터 설정: Epochs, Batch size, Learning rate 설정.

 + 전이학습 : 사전학습 된 MobileNet, DenseNet, ResNet 모델에 추가로 layer 구성 한 뒤 같이 학습.

 + 평가 및 시각화 : 각 모델들을 학습 후 평가 및 시각화.

 + 하이퍼 파라미터 튜닝 : 하이퍼 파라미터 튜닝 후 모델 학습 및 평가.

 + 최종결론 : MobileNet, DenseNet 두 모델에 대해 Finetuning 진행하기로 결정.
