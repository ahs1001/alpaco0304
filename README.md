# alpaco0304

# 000 모델을 이용한 이상치 도출

* Github Url: https://github.com/shiny0510/FewShotGAN-Unet3D
* Requirement: pandas, numy, torch, seaborn, matplotlib

1. **수행기관**: 알파코, 빅데이터기반 딥러닝 부트캠프
2. **역할**: Method튜닝, 전처리, 팀장, 트러블 슈팅
3. **데이터**: 환자 데이터 10000개, 정상인 데이터 20만개
4. **Method**: 전처리: 이미지 Normalize + MixUp(Augmentation) + Denosing
5. **모델**: F-AnoGAN (Medical Image ANalysis, 2019.05) optimizer: Adam loss: L1 loss

![architecture](https://github.com/ahs1001/alpaco0304/assets/149747521/4bdc1160-4cef-4f53-918d-c5eca1f3efa6)

**Architecture**

<img src=https://github.com/ahs1001/alpaco0304/assets/149747521/515b60f1-28ea-4d2b-9a1e-d5f9db10c26c width=600 height=400>

**Output**
