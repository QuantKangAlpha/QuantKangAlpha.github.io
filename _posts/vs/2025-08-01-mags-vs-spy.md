---
layout: single
title: MAGS vs SPY
excerpt: MAGS의 최근 2년 3개월 CAGR은 44.7%로 SPY의 21.4%보다 23.4% 높았습니다.
header:
  overlay_color: "#333"
  show_overlay_excerpt: false
toc: true
categories:
- vs
keywords: SPY, MAGS, MAGS SPY 비교
---

## 비교 상품 소개


MAGS 상품과 SPY 상품의 성과를 수익률과 위험도로 비교합니다.





{% include commons/vs-notice.md %}

## 지난 성과

두 상품의 성과를 비교할 수 있는 가장 긴 기간은 최근 2년 3개월입니다. 아래는 이 기간의 성과[^fn_vs_perf]를 그래프와 표로 나타낸 것입니다.
그래프 범례에서 괄호안의 퍼센트 수치는 CAGR[^fn_vs_cagr_metric]입니다.
하단의 보조 그래프는 SPY 대비 MAGS의 비를 나타냅니다.
MAGS의 수익률이 SPY보다 지속적으로 우세하면 상승하고, 반대의 경우에는 하락합니다.

![MAGS](/vs/images/mags-vs-spy_dual.png){: .align-center}

| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| MAGS | <span style="color: tomato">44.7<small>%</small></span> | 27.5<small>%</small> | 1.62 | -29.9<small>%</small> | -4.9<small>%</small> |
| SPY | <span style="color: tomato">21.4<small>%</small></span> | 15.8<small>%</small> | 1.35 | -18.8<small>%</small> | -2.2<small>%</small> |

<!-- more -->


성과를 분석하는 전통적인 방법인 수익률과 위험도[^fn_vs_risk]를 살펴봅니다.

**수익률 지표 (CAGR):** MAGS의 CAGR은 44.7%로 SPY의 21.4%보다 23.4% 높았습니다. (높은 수익률)[^fn_vs_comp]

**위험도 지표 (표준편차):** MAGS의 표준편차는 27.5%로 SPY의 15.8%보다 11.7% 높았습니다. (높은 위험도)

**위험도 지표 (MDD):** MAGS의 29.9%의 MDD는 SPY의 18.8%보다 11.2% 높았습니다. (높은 위험도)



## 동일 수준 위험 노출을 위한 비중 조절

수익률과 위험도가 다른 상품을 비교하는 방법의 하나는, 둘 중 하나를 동일하게 설정하고, 나머지 하나를 비교하는 것입니다.
여기서는 SPY의 투자 비중[^fn_vs_weight]을 조절하여 MAGS의 위험도와 유사하게 맞추어 수익률를 비교합니다.

**위험도 지표 (표준편차):** 표준편차를 동일한 값으로 맞추기 위해서는 15.8% / 27.5% = 174% 비중으로 투자하면 됩니다.[^fn_vs_sharpe]

**위험도 지표 (MDD):** MDD를 동일한 값으로 맞추기 위해서는 18.8% / 29.9% = 159% 비중으로 투자하면 됩니다.


{% include /commons/ads/adsense.html %}



## 동일 수준 위험하에서의 추정 성과

아래는 비중을 조절한 경우를 추가하여, 그래프와 표에 성과를 기록한 것입니다.
SPY<sub>STD</sub>는 표준편차를 맞춘[^fn_vs_weighting] 경우이고, SPY<sub>MDD</sub>는 MDD를 맞춘 경우입니다.
앞에서와 같이 그래프 범례에서 괄호안의 퍼센트 수치는 CAGR입니다.


![MAGS](/vs/images/mags-vs-spy.png){: .align-center}



| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| MAGS | <span style="color: tomato">44.7<small>%</small></span> | 27.5<small>%</small> | 1.62 | -29.9<small>%</small> | -4.9<small>%</small> |
| SPY | <span style="color: tomato">21.4<small>%</small></span> | 15.8<small>%</small> | 1.35 | -18.8<small>%</small> | -2.2<small>%</small> |
| SPY<sub>STD</sub> <small>(174%)</small> | <span style="color: tomato">37.8<small>%</small></span> | 27.5<small>%</small> | 1.37 | -30.8<small>%</small> | -4.0<small>%</small> |
| SPY<sub>MDD</sub> <small>(159%)</small> | <span style="color: tomato">34.6<small>%</small></span> | 25.3<small>%</small> | 1.37 | -28.6<small>%</small> | -3.7<small>%</small> |



각각의 경우를 MAGS의 성과와 비교해 봅니다.

**위험도 지표 (표준편차):** 174% 투자 비중으로 표준편차를 비슷한 수준으로 맞추면, CAGR은 37.8%로 MAGS의 44.7%보다 -6.9% 낮았습니다. (낮은 수익률)

**위험도 지표 (MDD):** 159% 투자 비중으로 하여 MDD를 비슷한 수준으로 맞추면, CAGR은 34.6%로 MAGS의 44.7%보다 -10.1% 낮았습니다. (낮은 수익률)




## 최종 비교

**주의** 투자 시점과 기간, 그리고 전략에 따라 다른 결과가 나올 수 있습니다. 백테스트 기간이 짧은 경우 통계적 신뢰성이 떨어질 수 있습니다. 미래에도 동일한 경향이 지속된다고 보장할 수 없습니다.
{: .notice--warning}

지난 2년 3개월간 거치식으로 투자했다고 가정합니다.

SPY의 투자 비중을 조절하여 표준편차나 MDD를 동일하게 맞추면, CAGR이 평균 36.2%인 포트폴리오를 만들 수 있습니다.
이 포트폴리오는 MAGS의 44.7%보다 -8.5% 낮았습니다.

### MAGS &gt; SPY
{: .text-center}


## 관련 정보

- [유사 종목 성과 비교 목록](/vs/){: .btn .btn--info}


## 참고 도서 [오렌지사과의 출간 책 소개와 샘플북 목록](https://kongdori.tistory.com/691)

- [왜 위험한 주식에 투자하라는 걸까? - 장기 투자와 분산 투자에 대한 통계학적 시각](https://kongdori.tistory.com/421)
- [파이썬으로 그려보는 투자 포트폴리오 분석  - 정량적 투자 분석을 위한 입문서](https://kongdori.tistory.com/643)
- [구글 시트로 시작하는 투자 포트폴리오 분석 - 오렌지사과의 불친절한 워크북](https://kongdori.tistory.com/449)

{% include commons/footnotes.md %}