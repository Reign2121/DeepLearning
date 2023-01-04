# Perceptron # seoultech

Perceptron

매개변수

eta : float

  - 학습률 ( .0~1.0 사이의 실수값 )

n_iter : int

  - 훈련 데이터셋 반복 횟수

random_state : int

  - 가중치 무작위 초기화를 위한 난수 생성기 시드 <랜덤으로 뿌린다.> 아니면 오래걸림 w_ : 1d-array

  - 가중치 (w, b 모두 가중치다)

errors_ : list

  - 에포크마다 초기화를 위한 난수 생성기 시드

X : {array-like}, shape = [n_sample, n_feature]

  - n_sample 개의 샘플과 n_features 개의 특성으로 이루어진 훈련 데이터

y : array-like(유사배열), shape = [n_sample]

  - target 값
