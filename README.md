# LLM 기반 업무 자동화 프롬프트 엔지니어링 프로젝트

## 프로젝트 개요

본 프로젝트는 **서비스 시장 분석(TAM, SAM, SOM 산출)** 업무에 가장 적합한 대규모 언어 모델(LLM)을 선정하기 위해 수행한 프롬프트 엔지니어링 프로젝트이다.

### 업무 과업 정의

* 업무 과업: 서비스 시장 분석 보고서 작성
* 타겟 사용자: 스타트업 창업자 및 서비스 기획자
* 입력 데이터

  * 서비스 설명
  * 타겟 고객
  * 시장 범위
  * 수익 모델
* 출력 결과

  * TAM(Total Addressable Market)
  * SAM(Serviceable Available Market)
  * SOM(Serviceable Obtainable Market)
  * 경쟁사 분석
  * 시장 진입 전략

---

## 저장소 구성

```text
.
├── README.md
├── 01_model_comparison.md
├── 02_system_design.md
└── 03_conversation_log.md
```

---

## 제출 문서

### 01_model_comparison.md

모델 비교 및 선정 문서

포함 내용

* GPT-4o
* Claude Sonnet
* Gemini
* 모델 비교 평가표
* 평가 축 기반 성능 비교
* 환각(Hallucination) 검증
* 최종 모델 선정 근거
* 심층 인터뷰 문항 답변

---

### 02_system_design.md

시스템 설계 문서

포함 내용

* 시스템 프롬프트
* 유저 프롬프트
* 입력 템플릿
* Few-shot 예시
* 모호한 입력에 대한 되묻기 설계
* 프롬프트 개선 과정(v1 → v2)

---

### 03_conversation_log.md

실행 로그 문서

포함 내용

* 실제 실행 대화 로그
* 10턴 이상 대화
* 중간 조건 변경 사례
* 결과 검증 과정
* 최종 출력 결과

---

## 평가 기준 대응표

| 평가 항목          | 확인 문서                          |
| -------------- | ------------------------------ |
| 업무 과업 정의       | 02_system_design.md |
| 입력 템플릿         | 01_model_comparison.md          |
| 모델 비교          | 01_model_comparison.md         |
| 평가 축 기반 비교     | 01_model_comparison.md         |
| Few-shot 예시    | 02_system_design.md            |
| 모호한 입력 → 되묻기   | 02_system_design.md            |
| 환각 검증          | 01_model_comparison.md         |
| 10턴 이상 대화 로그   | 03_conversation_log.md         |
| 조건 변경 반영       | 03_conversation_log.md         |
| 프롬프트 분리        | 02_system_design.md            |
| 프롬프트 개선(v1→v2) | 02_system_design.md            |
| 모델 선정 이유       | 01_model_comparison.md         |
| 무료 모델 사용 전략    | 01_model_comparison.md         |
| 정책 변경 대응 전략    | 01_model_comparison.md         |
| 문맥 단절 개선 전략    | 01_model_comparison.md         |

---

## 문서 바로가기

* [01_model_comparison.md](./01_model_comparison.md)
* [02_system_design.md](./02_system_design.md)
* [03_conversation_log.md](./03_conversation_log.md)

---

본 저장소는 프롬프트 엔지니어링 프로젝트 제출을 위한 결과물이며, 모든 평가 기준에 대응하는 내용은 위 3개 문서에 정리되어 있다.

