# LLM 기반 업무 자동화 프롬프트 엔지니어링 프로젝트

## 프로젝트 개요

본 프로젝트는 **서비스 시장 분석(TAM, SAM, SOM 산출)** 업무에 가장 적합한 LLM 모델을 선정하기 위한 프롬프트 엔지니어링 프로젝트이다.

### 업무 과업

서비스 정보를 입력받아 다음 내용을 포함한 시장 분석 보고서를 생성한다.

* 시장 정의
* TAM (Total Addressable Market)
* SAM (Serviceable Available Market)
* SOM (Serviceable Obtainable Market)
* 경쟁사 분석
* 시장 진입 전략

### 타겟 사용자

* 스타트업 창업자
* 서비스 기획자
* 신규 사업 담당자
* PM(Product Manager)

### 입력 데이터

* 서비스 설명
* 타겟 고객
* 시장 범위
* 수익 모델

### 출력 결과

* TAM
* SAM
* SOM
* 경쟁사 분석
* 시장 진입 전략

---

# 제출 문서

## 1. 모델 비교 및 선정

파일:

`01_model_comparison.md`

내용:

* GPT-4o
* Gemini 2.5 Pro
* Claude Sonnet 4.6
* 평가 축 기반 비교
* 환각(Hallucination) 검증
* 모델 선정 결과
* 심층 인터뷰

바로가기:

[01_model_comparison.md](./01_model_comparison.md)

---

## 2. 시스템 설계

파일:

`02_system_design.md`

내용:

* 시스템 프롬프트
* 유저 프롬프트
* 입력 템플릿
* Few-shot 예시
* 모호한 입력에 대한 되묻기
* 프롬프트 개선(v1 → v2)

바로가기:

[02_system_design.md](./02_system_design.md)

---

## 3. 실행 로그

파일:

`03_conversation_log.md`

내용:

* 실제 실행 로그
* 10턴 이상 대화
* 조건 변경 사례
* 결과 검증

바로가기:

[03_conversation_log.md](./03_conversation_log.md)

---

# 평가 기준 대응

| 평가 항목          | 문서                     |
| -------------- | ---------------------- |
| 업무 과업 정의       | README.md              |
| 입력 템플릿         | 02_system_design.md    |
| Few-shot 예시    | 02_system_design.md    |
| 시스템 프롬프트       | 02_system_design.md    |
| 유저 프롬프트        | 02_system_design.md    |
| 프롬프트 개선(v1→v2) | 02_system_design.md    |
| 모델 비교          | 01_model_comparison.md |
| 환각 검증          | 01_model_comparison.md |
| 모델 선정 이유       | 01_model_comparison.md |
| 심층 인터뷰         | 01_model_comparison.md |
| 10턴 이상 로그      | 03_conversation_log.md |
| 조건 변경 반영       | 03_conversation_log.md |

---

본 저장소의 모든 결과물은 위 3개 문서에 포함되어 있다.

