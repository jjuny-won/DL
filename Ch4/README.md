# Summary

- 기계학습에서 사용하는 데이터셋은 훈련 데이터와 시험 데이터로 나눠서 사용한다.
- 훈련 데이터로 학습한 모델의 범용 능력을 시험 데이터로 평가한다.
- 신경망 학습은 손실 함수를 지표로, 손실 함수의 값이 작아지는 방향으로 가중치 매개 변수를 갱신한다.
- 가중치 매개변수를 갱신할 떄는 가중치 매개변수의 기울기를 이용하고, 기울어진 방향으로 갖ㅇ치의 값을 갱신하는 작업을 반복한다.
- 아주 작은 값을 주었을 떄의 차분으로 미분하는 것을 수치 미분이라고 한다.
- 수치 미분을 통해 갖ㅇ치 매개 변수의 기울기를 구현할 수 있다.
- 수치 미분을 이용한 계산은 시간이 많이 걸리지만, 구현은 간단하다.