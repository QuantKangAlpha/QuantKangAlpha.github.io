---
layout: single
title: SPY vs IDVO
excerpt: SPY의 최근 2년 10개월 CAGR은 18.7%로 IDVO의 17.9%와 비슷했습니다.
header:
  overlay_color: "#333"
  show_overlay_excerpt: false
toc: true
categories:
- vs
keywords: IDVO, SPY, SPY IDVO 비교
---

## 비교 상품 소개


SPY 상품과 IDVO 상품의 성과를 수익률과 위험도로 비교합니다.





{% include commons/vs-notice.md %}

## 지난 성과

두 상품의 성과를 비교할 수 있는 가장 긴 기간은 최근 2년 10개월입니다. 아래는 이 기간의 성과[^fn_vs_perf]를 그래프와 표로 나타낸 것입니다.
그래프 범례에서 괄호안의 퍼센트 수치는 CAGR[^fn_vs_cagr_metric]입니다.
하단의 보조 그래프는 IDVO 대비 SPY의 비를 나타냅니다.
SPY의 수익률이 IDVO보다 지속적으로 우세하면 상승하고, 반대의 경우에는 하락합니다.

![SPY](/vs/images/spy-vs-idvo_dual.png){: .align-center}

| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| SPY | <span style="color: tomato">18.7<small>%</small></span> | 17.1<small>%</small> | 1.09 | -18.8<small>%</small> | -2.8<small>%</small> |
| IDVO | <span style="color: tomato">17.9<small>%</small></span> | 16.3<small>%</small> | 1.10 | -15.5<small>%</small> | -2.5<small>%</small> |

<!-- more -->


성과를 분석하는 전통적인 방법인 수익률과 위험도[^fn_vs_risk]를 살펴봅니다.

**수익률 지표 (CAGR):** SPY의 CAGR은 18.7%로 IDVO의 17.9%와 비슷했습니다. (비슷한 수익률)[^fn_vs_comp]

**위험도 지표 (표준편차):** SPY의 표준편차는 17.1%로 IDVO의 16.3%와 비슷했습니다. (비슷한 위험도)

**위험도 지표 (MDD):** SPY의 18.8%의 MDD는 IDVO의 15.5%보다 3.3% 높았습니다. (높은 위험도)



## 동일 수준 위험 노출을 위한 비중 조절

수익률과 위험도가 다른 상품을 비교하는 방법의 하나는, 둘 중 하나를 동일하게 설정하고, 나머지 하나를 비교하는 것입니다.
여기서는 IDVO의 투자 비중[^fn_vs_weight]을 조절하여 SPY의 위험도와 유사하게 맞추어 수익률를 비교합니다.

**위험도 지표 (표준편차):** 표준편차를 동일한 값으로 맞추기 위해서는 16.3% / 17.1% = 105% 비중으로 투자하면 됩니다.[^fn_vs_sharpe]

**위험도 지표 (MDD):** MDD를 동일한 값으로 맞추기 위해서는 15.5% / 18.8% = 121% 비중으로 투자하면 됩니다.


{% include /commons/ads/adsense.html %}



## 동일 수준 위험하에서의 추정 성과

아래는 비중을 조절한 경우를 추가하여, 그래프와 표에 성과를 기록한 것입니다.
IDVO<sub>STD</sub>는 표준편차를 맞춘[^fn_vs_weighting] 경우이고, IDVO<sub>MDD</sub>는 MDD를 맞춘 경우입니다.
앞에서와 같이 그래프 범례에서 괄호안의 퍼센트 수치는 CAGR입니다.


![SPY](/vs/images/spy-vs-idvo.png){: .align-center}



| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| SPY | <span style="color: tomato">18.7<small>%</small></span> | 17.1<small>%</small> | 1.09 | -18.8<small>%</small> | -2.8<small>%</small> |
| IDVO | <span style="color: tomato">17.9<small>%</small></span> | 16.3<small>%</small> | 1.10 | -15.5<small>%</small> | -2.5<small>%</small> |
| IDVO<sub>STD</sub> <small>(105%)</small> | <span style="color: tomato">18.8<small>%</small></span> | 17.1<small>%</small> | 1.10 | -16.2<small>%</small> | -2.6<small>%</small> |
| IDVO<sub>MDD</sub> <small>(121%)</small> | <span style="color: tomato">21.6<small>%</small></span> | 19.8<small>%</small> | 1.09 | -18.5<small>%</small> | -3.0<small>%</small> |



각각의 경우를 SPY의 성과와 비교해 봅니다.

**위험도 지표 (표준편차):** 105% 투자 비중으로 표준편차를 비슷한 수준으로 맞추면, CAGR은 18.8%로 SPY의 18.7%와 비슷했습니다. (비슷한 수익률)

**위험도 지표 (MDD):** 121% 투자 비중으로 하여 MDD를 비슷한 수준으로 맞추면, CAGR은 21.6%로 SPY의 18.7%보다 3.0% 높았습니다. (높은 수익률)




## 최종 비교

**주의** 투자 시점과 기간, 그리고 전략에 따라 다른 결과가 나올 수 있습니다. 백테스트 기간이 짧은 경우 통계적 신뢰성이 떨어질 수 있습니다. 미래에도 동일한 경향이 지속된다고 보장할 수 없습니다.
{: .notice--warning}

지난 2년 10개월간 거치식으로 투자했다고 가정합니다.

IDVO의 투자 비중을 조절하여 표준편차나 MDD를 동일하게 맞추면, CAGR이 평균 20.2%인 포트폴리오를 만들 수 있습니다.
이 포트폴리오는 SPY의 18.7%보다 1.5% 높았습니다.

### SPY &lt; IDVO
{: .text-center}


## 관련 정보

- [[초급 부록 B4] 다시 보는 KODEX 200과 SPY (평균-분산 그래프에서는 어느 자산이 투자에 유리했을까?)](https://kongdori.tistory.com/398)
- [S&P 500 국내 ETF는 무엇을 좋을까? (국내 상장 ETF 9종 비교와 분석)](https://kongdori.tistory.com/309)
- [주식 수익률은 어떤 분포일까? (KODEX 200, SPY 환헤지/환노출, 그리고 정규분포, 갑돌이의 은퇴 자금 마련 #1)](https://kongdori.tistory.com/220)
- [VOO나 IVV는 SPY에 비해 수익률이 얼마나 높은 걸까?](https://kongdori.tistory.com/53)
- [유사 종목 성과 비교 목록](/vs/){: .btn .btn--info}


## 참고 도서 [오렌지사과의 출간 책 소개와 샘플북 목록](https://kongdori.tistory.com/691)

- [왜 위험한 주식에 투자하라는 걸까? - 장기 투자와 분산 투자에 대한 통계학적 시각](https://kongdori.tistory.com/421)
- [파이썬으로 그려보는 투자 포트폴리오 분석  - 정량적 투자 분석을 위한 입문서](https://kongdori.tistory.com/643)
- [구글 시트로 시작하는 투자 포트폴리오 분석 - 오렌지사과의 불친절한 워크북](https://kongdori.tistory.com/449)

{% include commons/footnotes.md %}