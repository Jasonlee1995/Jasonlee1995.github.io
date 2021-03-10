---
layout: post
title: 간단 논문 리뷰 - ImageNet Classification with Deep Convolutional Neural Networks
excerpt: "2012 NIPS Spotlight, Classification"
categories: [2012 NIPS, Spotlight, Classification, 간단 논문 리뷰]
comments: true
---


# 1. 논문 리뷰에 앞서...

위 논문 리뷰는 개인적으로 논문을 읽고 정리한 글이기에, 논문에 대한 모든 내용을 담고 있지 않습니다.

위 글에서 다루지 않은 부분들은 논문 혹은 [`github`](https://github.com/Jasonlee1995/AI_Papers/issues/1)을 참고하시기 바랍니다.

그 외에 잘못된 내용, 오타, 기타 문의 및 제안 사항들은 [`github`](https://github.com/Jasonlee1995/AI_Papers/issues/1)에 comment를 남겨주시면 됩니다.


# 2. About Paper

AlexNet은 ImageNet과 같은 large dataset과 더불어, GPU의 발전으로 탄생할 수 있었습니다.

Conv, pool, fc layer을 조합하 그 당시의 best performance를 낼 수 있었으며, architecture는 다음과 같습니다.

![AlexNet Architecture](../../../../img/210310_AlexNet/Figure_1.png)

논문을 읽으면서 개념적으로 어려웠던 부분 3가지를 짚자면 다음과 같습니다.

1. LRN
2. PCA를 이용한 data augmentation
3. Upper-bound of CNN and fully-connected network

이에 대하여 저는 다음과 같이 이해했습니다.

1. LRN == brightness normalization
2. PCA data augmentation == heuristic한 방법이 아닌 체계적인 RGB intensity augmentation
3. Upper-bound of CNN and fully-connected network : 아무리 찾아봐도 잘 안나오는데, VC-dimension을 통해 대략적인 upper bound 측정


# 3. Reference
- ImageNet Classification with Deep Convolutional Neural Networks [[paper]](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
