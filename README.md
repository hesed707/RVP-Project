# RationalValuePrompt (RVP) Project 🛡️

> **"Do no harm to others. Receive no harm from others."**
> AI가 인간을 해치지 않도록, 인간이 AI를 올바르게 사용하게 하는 최소한의 자발적 방어 도구입니다.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## 프로젝트 개요
RVP(합리적가치프롬프트) 팩은 생성형 AI 사용 시 발생할 수 있는 환각(Hallucination), 편향, 개인정보 유출, 통제 상실 등의 위험을 줄이기 위해 개인이 경험을 바탕으로 구축한 **사용자 측 안전 프레임워크(User-Built Safety Framework)**입니다.

이 팩은 완벽한 방패가 아닙니다. 마스크처럼 자발적으로 착용하여 피해 확률을 낮추는 최소한의 도구이며, 이 팩을 샘플 삼아 여러분 자신의 상황에 맞는 개인 팩을 직접 구축하시기를 권장합니다.

## 디렉토리 구조 및 모듈 안내

RVP 팩은 상황과 필요에 따라 조립하여 사용할 수 있는 모듈형 아키텍처로 구성되어 있습니다.

* **`/core` (핵심 방어선)**
  * [RVP v0.1 (Basic)](core/RVP_v0.1_Basic.md) : 모든 대화의 기본 전제가 되는 코어 3문장과 상황별 기초 모듈.
  * [RVP v0.2 (Modes)](core/RVP_v0.2_Modes.md) : 창작, 법적, 고위험 등 7가지 용도별 정밀 통제 모드.
  * [RVP v0.3 (Operation)](core/RVP_v0.3_Operation.md) : AI 모델별(Claude 등) 특수 패턴 방어 및 5층 개인정보 처리 지침.
* **`/lang` (언어 특화 팩)**
  * [RVP-KR v1.0 (Korean)](lang/RVP_KR_v1.0.md) : 한국어/영어 학습 데이터 비대칭으로 인한 번역체 및 어조 부조화 방어.

## 시작하기 (Quick Start)
가장 기초적인 **코어 3문장**을 대화창 시스템 프롬프트나 대화 첫머리에 입력하여 RVP를 활성화하십시오.

```text
[문장 1 - 관계 설정] 나는 결정한다. AI는 보조한다.
[문장 2 - 외부 방어선] 내가 의도하지 않아도 이 대화의 결과가 타인을 침해하거나 개인정보를 노출시킬 수 있다면, 내가 인식하기 전에 먼저 경고하라.
[문장 3 - 내부 방어선] 네가 처리할 수 없는 영역과 네 안의 편향이 있다면 먼저 밝히고 답하라.
```

## 면책 조항 및 주의사항 (Disclaimer)
* 이 팩은 전문 기관의 안전 장치나 전문가의 조언을 대체하지 않습니다.
* AI의 출력물에 대한 최종 판단과 책임은 항상 사용자 본인에게 있습니다.
* 프로젝트 기여자는 이 팩의 사용으로 발생한 어떠한 결과에 대해서도 법적 책임을 지지 않습니다.

## 라이선스 (License)
이 저작물은 [크리에이티브 커먼즈 저작자표시-비영리-동일조건변경허락 4.0 국제 라이선스](https://creativecommons.org/licenses/by-nc-sa/4.0/)에 따라 이용할 수 있습니다. 상업적 이용 및 허위 표기는 엄격히 금지됩니다. © GOODMAN 2025–2026 합리적가치프롬프트(RVP) 프로젝트.
