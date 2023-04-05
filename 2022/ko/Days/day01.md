---
title: '#90DaysOfDevOps - Introduction - Day 1'
published: true
description: 90DaysOfDevOps - Introduction
tags: 'devops, 90daysofdevops, learning'
cover_image: null
canonical_url: null
id: 1048731
date: '2022-04-17T10:12:40Z'
---

## 개요 - Day 1

90일 중 1일차에는 데브옵스에 대한 기본적인 이해와 데브옵스적 사고방식을 돕는 도구에 대해서 학습합니다.

저는 몇 년 전부터 이 학습 여정을 시작했었습니다. 그 당시 가상화 플랫폼과 클라우드-기반 기술에 중점을 두어 학습하였고, 주로 코드형 인프라 (Infrastructure as Code)와 앱 구성관리를 테라폼과 셰프로 알아보고 있었습니다.

2021년 3월, Veeam의 Kasten사에서 클라우드 네이티브 전략에 대해 저의 노력을 쏟을 좋은 기회가 주어졌었습니다. 그것은 쿠버네티스와 데브옵스 그리고 관련 기술을 둘러싼 커뮤니티에 엄청난 관심을 끌게 될만한 것이었습니다. 저는 학습 여정을 시작하면서 쿠버네티스와 컨테이너화의 기초를 학습하는 것 외에도 아주 넓은 세계가 있다는 것을 알아차렸습니다. 그 시기는 제가 커뮤니티에서 발표하고, 데브옵스 문화, 툴 그리고 프로세스에 대해 학습해 나가기 시작할 때였습니다. 그래서 저는 학습하고 싶은 분야 중 일부 영역을 공개적으로 기록하기 시작했습니다.

[So you want to learn DevOps?](https://blog.kasten.io/devops-learning-curve)

## 여정을 시작하면서

위의 블로그를 읽고 저의 학습 여정의 수준이 매우 높을 것이라고 짐작하시는 분들을 위해 말씀드리면, 저는 그 분야들에 대해 전문가는 아닙니다만 유료이건 무료이건 어떤 형태로든 자료를 공유하고 싶었습니다. 우리는 모두 서로 다른 환경에 있을 것이니 각자에게 맞는 선택을 하시길 바랍니다.

앞으로 90일간 저는 기본적인 영역들에 대해 다루고 자료들을 문서화하려고 합니다. 커뮤니티의 적극적인 참여도 바라고 있습니다. 많은 분의 학습 여정과 자료의 공유를 통해 공개적으로 함께 도와가며 서로 배우길 바랍니다.

프로젝트 리포지토리의 readme에 12주에 6일을 더한 분량의 섹션 별로 분할을 해두었습니다. 첫 6일간은 특정 영역에 뛰어들기 전에 데브옵스에 대한 전반적인 기본 지식들에 대해 학습할 것입니다. 반복해서 말씀드리면 저의 자료가 완벽하지 않습니다. 따라서 이 자료들이 유용하게 활용될 수 있도록 커뮤니티의 도움을 바랍니다.

지금 이 순간에 공유하고 싶은 자료가 하나 더 있습니다. 모두가 꼼꼼히 살펴야 하고, 스스로에 대한, 자신의 관심과 현재 위치를 마인드맵으로 그려야 할, 그것은

[DevOps Roadmap](https://roadmap.sh/devops)

이 주제에 대한 블로그 포스트, 초기 목록을 작성하는데 데브옵스 로드맵이 아주 유용하게 사용되었습니다. 본 리포지토리의 12가지 주제 이외에도 다른 영역에 대한 더 많은 정보를 얻을 수 있을 것입니다.

## 첫 단계 - 데브옵스란?

소개드리고 싶은 유튜브 비디오나 블로그 글이 너무 많습니다. 하지만 우리는 90일의 도전을 시작했고 매일 한 시간씩 새로운 것을 배우거나 데브옵스에 관해 배우기로 했으므로, "DevOps란 무엇인가"라는 높은 수준의 정보를 먼저 얻는 것이 좋다고 생각합니다.

우선, 데브옵스는 도구가 아닙니다. 살 수 있는 것도 아니고, software SKU나 깃허브 레포지토리에서 다운로드 받을 수 있는 오픈 소스도 아닙니다. 또한 프로그래밍 언어도 아니고, 괴상한 흑마술도 아닙니다.

데브옵스란 소프트웨어 개발에서 좀 더 현명하게 일하는 방법을 말합니다. - 잠깐... 혹시 소프트웨어 개발자가 아니라면 이 학습 과정을 중단해야 할까요??? 아닙니다.. 데브옵스란 소프트웨어 개발과 운영의 통합을 의미하기 때문입니다. 위에서 언급했듯이 저는 일반적으로 운영에 속하는 VM(가상머신)과 관련된 쪽에 있었지만, 커뮤니티에는 다양한 배경을 가진 사람들이 있습니다. 그리고 개인, 개발자, 운영자 그리고 QA 엔지니어 모두는 DevOps를 더 잘 이해함으로써 모범사례에 관해 동등하게 배울 수 있습니다.

데브옵스는 이 목표를 달성하기 위한 일련의 관행입니다: 제품이 초기 아이디어 단계부터 최종 사용자, 내부 팀 또는 고객 등 모든 사용자에게 실제 운영 서비스로 전달되기까지의 시간을 단축하는 것.

첫 주에 다룰 또 다른 분야는 **애자일 방법론** 에 관한 것입니다. 애플리케이션을 지속적으로 전달(Continuous Delivery)하기 위해 데브옵스와 애자일은 주로 함께 다루어집니다.

개략적으로 말해 데브옵스적 사고방식이나 문화는 길고 몇 년이 걸릴 수 있는 소프트웨어 배포 프로세스를 더 작고, 자주 배포하는 방식으로 시간을 단축시키는 것입니다. 추가로 이해해야 할 또 다른 핵심 포인트는 위에 언급한 개발, 운영, QA 팀 간의 사일로를 무너트리는 것은 데브옵스 엔지니어의 책임입니다.

데브옵스의 관점에서 보면 **개발, 테스트, 배포**는 모두 데브옵스 팀과 함께해야 하기 때문입니다.

최종적으로 이런 것을 효과적이고 효율적으로 하기 위해서는 **자동화**를 최대한 활용해야 합니다.

## 자료

이곳을 학습 도구로 활용하기 위해 이 readme 파일에 추가적으로 자료를 덧붙이는 것에 대해 항상 열려있습니다.

그리고 아래 동영상들을 꼭 보시기 바랍니다. 또한 위에 설명드린 내용에서 많은 인사이트를 얻었으면 합니다.

- [DevOps in 5 Minutes](https://www.youtube.com/watch?v=Xrgk023l4lI)
- [What is DevOps? Easy Way](https://www.youtube.com/watch?v=_Gpe1Zn-1fE&t=43s)
- [DevOps roadmap 2022 | Success Roadmap 2022](https://www.youtube.com/watch?v=7l_n97Mt0ko)
- [From Zero to DevOps Engineer - DevOps Roadmap for YOUR specific background](https://www.youtube.com/watch?v=G_nVMUtaqCk)

여기까지 읽었다면 나에게 필요한 내용인지 아닌지 알 수 있을 것입니다. [Day 2](day02.md)