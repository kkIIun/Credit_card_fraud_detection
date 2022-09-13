# Dacon Unsupervised Anomaly Detection

---

## 1. 데이터 전처리 방식

    dataFrame type을 torch.Tensor type으로 바꿨습니다.

## 2. model 설명

    model은 Autoencoder를 사용해서 30->90->150->90->30 으로 space를 늘렸다가 줄여 처음 입력과 출력의 값을 빼줘서 손실함수를 계산합니다.
