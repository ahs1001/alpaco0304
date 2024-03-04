# alpaco0304

# OOO 모델을 이용한 이상치 도출

* Github Url: https://github.com/shiny0510/FewShotGAN-Unet3D
* Requirement: pandas, numy, torch, seaborn, matplotlib, flask

1. **수행기관**: 알파코 딥러닝 부트캠프
2. **역할**: 웹, 딥러닝
3. **데이터**: MNIST train 6만장 test 3만장

![architecture](https://github.com/ahs1001/alpaco0304/assets/149747521/4bdc1160-4cef-4f53-918d-c5eca1f3efa6)

**Architecture**

<img src=https://github.com/ahs1001/alpaco0304/assets/149747521/515b60f1-28ea-4d2b-9a1e-d5f9db10c26c width=600 height=400>

**Output**

**느낀점**: CNN으로는 0~9 이미지의 학습 성능이 잘 나왔지만 transform을 어떻게 주냐에 따라서 성능을 감소시키는 기법들이 뭐인지 리포트하고 싶었다.

**참고문헌**: Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems 25 (2012)
