---
layout: single
title: "1.CUI (Corrosion Under Insulation)"
categories: Piping
tag: [Corrosion, CUI]
toc: true
---

# CUI (Corrosion Under Insulation) – API 571 기준 정리

**CUI(Corrosion Under Insulation, 보온재 하부 부식)**는 보온재 내부에 수분이 침투하면서 배관이나 장비 외부 표면에서 발생하는 국부적인 부식 현상입니다. API 571에서는 CUI를 주요 손상 메커니즘 중 하나로 분류하며, 주로 탄소강 및 저합금강에서 문제가 발생합니다.

---

## 1. 손상 메커니즘 개요

- **정의:** 보온재로 덮인 장비 표면에 수분이 침투해 부식을 유발
- **원인:** 비, 응축수, 공기 중 수분, 배관 누수 등이 보온재 내부로 유입
- **위험성:** 보온재가 부식을 가려 외관상 식별이 어렵고, 심각한 국부 부식 유발

---

## 2. CUI 유발 주요 요인

| 요인                            | 설명                                                         |
| ------------------------------- | ------------------------------------------------------------ |
| **Temperature**                 | 특정 온도 범위에서 수분이 응축 또는 증발하지 않고 금속 표면에 머물며 부식을 유발 |
| **Duration of Wetting**         | 금속이 젖어 있는 시간이 길수록 부식 위험 증가                |
| **Design of Insulation System** | Drainage 부족, 방수 미비 설계는 침수 및 고인 수분 문제 발생  |
| **Type of Insulation**          | 흡수성 보온재 (예: Calcium Silicate, Mineral Wool)는 수분 흡수에 취약 |
| **External Environment**        | 해안가, 고습 지역, 우천이 잦은 기후에서는 CUI 가능성 증가    |

---

## 3. 주요 대상 재질 및 취약 온도 범위

| 재질 구분                                          | 적용 온도 범위 (°C) | 주요 손상 유형                      |
| -------------------------------------------------- | ------------------- | ----------------------------------- |
| 탄소강 (CS), 저온탄소강 (LTCS), 400계 스테인리스강 | -12 ~ 175           | 일반적인 CUI                        |
| 300계 스테인리스강 (예: 304, 316)                  | 60 ~ 175            | 염화물 응력 부식균열 (Chloride SCC) |
| 듀플렉스 스테인리스강 (Duplex SS)                  | 140 ~ 175           | 염화물 SCC 위험 존재 (고온 조건)    |

> *위 범위는 수분 존재 및 염분 환경을 가정한 일반적인 경향이며, 실제는 장비 조건 및 환경에 따라 달라질 수 있습니다.*

---

## 4. 육안 징후

- 보온재 외부의 **녹물 자국, 습기, 보온재 탈락**
- 배관 표면의 **피팅부, 용접부** 등에서 집중적으로 발생
- 보온재 제거 전까지 **시각적으로 식별 어려움**

---

## 5. 검사 방법 (Inspection Techniques)

- **Visual Inspection (VT):** 보온재 제거 후 육안 점검
- **Ultrasonic Thickness (UT):** 두께 측정
- **Radiographic Testing (RT):** 외부에서 부식 부위 탐지
- **고위험 영역 우선 검사:** 지지대 인접, 드레인 주변, 노출 가능 지점

---

## 6. 예방 및 관리 방안

- **방수성 보온재 사용 (Hydrophobic Insulation)**
- **도장(Coating) 및 표면 처리** 후 보온재 설치
- **Drainage 및 Vapor Barrier** 확보
- **정기적 유지보수 및 검사 계획 수립**
- **부식 민감 구간 설계 시 보강 조치 및 재질 변경 고려**

---

## 7. 도장 사양 기준 (실무 경험 기반)

### ▶️ **CUI 관련 도장 사양의 온도 기준: 175°C**

프로젝트의 **도장 스펙(Painting Specification)**에서는 일반적으로 **175°C**를 기준으로 보온 대상 배관의 도장 유무가 결정됩니다.

- **175°C 이상:**  
  고온으로 인해 **도장이 적용되지 않음**
- **175°C 미만:**  
  보온 하부 CUI 방지를 위해 **하도(Primer Coat)**만 적용하는 경우 많음

### ▶️ **Austenitic Stainless Steel의 경우**

- **염화물 SCC**에 취약한 **300계 스테인리스강(예: 304, 316)**은 **염소 이온 + 고온** 환경에서 부식이 빠르게 진행됨
- **175°C 이하인 경우에는 도장을 통해 부식 예방 가능**
- 따라서, 스테인리스강에도 **온도에 따라 도장 적용 여부가 명확히 구분**됨

> *즉, CUI 및 SCC 예방을 위한 도장 설계 기준이 실무에서도 "175도"를 기준으로 정형화되어 있음*

---

## 8. 연관 손상 메커니즘

- **염화물 SCC (Chloride Stress Corrosion Cracking):**  
  스테인리스강이 염화물이 존재하는 보온재 하에서 고온 환경에 노출될 경우 발생

---

## 9. API 571 관련 조항

| 항목        | 설명                                        |
| ----------- | ------------------------------------------- |
| **4.3.3**   | CUI - 탄소강 및 저합금강 대상               |
| **5.1.1.3** | 염화물 SCC - 오스테나이트 스테인리스강 대상 |

