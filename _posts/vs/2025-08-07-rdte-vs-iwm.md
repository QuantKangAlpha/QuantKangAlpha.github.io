---
layout: single
title: RDTE vs IWM
excerpt: RDTE의 최근 10개월 CAGR은 11.4%로 IWM의 7.5%보다 3.9% 높았습니다.
header:
  overlay_color: "#333"
  show_overlay_excerpt: false
toc: true
categories:
- vs
keywords: IWM, RDTE, RDTE IWM 비교
---

## 비교 상품 소개


RDTE 상품과 IWM 상품의 성과를 수익률과 위험도로 비교합니다.





{% include commons/vs-notice.md %}

## 지난 성과

두 상품의 성과를 비교할 수 있는 가장 긴 기간은 최근 10개월입니다. 아래는 이 기간의 성과[^fn_vs_perf]를 그래프와 표로 나타낸 것입니다.
그래프 범례에서 괄호안의 퍼센트 수치는 CAGR[^fn_vs_cagr_metric]입니다.
하단의 보조 그래프는 IWM 대비 RDTE의 비를 나타냅니다.
RDTE의 수익률이 IWM보다 지속적으로 우세하면 상승하고, 반대의 경우에는 하락합니다.

![RDTE](/vs/images/rdte-vs-iwm_dual.png){: .align-center}

| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| RDTE | <span style="color: tomato">11.4<small>%</small></span> | 20.8<small>%</small> | 0.55 | -24.3<small>%</small> | -6.9<small>%</small> |
| IWM | <span style="color: tomato">7.5<small>%</small></span> | 23.4<small>%</small> | 0.32 | -27.5<small>%</small> | -9.0<small>%</small> |

<!-- more -->


성과를 분석하는 전통적인 방법인 수익률과 위험도[^fn_vs_risk]를 살펴봅니다.

**수익률 지표 (CAGR):** RDTE의 CAGR은 11.4%로 IWM의 7.5%보다 3.9% 높았습니다. (높은 수익률)[^fn_vs_comp]

**위험도 지표 (표준편차):** RDTE의 표준편차는 20.8%로 IWM의 23.4%보다 -2.6% 낮았습니다. (낮은 위험도)

**위험도 지표 (MDD):** RDTE의 24.3%의 MDD는 IWM의 27.5%보다 -3.2% 낮았습니다. (낮은 위험도)



## 동일 수준 위험 노출을 위한 비중 조절

수익률과 위험도가 다른 상품을 비교하는 방법의 하나는, 둘 중 하나를 동일하게 설정하고, 나머지 하나를 비교하는 것입니다.
여기서는 IWM의 투자 비중[^fn_vs_weight]을 조절하여 RDTE의 위험도와 유사하게 맞추어 수익률를 비교합니다.

**위험도 지표 (표준편차):** 표준편차를 동일한 값으로 맞추기 위해서는 23.4% / 20.8% = 89% 비중으로 투자하면 됩니다.[^fn_vs_sharpe]

**위험도 지표 (MDD):** MDD를 동일한 값으로 맞추기 위해서는 27.5% / 24.3% = 88% 비중으로 투자하면 됩니다.


{% include /commons/ads/adsense.html %}



## 동일 수준 위험하에서의 추정 성과

아래는 비중을 조절한 경우를 추가하여, 그래프와 표에 성과를 기록한 것입니다.
IWM<sub>STD</sub>는 표준편차를 맞춘[^fn_vs_weighting] 경우이고, IWM<sub>MDD</sub>는 MDD를 맞춘 경우입니다.
앞에서와 같이 그래프 범례에서 괄호안의 퍼센트 수치는 CAGR입니다.


![RDTE](/vs/images/rdte-vs-iwm.png){: .align-center}



| **종목** | **CAGR** | **편차** | **샤프** | **MDD** | **AvDD** |
| :------------ | ------: | -----------: | -------: | ------: | -------: |
| RDTE | <span style="color: tomato">11.4<small>%</small></span> | 20.8<small>%</small> | 0.55 | -24.3<small>%</small> | -6.9<small>%</small> |
| IWM | <span style="color: tomato">7.5<small>%</small></span> | 23.4<small>%</small> | 0.32 | -27.5<small>%</small> | -9.0<small>%</small> |
| IWM<sub>STD</sub> <small>(89%)</small> | <span style="color: tomato">6.9<small>%</small></span> | 20.8<small>%</small> | 0.33 | -24.8<small>%</small> | -8.0<small>%</small> |
| IWM<sub>MDD</sub> <small>(88%)</small> | <span style="color: tomato">6.9<small>%</small></span> | 20.7<small>%</small> | 0.33 | -24.7<small>%</small> | -7.9<small>%</small> |



각각의 경우를 RDTE의 성과와 비교해 봅니다.

**위험도 지표 (표준편차):** 89% 투자 비중으로 표준편차를 비슷한 수준으로 맞추면, CAGR은 6.9%로 RDTE의 11.4%보다 -4.5% 낮았습니다. (낮은 수익률)

**위험도 지표 (MDD):** 88% 투자 비중으로 하여 MDD를 비슷한 수준으로 맞추면, CAGR은 6.9%로 RDTE의 11.4%보다 -4.5% 낮았습니다. (낮은 수익률)




## 최종 비교

**주의** 투자 시점과 기간, 그리고 전략에 따라 다른 결과가 나올 수 있습니다. 백테스트 기간이 짧은 경우 통계적 신뢰성이 떨어질 수 있습니다. 미래에도 동일한 경향이 지속된다고 보장할 수 없습니다.
{: .notice--warning}

지난 10개월간 거치식으로 투자했다고 가정합니다.

IWM의 투자 비중을 조절하여 표준편차나 MDD를 동일하게 맞추면, CAGR이 평균 6.9%인 포트폴리오를 만들 수 있습니다.
이 포트폴리오는 RDTE의 11.4%보다 -4.5% 낮았습니다.

### RDTE &gt; IWM
{: .text-center}


## 관련 정보

- [IWM(미국 소형주) + SPY + 환율 + 예금 분산 투자 (평균-분산 그래프 분석) [자산 배분 시즌 2]](https://m.blog.naver.com/onuri2005/223923687939)
- [유사 종목 성과 비교 목록](/vs/){: .btn .btn--info}


## 참고 도서 [오렌지사과의 출간 책 소개와 샘플북 목록](https://kongdori.tistory.com/691)

- [왜 위험한 주식에 투자하라는 걸까? - 장기 투자와 분산 투자에 대한 통계학적 시각](https://kongdori.tistory.com/421)
- [파이썬으로 그려보는 투자 포트폴리오 분석  - 정량적 투자 분석을 위한 입문서](https://kongdori.tistory.com/643)
- [구글 시트로 시작하는 투자 포트폴리오 분석 - 오렌지사과의 불친절한 워크북](https://kongdori.tistory.com/449)

{% include commons/footnotes.md %}