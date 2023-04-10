<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=2ndMiniProject&fontSize=90" />

### 2차 미니프로젝트

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white"/>
---

텐서플로를 활용한 자동차 분류 모델 제작

Fine tuning을 중점으로 진행하여 최적의 성능을 가진 모델 제작을 목적으로 함






+ 각 영화 사이트를 selenium을 통해서 크롤링하여 영화 목록을 가져오고,
  <br>
  사용자가 선택한 영화에 대한 리뷰를 dict에 저장하는 기능 구현


+ CGV, MEGA, LOTTE, DAUM이라는 클래스에 각 영화 사이트를 크롤링하고 리뷰를 분석하는 기능을 구현하였고,
  <br>
  이를 Movie라는 클래스에서 상속받아서 각 영화 사이트 클래스의 기능을 수행할 수 있게 하였다

+ 영화 사이트마다 리뷰 방식이 다르기 때문에 클래스로 구분하여 각 사이트에 맞추어 리뷰를 분석하였고,
  <br>
  메가박스의 경우 매력 포인트가 리뷰에 표시되어서 이를 카운트하여 매력 그래프를 그려주는 기능을 추가 구현

+ 또한 리뷰 내에 단어들을 통해 5가지 키워드에 대한 단어의 빈도 수를 카운트하여
  <br>
  해당 영화가 어떤 감정 포인트를 가지고 있는 영화인지에 대한 그래프를 그려주는 기능 구현
  <br>
  실제 영화 사이트 내에 감정 포인트를 그려주는 영화 사이트가 있는데 비교하였을 때 높은 유사도를 보임

+ 또한 Movie 클래스 내에서 선택하는 영화 사이트에 따라 보여지는 메뉴를 다르게 하였고,
  <br>
  카카오맵 api를 사용하여 현재 위치에서 해당 영화관의 위치까지의 경로를 표시하고,
  <br>
  걸리는 시간을 알려주게 하였다
