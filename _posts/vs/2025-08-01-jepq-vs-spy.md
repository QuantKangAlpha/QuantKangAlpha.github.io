---
layout: single
title: JEPQ vs SPY
excerpt: JEPQ의 최근 3년 2개월 CAGR은 13.4%로 SPY의 13.7%와 비슷했습니다.
header:
  overlay_color: "#333"
  show_overlay_excerpt: false
toc: true
categories:
- vs
keywords: SPY, JEPQ, JEPQ SPY 비교
---

## 비교 상품 소개


JEPQ 상품과 SPY 상품의 성과를 수익률과 위험도로 비교합니다.





{% include commons/vs-notice.md %}

## 지난 성과

두 상품의 성과를 비교할 수 있는 가장 긴 기간은 최근 3년 2개월입니다. 아래는 이 기간의 성과[^fn_vs_perf]를 그래프와 표로 나타낸 것입니다.
그래프 범례에서 괄호안의 퍼센트 수치는 CAGR[^fn_vs_cagr_metric]입니다.
하단의 보조 그래프는 SPY 대비 JEPQ의 비를 나타냅니다.
JEPQ의 수익률이 SPY보다 지속적으로 우세하면 상승하고, 반대의 경우에는 하락합니다.

![JEPQ](/vs/images/jepq-vs-spy_dual.png){: .align-center}

| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| JEPQ | <span style="color: tomato">13.4<small>%</small></span> | 17.5<small>%</small> | 0.76 | -20.1<small>%</small> | -4.0<small>%</small> |
| SPY | <span style="color: tomato">13.7<small>%</small></span> | 18.1<small>%</small> | 0.76 | -18.8<small>%</small> | -3.9<small>%</small> |

<!-- more -->


성과를 분석하는 전통적인 방법인 수익률과 위험도[^fn_vs_risk]를 살펴봅니다.

**수익률 지표 (CAGR):** JEPQ의 CAGR은 13.4%로 SPY의 13.7%와 비슷했습니다. (비슷한 수익률)[^fn_vs_comp]

**위험도 지표 (표준편차):** JEPQ의 표준편차는 17.5%로 SPY의 18.1%와 비슷했습니다. (비슷한 위험도)

**위험도 지표 (MDD):** JEPQ의 20.1%의 MDD는 SPY의 18.8%보다 1.3% 높았습니다. (높은 위험도)



## 동일 수준 위험 노출을 위한 비중 조절

수익률과 위험도가 다른 상품을 비교하는 방법의 하나는, 둘 중 하나를 동일하게 설정하고, 나머지 하나를 비교하는 것입니다.
여기서는 SPY의 투자 비중[^fn_vs_weight]을 조절하여 JEPQ의 위험도와 유사하게 맞추어 수익률를 비교합니다.

**위험도 지표 (표준편차):** 표준편차를 동일한 값으로 맞추기 위해서는 18.1% / 17.5% = 97% 비중으로 투자하면 됩니다.[^fn_vs_sharpe]

**위험도 지표 (MDD):** MDD를 동일한 값으로 맞추기 위해서는 18.8% / 20.1% = 107% 비중으로 투자하면 됩니다.


{% include /commons/ads/adsense.html %}



## 동일 수준 위험하에서의 추정 성과

아래는 비중을 조절한 경우를 추가하여, 그래프와 표에 성과를 기록한 것입니다.
SPY<sub>STD</sub>는 표준편차를 맞춘[^fn_vs_weighting] 경우이고, SPY<sub>MDD</sub>는 MDD를 맞춘 경우입니다.
앞에서와 같이 그래프 범례에서 괄호안의 퍼센트 수치는 CAGR입니다.


![JEPQ](/vs/images/jepq-vs-spy.png){: .align-center}



| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| JEPQ | <span style="color: tomato">13.4<small>%</small></span> | 17.5<small>%</small> | 0.76 | -20.1<small>%</small> | -4.0<small>%</small> |
| SPY | <span style="color: tomato">13.7<small>%</small></span> | 18.1<small>%</small> | 0.76 | -18.8<small>%</small> | -3.9<small>%</small> |
| SPY<sub>STD</sub> <small>(97%)</small> | <span style="color: tomato">13.3<small>%</small></span> | 17.5<small>%</small> | 0.76 | -18.2<small>%</small> | -3.8<small>%</small> |
| SPY<sub>MDD</sub> <small>(107%)</small> | <span style="color: tomato">14.6<small>%</small></span> | 19.4<small>%</small> | 0.76 | -20.0<small>%</small> | -4.2<small>%</small> |



각각의 경우를 JEPQ의 성과와 비교해 봅니다.

**위험도 지표 (표준편차):** 97% 투자 비중으로 표준편차를 비슷한 수준으로 맞추면, CAGR은 13.3%로 JEPQ의 13.4%와 비슷했습니다. (비슷한 수익률)

**위험도 지표 (MDD):** 107% 투자 비중으로 하여 MDD를 비슷한 수준으로 맞추면, CAGR은 14.6%로 JEPQ의 13.4%보다 1.3% 높았습니다. (높은 수익률)




## 최종 비교

**주의** 투자 시점과 기간, 그리고 전략에 따라 다른 결과가 나올 수 있습니다. 백테스트 기간이 짧은 경우 통계적 신뢰성이 떨어질 수 있습니다. 미래에도 동일한 경향이 지속된다고 보장할 수 없습니다.
{: .notice--warning}

지난 3년 2개월간 거치식으로 투자했다고 가정합니다.

SPY의 투자 비중을 조절하여 표준편차나 MDD를 동일하게 맞추면, CAGR이 평균 14.0%인 포트폴리오를 만들 수 있습니다.
이 포트폴리오는 JEPQ의 13.4%와 비슷했습니다.

### JEPQ ≒ SPY
{: .text-center}
**참고** 위험 대비 수익률이 비슷한 경우라면, 적은 비중으로 동일한 투자 효과를 낼 수 있는 상품을 선택하는 것이, 투자 전략 유연성 측면에서는 보다 유리할 수 있습니다.
{: .notice--info}


## 관련 정보

- [JEPQ (나스닥 100 기반 액티브 커버드콜) + QQQ + 환율 + 예금 분산 투자 (평균-분산 그래프 분석) [자산 배분 시즌 2]](https://m.blog.naver.com/onuri2005/223933176683)
- [JEPI - CALL = ? (JEPI/JEPQ의 내부는 어떤 액티브 ETF일까?)](https://kongdori.tistory.com/256)
- [커버드콜 ETF는 왜 장기 투자에 적합하지 않은가? (효율적 투자선과 50% 오렌지 주스)](https://kongdori.tistory.com/244)
- [JEPI/JEPQ에 장기 배당 재투자하는 것은 좋은 방법일까? (장기투자와 세금)](https://kongdori.tistory.com/216)
- [당신이 JEPI/JEPQ를 사면 안되는 이유 (해외 상장 인컴 ETF의 배당소득세와 양도소득세)](https://kongdori.tistory.com/213)
- [JEPI/JEPQ는 특별한가? (SCHD/QQQ + 현금과의 비교)](https://kongdori.tistory.com/211)
- [커버드 콜 전략은 유용한가? (커버드 콜 전략을 쓰는 주요 ETF의 지금까지 수익률과 분석)](https://kongdori.tistory.com/155)
- [JEPQ는 기대하는 수준의 성과를 보였나? (QQQ 대비)](https://kongdori.tistory.com/150)
- [유사 종목 성과 비교 목록](/vs/){: .btn .btn--info}


## 참고 도서 [오렌지사과의 출간 책 소개와 샘플북 목록](https://kongdori.tistory.com/691)

- [왜 위험한 주식에 투자하라는 걸까? - 장기 투자와 분산 투자에 대한 통계학적 시각](https://kongdori.tistory.com/421)
- [파이썬으로 그려보는 투자 포트폴리오 분석  - 정량적 투자 분석을 위한 입문서](https://kongdori.tistory.com/643)
- [구글 시트로 시작하는 투자 포트폴리오 분석 - 오렌지사과의 불친절한 워크북](https://kongdori.tistory.com/449)

{% include commons/footnotes.md %}