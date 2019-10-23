---
layout: inner
title: About
permalink: /about/books

---

## Book List

Personal archive with favorite quotes

2018

- 알고리즘, 인생을 계산하다 [Algorithms to live by: The computer science of Human decisions] by Brian Christian, Tom Griffiths
  - "어쩌면 우리는 그런 계산 결과를 갖고 살아갈 수 있을 것이다. 매번 장애물과 마주칠 때마다 완벽함을 추구하느라 하염없이 세월을 보낼 생각이 아니라면, 어려운 문제는 계속 붙들고 씨름하기 보다 더 쉬운 형태를 상상하여 그것을 먼저 공략하자. 제대로 적용될 때, 이것은 단지 희망 섞인 생각이나 환상이나 게으른 공상이 아니다. 발전을 이루는 최선의 방법 중 하나다." P336-337
- 모두의 딥러닝 by 조태호
  - [Practice code](https://github.com/joyce04/data_science/tree/master/deep_learning)
- 케라스로 구현하는 딥러닝과 강화학습 [Deep Learning with Keras] by Antonio Gulli, Sujit Pal <br> 번역본은 2018년에 나왔지만, 케라스는 1.0버전 코드라서 2.0버전 업그레이드에 대한 고려가 되어있지 않음…. 기대가 커서 그런지 실망도 큼....
  - [Practice code](https://github.com/joyce04/data_science/tree/master/deep_learning_with_keras)

<br/>

2019

- Settles, Burr. Active learning literature survey. University of Wisconsin-Madison Department of Computer Sciences, 2009.<br>
- 엔지니어를 위한 데이터 시각화 : D3.js로 배우는 데이터 시각화 이론과 12가지 사례 by 모리후지 다이치, 안티베이지안 (한빛미디어)<br>
  **올바른 의문에 근사적인 해를 가지는 것이 잘못된 의문에 대한 정확한 해를 가진 것보다 훨씬 낫다. - J.W. Tukey**<br>

  일반적으로 시각화는 데이터에서 몇 가지 변수를 추출해서 인식해야 할 데이터 변수를 픽업한다. 또한 다른 데이터와 대응시키거나 중첩해서 정리하는 대수적 처리와 집계, 통계적인 처리를 해서 다른 데이터로 변환한다.
  통계 분석의 금언 중에서 GIGO라는 것이 있다. GIGO란 garbage in garbage out의 약자로 직역하면 쓰레기를 넣으면 쓰레기가 나온다는 말이지만 **통계 분석에서는 데이터가 쓰레기면 쓰레기 같은 결과밖에 나오지 않는다는 것을 의미한다.** 이 말은 시각화에서도 똑같이 적용할 수 있으며 목적에 맞지 않는 부적절한 데이터는 시각화해도 아무것도 얻을 수 없다는 것을 말하고 있다. <br>

  데이터 세트를 시각화 할때의 세 단계 <br>specification : 데이터 중 어느 변수를 시각화할 대상으로 삼을지, 어떤 표현으로 시각화 할지 결정한다.
  Assembly : 축, 라벨, 범례를 종합하여 시각화 표현을 어떻게 조립할지 결정한다.
  Display : 종이와 프로젝트, 동영상 등 어떤 장치, 어떤 미디어로 보여줄지 결정한다.<br>

  데이터 종류- 시간과 대상을 다루는 방식에 따라 다음 같이 나뉜다.
  Cross section data: 시점을 고정해서 다양한 대상으로부터 획득한 데이터를 가리킨다. 어떤 날짜의 서비스별 매출 데이터 등
  Time series data: 시간의 흐름에 따라 수집된 데이터
  Panel data: cross section + time series <br>

  시각화 할 때는 최소한 다음 정보들을 확인해야한다.<br>
  1. 데이터 크기
  2. 데이터 취득 기간
  3. 데이터 취득 방법 : 어떻게 취득했는지에 따라 바이어스는 달라진다.
  4. 데이터의 정의 : 데이터의 정의가 모호하면 해석할 수 없는 사례가 많다.
  5. 비교 가능한 상태로 되어 있는가?

  상태 전이도 : 어떤 상태로부터 어떤 상태로 전이하는 경로와 확률을 함께 적은 그림이다. 목적은 어떤 노드에서 어느 노드로 전이하는지 파악할 수 있게 한다.<br>
