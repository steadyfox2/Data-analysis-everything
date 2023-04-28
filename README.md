# Data-analysis-everything
데이터 분석가가 반드시 알아야할 모든 것 책 코드 리뷰

# 데이터 탐색과 시각화

<details><summary><h3>공분산과 상관 분석 실습</h3></summary>

- **`공분산과 상관 분석 실습`**
  - 
  <img src = "https://user-images.githubusercontent.com/114843451/232720824-0d5e1a8e-3f6c-43de-8a7b-64a4da213b8d.png" width="35%" height="30%">

몇 개의 산점도는 어느 정도의 상관성이 보이는 것을 확인할 수 있다.
종속변수라 할 수 있는 quality 변수는 자연수 형태로 3~9로만 이루어져 있기 때문에 다른 변수들과 줄무늬 형태의 산점도를 보인다.
동일한 변수는 일직선으로만 나오기 때문에 큰 의미가 없으므로 분포도로 변환하여 정보량을 늘리는 것이다.

df.cov()와 df.corr(method='pearson')를 활용해서 공분산과 피어슨 상관계수를 확인해주었다.

- **`히트맵`** 
  - 
  <img src = "https://user-images.githubusercontent.com/114843451/232721961-081d5cf3-3aee-4d54-9018-ccd4be07319b.png" width="35%" height="30%">

노란색에 가까울수록 양의 상관관계를 보이고 보라색에 가까울수록 음의 상관관계를 보인다. 

- **`clustermap 히트맵 시각화`** 

  <img src = "https://user-images.githubusercontent.com/114843451/232722307-272e4e56-884f-4b8f-be37-9d7c7875b4eb.png" width="35%" height="30%">

히트맵과 함께 상관계수도 확인할 수 있게 되었다.

- **`중복 제거 히트맵 시각화`** 

  <img src = "https://user-images.githubusercontent.com/114843451/232722615-fc637597-f242-4dcd-90f5-fc2607f96984.png" width="35%" height="30%">

이번 장을 통해서 공분산과 히트맵에 개념, 코드를 익힐 수 있었다.

개념 정리 

공분산: 두 변수의 관계를 나타내는 양

히트맵: 히트 맵(heat map)은 열을 뜻하는 히트(heat)와 지도를 뜻하는 맵(map)을 결합시킨 단어로, 색상으로 표현할 수 있는 다양한 정보를 일정한 이미지 위에 열분포 형태의 비주얼한 그래픽으로 출력하는 것
</details>
