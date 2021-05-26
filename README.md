# XAI 정리

## Model-Agnostic Methods
1) [Graphic: PDP, ICE, ALE](https://github.com/yooonjiwon/XAI/blob/main/3%EC%A3%BC%EC%B0%A8_PDP_ICE_ALE_%EC%9C%A4%EC%A7%80%EC%9B%90.pdf)
Summary: 그래프를 이용해서 직관적인 설명을 돕는 방법들로, 어떤 모델을 선택하더라도 그래프로 표현 가능.
하지만 표현하고 싶은 feature들에 따라 PDP+ICE를 사용할지 ALE로 표현을 할지 달라짐.
표현하고 싶은 feature 사이에 correlation이 의심된다면 ALE 사용, 그렇지 않다면 PDP+ICE.
