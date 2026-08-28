<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0614,25:1E1B4B,50:6D28D9,75:DB2777,100:F472B6&height=290&section=header&text=Min's%20Neural%20Cloud%20Hub&fontFamily=Cinzel&fontSize=50&fontColor=FFFFFF&fontAlignY=36&animation=twinkling&desc=An%20Archive%20of%20AI%20Research%20Projects%20and%20Experiments&descSize=19&descAlignY=59&stroke=F9A8D4&strokeWidth=1"
    width="100%"
    alt="My Neural Cloud Hub"
  />
</p>

<p align="center">
  Medical imaging AI와 reproducible experimentation을 공부하며,<br />
  문제 정의부터 evaluation과 deployment까지 연결되는 프로젝트를 구축하고 있습니다.
</p>

<p align="center">
  <a href="#current-research">Current Research</a> ·
  <a href="#selected-projects">Selected Projects</a> ·
  <a href="#research-interests">Research Interests</a> ·
  <a href="#technical-range">Technical Range</a>
</p>

## Profile

| | |
|---|---|
| Name | Yongmin Park (박용민) |
| Academic Affiliation | 경기대학교(수원) · 컴퓨터공학전공 (Entered in 2022) |
| Academic Status | 3rd-Year Undergraduate Student |
| Current Research | Quantitative Medical Imaging · Musculoskeletal Ultrasound |
| Current Study | Statistical Learning · Modern Deep Learning Foundations |
| Portfolio | [laplace-tech.github.io](https://laplace-tech.github.io/) |
| Email | [add28482848@kyonggi.ac.kr](mailto:add28482848@kyonggi.ac.kr) |

## Current Research

### [UMUD Muscle Ultrasound Research](https://github.com/Laplace-tech/umud-muscle-ultrasound-research) &nbsp;<sub><img src="https://img.shields.io/badge/IN%20PROGRESS-7C3AED?style=flat-square" alt="In Progress" /></sub>

[UMUD Challenge: Muscle Architecture in Ultrasound Data](https://www.kaggle.com/competitions/umud-challenge-muscle-architecture-in-ultrasound-data)를 기반으로, 근골격 초음파 영상에서 muscle architecture를 자동 정량화하는 독립 연구 프로젝트.

- **Targets:** Pennation Angle, Fascicle Length, Muscle Thickness
- **Research direction:** `structure extraction → anatomical geometry → quantitative measurement`
- **Methodology:** leakage-resistant validation, controlled experiments, ablation, error analysis
- **Outcome:** Private Leaderboard 평가와 공개·재현 가능한 research pipeline
- **Current phase:** Competition rules, metric, dataset provenance, sequence grouping audit

> 목표는 단일 제출을 만드는 데 그치지 않고, 외부 검증 가능한 성능과 재현 가능한 연구 근거를 함께 남기는 것입니다.

## About

Exploring diverse AI domains by studying the principles behind modern models
and designing reproducible research pipelines from experimentation to deployment.

## Research Interests

- Quantitative medical image analysis와 domain-aware validation
- Optimization algorithms와 learning dynamics의 mathematical analysis
- Attention과 Vision Transformer의 architecture 및 information flow

## Selected Projects

### 01 · [MediScope](https://github.com/Laplace-tech/capstone-cxr) &nbsp;<sub><img src="https://img.shields.io/badge/Team%20Leader-0F766E?style=flat-square" alt="Team Leader" /></sub>

CNN 기반 Chest X-ray classification model과 Grad-CAM 시각화 기법을 web application으로 통합한 의료영상 판독 보조 프로토타입.

- Multi-label classification과 Grad-CAM을 결합한 AI architecture 설계
- Data preparation, model training, inference, service integration을 잇는 end-to-end R&D pipeline 구축

### 02 · [CheXpert Research PoC](https://github.com/Laplace-tech/CheXpert) &nbsp;<sub><img src="https://img.shields.io/badge/1st%20Author-475569?style=flat-square" alt="1st Author" /></sub>

스탠퍼드 머신러닝 그룹이 공개한 CheXpert 데이터셋을 활용해 의료영상 분류 모델의 학습·평가 파이프라인을 검증한 research PoC.

- Uncertainty label policy를 포함한 data preparation과 model training workflow 설계
- Class-wise evaluation, threshold tuning, error analysis, Grad-CAM 기반 inference flow 구현
- 2026 한국정보기술학회 하계종합학술대회 대학생 논문경진대회 우수논문상 은상

### 03 · [Maverick](https://github.com/Laplace-tech/maverick) &nbsp;<sub><img src="https://img.shields.io/badge/2026%20%ED%95%98%EA%B3%84%EB%B0%A9%ED%95%99%20%EA%B0%9C%EC%9D%B8%20%EA%B3%B5%EB%B6%80-1E3A5F?style=flat-square" alt="2026 하계방학 개인 공부" /></sub>

[Dive into Deep Learning](https://d2l.ai/)의 수식과 algorithm을 PyTorch로 재구성한 학습 repository.

- Linear Regression과 Classification부터 CNN, RNN, Attention, Transformer까지 modern deep learning의 핵심 model을 scratch부터 구현
- Low-level algorithm과 PyTorch abstraction을 비교하며 tensor shape, data flow, training behavior 검증

## Technical Range

| Area | Tools |
|---|---|
| AI & Experimentation | `Python` · `PyTorch` · `NumPy` · `pandas` · `scikit-learn` · `Jupyter` |
| Backend & Data | `FastAPI` · `Java` · `Spring Boot` · `PostgreSQL` |
| Infrastructure & Development | `Docker` · `Linux` · `Git` · `GitHub` · `VS Code` |

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:F472B6,25:DB2777,50:6D28D9,75:1E1B4B,100:0B0614&height=160&section=footer"
    width="100%"
    alt="Footer"
  />
</p>
