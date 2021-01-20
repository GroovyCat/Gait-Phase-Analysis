# Gait-Phase-Analysis
* LSTM 네트워크를 통한 보행 단계 예측 분석

## Introduction
* 하지 외골격 로봇은 하지 마비 환자의 재활 분야에 관심이 높아지고 있음.
* 착용자들이 운동 기능을 되찾을 수 있도록 지지 역할, 운동 보조, 신체의 추진력을 제공할 수 있음.
* 보행 패턴은 반복 동작 패턴을 생성하게 되는데 보조 외골격은 관절 주위에서 필요한 힘을 제공하여 미리 정의된 궤적으로 착용자의 움직임을 안내할 수 있음.
* 보행 단계를 분석하는 것은 하지 외골격 로봇을 제어해 환자의 재활을 도울 수 있도록 할 수 있음. 그래서 로봇을 착용하기 전 사용자들의 발 데이터를 통해 보행 단계 패턴을 분석하고자함.
* 보행 단계 예측은 미래 값의 시퀀스가 과거의 시퀀스를 기반으로 예측되는 Timeseries 예측임.
* 그 중에서도 LSTM은 시계열 데이터를 처리하는 가장 효과적인 모델 중 하나임.

## Materials and Methods
### Dataset 설명
* https://www.kaggle.com/dasmehdixtr/human-gait-phase-dataset
* kaggle에 오픈된 gait-phase-dataset을 사용해 보행 단계를 분석함.
* 데이터셋에 대한 자세한 설명은 위 링크를 통해 확인하기 바람.
* 해당 분석에서 쓰인 LSTM의 하이퍼 파라미터 소개
![lstm](https://user-images.githubusercontent.com/15725909/105153664-0ab1d200-5b4c-11eb-8706-986a0ea3bf22.png)

