---
title: CP (심화 내용)
description: CP와 W'에 대한 심화 내용
published: true
date: 2024-12-16T04:29:59.198Z
tags: power, cycling, cp, advanced
editor: markdown
dateCreated: 2024-12-11T09:00:13.610Z
---

# CP (심화내용)
## CP

CP는 특정 운동 지속 시간 이상에서 지속 가능한 최대 유산소 강도를 나타냅니다.
이 강도의 [파워](/ko/aerobic/cycling/term/power)는 이론적으로 무기한 지속 가능하다고 간주되지만, 실제로는 피로 축적과 외부 요인으로 제한됩니다.

FTP와 유사한 점이 있고 많이 혼동되지만, CP는 더 수학적으로 정의됩니다. CP는 **파워-지속 시간 관계(Power-Duration Relationship)** 를 기반으로 계산됩니다.


## W' (W prime)
CP를 초과하는 강도로 운동할때 사용되는 무산소 에너지의 저장량입니다.
CP를 초과하는 강도로 운동을 지속하게 되면 결국에는 라이더의 W' 이 고갈되어 어느순간 운동을 더 이상 지속할 수 없게 됩니다.

## 상세

우리가 유지가능한 파워와 시간에 대한 [그래프](/ko/RiduckService/PowerProfile)를 그리게 되면 

![]()
이런식으로 로그 함수와 유사한 그래프가 그려지게 됩니다.

이때 가로 선과 평행하게 수렴하게 되는 지점의 파워를 CP라 정의하며 그 이상 유지 할 수 있는 일의 양을 W' 이라고 부르게 됩니다.


또 운동시간(Time)과 운동량(Joule, Watt * Time)의 그래프를 그리게 되었을때

![운동 시간 당 운동량의 변화 그래프](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e7bd00b6-c027-4e32-8b19-3eda31c815c3/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2023-05-22_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_1.53.53.png)

위와 같은 그래프가 그려지게 됩니다.

또 이 그래프는 다음과 같은 식을 따르게 됩니다.

$$
운동량(Joule, W * t) = CP * t + W'
$$

이를 말로 풀어 쓰면 다음과 같이 쓸 수 있습니다.
수행한 총 운동량(Joule)은 무한정 수행가능한 유산소 파워(CP)와 시간의 곱(t) 그리고 사용할 수 있는 무산소 운동량(W') 과 같다.

$$
P = CP + \frac{W'}{t}
$$


## Reference


