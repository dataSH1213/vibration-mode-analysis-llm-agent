# 🌊 Vibration Analysis LLM Agent (진동 분석 AI 에이전트)

## 📖 Project Overview (프로젝트 개요)
이 프로젝트는 기계나 구조물에서 수집된 **진동 데이터(Vibration Data)**를 입력받아, LLM(거대언어모델)을 통해 **모드 해석(Mode Analysis)** 및 상태 진단을 자동으로 수행하는 에이전트를 개발하는 것을 목표로 합니다.

진동 분석은 전문 지식이 필요하지만, 이 에이전트를 통해 누구나 쉽게 진동 데이터를 해석하고 인사이트를 얻을 수 있도록 돕고자 합니다.

## 🎯 Key Features (주요 기능 - 목표)
- [ ] **데이터 전처리**: 시계열 진동 데이터를 주파수 도메인(FFT)으로 변환
- [ ] **모드 추출**: 고유 진동수(Natural Frequency) 및 모드 형상 파악
- [ ] **AI 분석 리포트**: 분석된 수치를 바탕으로 LLM이 장비의 상태나 이상 유무를 텍스트로 설명
- [ ] **대화형 인터페이스**: 사용자가 "지금 2차 모드에서 문제가 뭐야?"라고 물으면 답변 제공

## 🛠 Tech Stack (사용 기술)
* **Language**: Python
* **Signal Processing**: SciPy, NumPy (FFT, Peak Picking)
* **LLM Integration**: LangChain, OpenAI API (or Local LLM)
* **Framework**: Streamlit (UI 구성 예정)

## 🗓️ Roadmap (개발 계획)

### Phase 1: 기획 및 기초 학습 (Current Stage 🚩)
- [x] 깃허브 리포지토리 생성 및 README 작성
- [ ] 진동 분석 기초 이론 정리 (FFT, 고유 진동수 개념)
- [ ] LLM 에이전트 개발 방법론 학습 (LangChain 기초)

### Phase 2: 데이터 처리 모듈 개발
- [ ] 샘플 진동 데이터 확보 (오픈 데이터셋 또는 가상 데이터 생성)
- [ ] 파이썬을 이용한 FFT 변환 코드 작성
- [ ] 주요 피크(Peak) 감지 알고리즘 구현

### Phase 3: LLM 에이전트 연동
- [ ] 분석된 정량적 데이터(수치)를 텍스트 프롬프트로 변환
- [ ] LLM에게 진동 데이터를 설명하도록 프롬프트 엔지니어링 수행
- [ ] 챗봇 형태의 기본 인터페이스 구축

### Phase 4: 배포 및 문서화
- [ ] Streamlit을 이용한 웹 데모 제작
- [ ] 사용 가이드 문서 작성