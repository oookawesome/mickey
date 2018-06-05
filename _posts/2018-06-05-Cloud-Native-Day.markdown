---
layout: post
title: Pivotal Cloud Native Day in Seoul 참석 내용
date: 2018-06-05 17:30:00 +0300
description: Pivotal Cloud Native Day in Seoul 참석 내용
image :
    feature: pivotal.jpg
    topPosition: -50px
categories: Pivotal, Cloud Native
tags: [Pivotal, Cloud Native]
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---
#### Pivotal Cloud Native Day in Seoul
6월 5일 피보탈에서 진행하는 Cloud Native Day 컨퍼런스에 참여했다. 피보탈에서 일하는 방법과 Cloud Native Application으로 product을 개발하는 방법에 대한 내용이었다. (이를 위한 Pivotal Cloud Foundry라는 자사 솔루션 홍보도 많았다.) 사실 Cloud Native가 뭔지도 잘 몰라서 찾아보기도 했다..

> CNCF(Cloud Native Computing Foundation)에서 정의한 Cloud Native System의 특징은  
a) 컨테이너 단위로 관리  
b) Auto Scale  
c) Microservice 중심 관리

![pivotal](../assets/images/posts/pivotal.jpg){: width="100%" height="100%"}

#### 넷플릭스 MSA
여러 세션이 있었으나 가장 주의깊게 들었던 넷플릭스 케이스에 대한 내용을 정리했다.
- 마이크로 서비스 잘 나누는 것 보다도 테스트, 운영, 개발이 제대로 되도록 환경을 갖추는 것이 중요
- 넷플릭스에서는 개발자가 코드 작성하고, 돌리고, 운영한다. (Full Cycle Developer)
이걸 다 하게 하려면 어떻게 했을까? 각 기술별(빌드, 운영...)로 특수한 스페셜리스트들이 나눠지게 됬고, 이게 각 클라우드 플랫폼 팀이 됬다. 이들이 각 기술을 쉽게 활용할 수 있도록 Tool을 만들어 개발자들에게 제공했다.
- 넷플릭스가 앞선 방식에 익숙해지는 데 오랜시간이 걸렸다.
- 이러한 Tool들이 Zuul, Eureka, Hystrix 이런 것들이었고 얘네들은 모두 오픈소스에 올렸다.
