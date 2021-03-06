---  
title: "[Book Review] 아마존 웹 서비스 AWS Discovery Book"  
categories: Review  
tag:
  - aws
  - 아마존
  - 클라우드
  - 백엔드
  - Amazon Web Service
date: 2021-05-14
---  

클라우드 서비스 개념을 이해하고 직접 구성해보기

---

## Book Info

[![책](/assets/images/review/aws-discovery-book.jpg)](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788956748238&orderClick=LEa&Kc=)

- 제목: 아마존 웹 서비스 AWS Discovery Book
- 저자: 권영환
- 출판사: 정보문화사
- 출간: 2019-02-10

## 이 책을 읽게 된 이유

백엔드 개발자가 되기 위해서는 클라우드 환경에서의 경험이 필요합니다. 특히 AWS는 대부분의 스타트업에서 쓰이고 있으며, 백엔드 개발자 채용 공고만 봐도 클라우드 경험 또는 AWS 사용 경험이 있는 사람을 더욱 선호합니다. 저도 백엔드 개발자를 목표로 하고 있기에 AWS를 경험해봐야겠다는 생각에 읽게 됐습니다.

`'AWS 공식 문서가 너무 잘 되어 있는데 굳이 책을 봐야 할까?'` 라는 생각도 했지만 AWS 공부를 깊게 하기에는 너무 시간이 부족하다고 판단이 되어 핵심만 빠르게 실습할 수 있는 책을 보고 싶었습니다. [따라하며 배우는 AWS 네트워크 입문](http://pod.kyobobook.co.kr/podBook/podBookDetailView.ink?barcode=1400000392652&ejkGb=KOR), [서비스 운영이 쉬워지는 AWS 인프라 구축 가이드](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791158391317&orderClick=LEa&Kc=) 등의 책들도 고려했었습니다만, 결국은 이 책이 전자도서관에 있길래 빌려 읽었습니다. [따라하며 배우는 AWS 네트워크 입문](http://pod.kyobobook.co.kr/podBook/podBookDetailView.ink?barcode=1400000392652&ejkGb=KOR) 책은 2020년 후반에 나온 책이라 더 고민됐었습니다. 나머지 책들은 나중에 기회가 된다면 더 깊게 공부하고 싶을 때 읽어볼 것 같습니다. 

## 책 리뷰

이 책은 AWS의 개념을 간단하게 익히기 좋은 입문 책이라고 생각합니다. 매우 깊게 알려주지는 않지만 핵심이라고 생각이 드는 주요 서비스들은 다 알려줍니다. 또한, 실습이 엄청 많습니다. 모두 이미지로 자세하게 설명되어 있으며, AWS 회원가입부터 EC2, S3, VPC 등 AWS를 처음 경험하는 초보자들도 실습을 따라할 수 있습니다. 물론 2019년에 나온 책이라 메뉴 또는 명칭이 조금 다르지만, 크게 다른 부분은 없었습니다.(뭐 모르는 부분은 구글링 하면 다 나오니까요.)

저는 `AWS는 유료 서비스인데 실습을 위해서 결제를 해야 하는가?`라는 생각을 했었습니다만, 이 책은 `AWS 프리 티어`를 활용하기에 그런 걱정은 할 필요가 없었습니다. 이 책의 실습만 잘 따라한다면 요금 결제가 될 일이 없습니다. 실습이 끝날 때마다 바로바로 사용한 서비스들을 종료하거나, 중지시킴으로써 과금이 될 일이 없는 거죠.

가끔 다음 장의 실습에서 이전 장의 실습을 이용한 경우들이 있긴 하지만, 이미 실습한 인스턴스들을 종료를 해서 이전 실습을 다시 했던 경우도 있었습니다. 이런 부분들은 복습하는 느낌으로 다시 실습했습니다. 중지라는 좋은 방법도 있지만, 중지를 했었을 때 요금이 부과되지 않는다는 보장이 없었기에 그냥 종료했습니다. 전 덕분에 이전 실습을 복습하는 것이 꽤 좋았네요. 중지와 종료의 차이를 알기 원하시는 분들은 공식 문서 [인스턴스 수명 주기](https://docs.aws.amazon.com/ko_kr/AWSEC2/latest/UserGuide/ec2-instance-lifecycle.html#lifecycle-differences)를 참고하시면 될 것 같습니다. 

한 장에 개념->개념에 맞는 AWS 서비스->실습->에필로그 순서로 구성되어 있습니다. 한 장이 끝날 때마다 에필로그에는 도움이 되는 내용 또는 역사 등이 나와서 저에게는 꽤 재밌는 부분이었습니다. 특히 8장에서 Auto Scaling을 공부할 때는 `auto scaling 기능이 실제로 사용할 수 있을까?, 과연 사용하는 사람이 있을까?`라는 의문이 있었는데 바로 에필로그에 데브시스터즈에서 쿠키런 서비스를 운영할 때 사용했다는 사례가 있길래 꽤 괜찮은 서비스라고 생각했습니다.

마지막 12장, 13장에는 AWS certification을 어떻게 준비하고 어떻게 공부해야 하는 지에 관해 설명하고 있습니다. 이 부분에도 시험 응시나 어떤 사이트에서 공부를 해야 하는지에 대해 이미지로 잘 설명이 되어 있습니다. 2년이 지난 지금도 유효한 방법인지는 잘 모르겠으나 AWS 자격증에 관심이 있으시거나 필요하신 분들은 참고하시면 좋을 것 같습니다.

## 대상 독자

이 책의 대상 독자는 아무래도 AWS 경험을 간단하게 해보고 싶은 입문자입니다. 혼자 하면 어려울 수 있었던 실습들을 시행착오 없이 도와줍니다. 이미지로 설명이 잘 되어 있어서 많은 도움이 됐습니다. 

이 책이 입문서이긴 하지만, 기본적인 CS(Computer Science) 지식은 필요하다고 생각합니다. 이 책에서도 CS 개념들을 설명해주기는 하지만, 아주 간략하게만 설명해주고 자세하게는 기술되어 있지 않습니다. 저도 읽으면서 궁금한 부분, 어려운 부분들이 있어서 구글링을 했었고요. 더 열심히 공부 해야겠다는 생각을 하게 만드는 책이었습니다.

## 요약

`이 책을 읽기전 기본적인 CS 개념들을 알고 있으면 더욱 읽기 쉬우며 AWS를 입문하기에는 좋은 책입니다.`