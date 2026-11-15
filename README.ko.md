<p align="center">
  🇰🇷 한국어 | 🇺🇸 <a href="./README.md">English</a>
</p>

<h2 align="center">
  <em>"복잡한 문제에서 구조를 찾는 일은 하나의 예술이다."</em>
</h2>

<p align="center">
  컴퓨터공학 학부연구생<br>
  계산신경과학 · 학습과 의사결정 · 계산정신의학
</p>

<p align="center">
  <a href="https://junho.art"><img src="https://img.shields.io/badge/Website-junho.art-1f6feb?style=for-the-badge"/></a>
  <a href="mailto:junho@junho.art"><img src="https://img.shields.io/badge/Email-junho%40junho.art-6f42c1?style=for-the-badge"/></a>
</p>

---

## 안녕하세요, 허준호입니다 👋

저는 계산신경과학, 뇌 네트워크 모델링, 인간의 학습과 의사결정, 계산정신의학에 관심을 가진 컴퓨터공학 학부연구생입니다.

주의와 각성, 학습 효율이 변화하는 경험을 통해 같은 사람도 내적 상태에 따라 정보를 다르게 처리할 수 있는 이유와, 사람마다 서로 다른 인지적·행동적 양상이 나타나는 이유에 관심을 갖게 되었습니다. 개인적 경험을 과학적 근거로 일반화하지 않고, 검증할 연구 질문의 출발점으로 삼아 계산 모델과 행동·신경 데이터를 통해 탐구하고자 합니다.

## 연구 관심 분야

- 계산신경과학
- 뇌 네트워크 모델링
- 신경 및 행동 데이터 분석
- 인간의 학습·일반화·의사결정
- 계산정신의학

## 현재 연구 경험

현재 백석대학교 Brain–AI Interface Lab에서 학부연구생으로 활동하고 있습니다.

- 교차검증한 집단 벡터로 M1 spike에서 팔 뻗기 방향 디코딩 ([Population-vector-decoding](https://github.com/Brain-AI-Interface-lab/Population-vector-decoding))
- Blackrock Cerebus/BOSS로 spike 파형 확인 및 실습 데이터의 PCA 기반 spike sorting
- 계산신경과학 및 신경 데이터 분석 관련 논문 검토
- 저널 토론 참여
- 신경 데이터 전처리의 기초 워크플로 학습
- 초기 연구 질문 구체화와 분석 환경 마련에 참여

## 현재 연구 방향

특히 다음 질문에 관심이 있습니다.

- 주의와 각성이 학습·추론·의사결정에 어떤 영향을 미치는가
- 뇌가 감각 증거와 사전지식을 어떻게 통합하는가
- 뇌 네트워크의 상호작용에서 학습과 일반화가 어떻게 나타나는가
- 신경 계산의 변화가 행동의 차이와 정신의학적 증상으로 어떻게 이어지는가
- 계산 모델로 개인 내 변동성과 개인차를 어떻게 함께 설명할 수 있는가

## 메인 프로젝트

### [Population-vector-decoding](https://github.com/Brain-AI-Interface-lab/Population-vector-decoding)

<a href="https://github.com/Brain-AI-Interface-lab/Population-vector-decoding"><img src="https://raw.githubusercontent.com/Brain-AI-Interface-lab/Population-vector-decoding/main/outputs/population_vector/pv_direction_mean_tet.gif" width="380" align="right" alt="8개 방향의 집단 벡터"/></a>

공개된 원숭이 M1 reaching 데이터(Flint et al., 2012)에 Georgopoulos et al.(1982, 1986)의 방향 튜닝과 집단 벡터 디코딩을 적용한 Julia 프로젝트입니다.

- 방향별 평균 발화율로 코사인 튜닝 피팅, 82개 중 34개 unit 튜닝(R² ≥ 0.7)
- 교차검증 집단 벡터: 방향별 평균 기준 목표 방향과의 오차 중앙값 12°, 단일 trial 8방향 정답률 59%(우연 수준 12.5%)
- 시간에 따른 분석: 집단 벡터가 손 속도보다 약 100 ms 먼저 커짐

<br clear="right"/>

## 주요 프로젝트

### [TrendXiv](https://github.com/4season/TrendXiv)

약 82,000편의 arXiv 컴퓨터과학 논문을 대상으로 단기 관심도 수준을 분류한 머신러닝 파이프라인입니다. 시간 분할 검증, 데이터 누출 통제, 주제 분야 특성에 대한 모델 의존성 분석에 중점을 두었습니다.

### [ConvDDI](https://github.com/4season/ConvDDI)

CNN으로 알약 이미지를 분류한 뒤, 예측 결과를 성분 및 병용금기 데이터베이스와 연결하여 규칙 기반으로 약물 간 병용금기를 확인하는 파이프라인입니다.

### [sobdm-project](https://github.com/4season/sobdm-project)

운행, 교통, 날씨와 주기적 시간 특성을 통합한 MLP 기반 버스 도착 예측 프로젝트입니다. 서로 독립적으로 수집된 데이터의 시간 정렬과 표현 방식에 중점을 두었습니다.

### [Magnolia](https://github.com/4season/Magnolia)

알림 데이터를 처리하고 카카오톡으로 전달하는 API 서버와 Android 애플리케이션입니다.

### [junho.art](https://github.com/4season/junho.art)

HTML, CSS, JavaScript로 개발한 반응형 연구 포트폴리오 웹사이트입니다. GraphQL API를 이용해 GitHub 프로젝트 정보를 자동으로 동기화합니다.

## 기술 기반

### 핵심 프로그래밍 및 분석

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
</p>

### 연구 및 개발 도구

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black"/>
  <img src="https://img.shields.io/badge/Oracle%20Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

그 밖에 프로젝트를 통해 MATLAB, Julia, Rust, Go, JavaScript, Node.js를 사용한 경험이 있습니다.

## 현재 학습 목표

- 뇌 계산 모델링
- 뇌영상 분석
- 확률 모델링
- 강화학습과 의사결정
- 신경 및 인지 과정의 수학적 모델링

## 연락처

- 웹사이트: [junho.art](https://junho.art)
- 이메일: [junho@junho.art](mailto:junho@junho.art)
- ORCID: [0009-0004-8594-9000](https://orcid.org/0009-0004-8594-9000)

