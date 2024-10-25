---
layout: single
title: JEPI vs SPY
excerpt: JEPI의 최근 4년 5개월 CAGR은 13.3%로 SPY의 18.2%보다 -5.0% 낮았습니다.
header:
  overlay_color: "#333"
  show_overlay_excerpt: false
toc: true
categories:
- vs
keywords: SPY, JEPI, JEPI SPY 비교
---

## 비교 상품 소개


JEPI 상품과 SPY 상품의 성과를 수익률과 위험도로 비교합니다.





{% include commons/vs-notice.md %}

## 지난 성과

두 상품의 성과를 비교할 수 있는 가장 긴 기간은 최근 4년 5개월입니다. 아래는 이 기간의 성과[^fn_vs_perf]를 그래프와 표로 나타낸 것입니다.
그래프 범례에서 괄호안의 퍼센트 수치는 CAGR[^fn_vs_cagr_metric]입니다.
하단의 보조 그래프는 SPY 대비 JEPI의 비를 나타냅니다.
JEPI의 수익률이 SPY보다 지속적으로 우세하면 상승하고, 반대의 경우에는 하락합니다.

![JEPI](/vs/images/jepi-vs-spy_dual.png){: .align-center}

| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| JEPI | <span style="color: tomato">13.3<small>%</small></span> | 10.3<small>%</small> | 1.28 | -13.7<small>%</small> | -2.1<small>%</small> |
| SPY | <span style="color: tomato">18.2<small>%</small></span> | 16.8<small>%</small> | 1.08 | -24.5<small>%</small> | -5.8<small>%</small> |

<!-- more -->


성과를 분석하는 전통적인 방법인 수익률과 위험도[^fn_vs_risk]를 살펴봅니다.

**수익률 지표 (CAGR):** JEPI의 CAGR은 13.3%로 SPY의 18.2%보다 -5.0% 낮았습니다. (낮은 수익률)[^fn_vs_comp]

**위험도 지표 (표준편차):** JEPI의 표준편차는 10.3%로 SPY의 16.8%보다 -6.5% 낮았습니다. (낮은 위험도)

**위험도 지표 (MDD):** JEPI의 13.7%의 MDD는 SPY의 24.5%보다 -10.8% 낮았습니다. (낮은 위험도)



## 동일 수준 위험 노출을 위한 비중 조절

수익률과 위험도가 다른 상품을 비교하는 방법의 하나는, 둘 중 하나를 동일하게 설정하고, 나머지 하나를 비교하는 것입니다.
여기서는 SPY의 투자 비중[^fn_vs_weight]을 조절하여 JEPI의 위험도와 유사하게 맞추어 수익률를 비교합니다.

**위험도 지표 (표준편차):** 표준편차를 동일한 값으로 맞추기 위해서는 16.8% / 10.3% = 62% 비중으로 투자하면 됩니다.[^fn_vs_sharpe]

**위험도 지표 (MDD):** MDD를 동일한 값으로 맞추기 위해서는 24.5% / 13.7% = 56% 비중으로 투자하면 됩니다.


{% include /commons/ads/adsense.html %}



## 동일 수준 위험하에서의 추정 성과

아래는 비중을 조절한 경우를 추가하여, 그래프와 표에 성과를 기록한 것입니다.
SPY<sub>STD</sub>는 표준편차를 맞춘[^fn_vs_weighting] 경우이고, SPY<sub>MDD</sub>는 MDD를 맞춘 경우입니다.
앞에서와 같이 그래프 범례에서 괄호안의 퍼센트 수치는 CAGR입니다.


![JEPI](/vs/images/jepi-vs-spy.png){: .align-center}



| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| JEPI | <span style="color: tomato">13.3<small>%</small></span> | 10.3<small>%</small> | 1.28 | -13.7<small>%</small> | -2.1<small>%</small> |
| SPY | <span style="color: tomato">18.2<small>%</small></span> | 16.8<small>%</small> | 1.08 | -24.5<small>%</small> | -5.8<small>%</small> |
| SPY<sub>STD</sub> <small>(62%)</small> | <span style="color: tomato">11.2<small>%</small></span> | 10.3<small>%</small> | 1.09 | -15.4<small>%</small> | -3.4<small>%</small> |
| SPY<sub>MDD</sub> <small>(56%)</small> | <span style="color: tomato">10.2<small>%</small></span> | 9.4<small>%</small> | 1.09 | -14.1<small>%</small> | -3.1<small>%</small> |



각각의 경우를 JEPI의 성과와 비교해 봅니다.

**위험도 지표 (표준편차):** 62% 투자 비중으로 표준편차를 비슷한 수준으로 맞추면, CAGR은 11.2%로 JEPI의 13.3%보다 -2.0% 낮았습니다. (낮은 수익률)

**위험도 지표 (MDD):** 56% 투자 비중으로 하여 MDD를 비슷한 수준으로 맞추면, CAGR은 10.2%로 JEPI의 13.3%보다 -3.1% 낮았습니다. (낮은 수익률)




## 최종 비교

**주의** 투자 시점과 기간, 그리고 전략에 따라 다른 결과가 나올 수 있습니다. 백테스트 기간이 짧은 경우 통계적 신뢰성이 떨어질 수 있습니다. 미래에도 동일한 경향이 지속된다고 보장할 수 없습니다.
{: .notice--warning}

지난 4년 5개월간 거치식으로 투자했다고 가정합니다.

SPY의 투자 비중을 조절하여 표준편차나 MDD를 동일하게 맞추면, CAGR이 평균 10.7%인 포트폴리오를 만들 수 있습니다.
이 포트폴리오는 JEPI의 13.3%보다 -2.5% 낮았습니다.

### JEPI &gt; SPY
{: .text-center}


## 관련 정보

- [SPY로 JEPI처럼 분배금을 만들면 얼마나 남을까? (기초 자산에서 커버드콜 ETF의 분배금만큼 꺼내 써 보자!)](https://kongdori.tistory.com/284)
- [ISPY - ProShares의 초단기 콜옵션 전략 기반 인컴 ETF (넌 누굴 닮았니?)](https://kongdori.tistory.com/267)
- [커버드콜 ETF는 왜 장기 투자에 적합하지 않은가? (효율적 투자선과 50% 오렌지 주스)](https://kongdori.tistory.com/244)
- [JEPI/JEPQ에 장기 배당 재투자하는 것은 좋은 방법일까? (장기투자와 세금)](https://kongdori.tistory.com/216)
- [당신이 JEPI/JEPQ를 사면 안되는 이유 (해외 상장 인컴 ETF의 배당소득세와 양도소득세)](https://kongdori.tistory.com/213)
- [JEPI/JEPQ는 특별한가? (SCHD/QQQ + 현금과의 비교)](https://kongdori.tistory.com/211)
- [JEPI는 SPY보다 더 좋은 ETF인가? (현금 흐름 창출과 배당 재투자 시)](https://kongdori.tistory.com/183)
- [커버드 콜 전략은 유용한가? (커버드 콜 전략을 쓰는 주요 ETF의 지금까지 수익률과 분석)](https://kongdori.tistory.com/155)
- [JEPI는 매달 현금 흐름이 필요한 경우 현명한 선택이었을까? (SCHD와 비교)](https://kongdori.tistory.com/49)
- [유사 종목 성과 비교 목록](/vs/){: .btn .btn--info}

{% include commons/footnotes.md %}