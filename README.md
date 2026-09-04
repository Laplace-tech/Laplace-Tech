<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0614,25:1E1B4B,50:6D28D9,75:DB2777,100:F472B6&height=290&section=header&text=Min's%20Neural%20Cloud%20Hub&fontFamily=Cinzel&fontSize=50&fontColor=FFFFFF&fontAlignY=36&animation=twinkling&desc=An%20Archive%20of%20AI%20Research%20Projects%20and%20Experiments&descSize=19&descAlignY=59&stroke=F9A8D4&strokeWidth=1"
    width="100%"
    alt="My Neural Cloud Hub"
  />
</p>

## Profile

| | |
|---|---|
| Name | Yongmin Park (박용민) |
| Academic Affiliation | 경기대학교(수원) · 컴퓨터공학전공 (Entered in 2022) |
| Academic Status | 3rd-Year Undergraduate Student |
| Current Research | OLES3D · 3D Abdominal CT Segmentation · Adaptive Patch Sampling |
| Research Interests | Medical AI · Medical Imaging · AI for Healthcare |
| Email | [add28482848@kyonggi.ac.kr](mailto:add28482848@kyonggi.ac.kr) |

---

## About Me

Exploring diverse AI domains by studying the principles behind modern models
and designing reproducible research pipelines from experimentation to deployment.

---

## Research Interests

- Deep learning for medical AI
- Medical image analysis: classification, segmentation, and quantitative imaging
- Reliable AI for healthcare: generalization, interpretability, and reproducible validation

---

## Current Research

### [OLES3D](https://github.com/Laplace-tech/oles3d) &nbsp;<sub><img src="https://img.shields.io/badge/IN%20PROGRESS-7C3AED?style=flat-square" alt="In Progress" /></sub>

nnU-Net v2의 architecture와 training budget을 고정하고, 장기별 학습상태와 오류유형을 이용한 adaptive patch sampling을 검증하는 3D abdominal CT segmentation 연구.

- TotalSegmentator v2 공개 CT의 selected abdominal organs를 대상으로 한 reproducible evaluation protocol 설계
- Single 8 GB GPU에서 default, matched static sampler, OLES3D를 비교하고 accuracy–time–memory trade-off 분석

---

## Completed works

### 01 · [MediScope](https://github.com/Laplace-tech/capstone-cxr) &nbsp;<sub><img src="https://img.shields.io/badge/Team%20Leader-0F766E?style=flat-square" alt="Team Leader" /></sub>

CNN 기반 Chest X-ray classification model과 Grad-CAM 시각화 기법을 web application으로 통합한 의료영상 판독 보조 프로토타입.

- Multi-label classification과 Grad-CAM을 결합한 AI architecture 설계
- Data preparation, model training, inference, service integration을 잇는 end-to-end R&D pipeline 구축

<br />

### 02 · [CheXpert Research PoC](https://github.com/Laplace-tech/CheXpert) &nbsp;<sub><img src="https://img.shields.io/badge/1st%20Author-475569?style=flat-square" alt="1st Author" /></sub>

스탠퍼드 머신러닝 그룹이 공개한 CheXpert 데이터셋을 활용해 의료영상 분류 모델의 학습·평가 파이프라인을 검증한 research PoC.

- Uncertainty label policy를 포함한 data preparation과 model training workflow 설계
- Class-wise evaluation, threshold tuning, error analysis, Grad-CAM 기반 inference flow 구현
- 2026 한국정보기술학회 하계종합학술대회 대학생 논문경진대회 우수논문상 은상

<br />

### 03 · [Maverick](https://github.com/Laplace-tech/maverick) &nbsp;<sub><img src="https://img.shields.io/badge/2026%20%ED%95%98%EA%B3%84%EB%B0%A9%ED%95%99%20%EA%B0%9C%EC%9D%B8%20%EA%B3%B5%EB%B6%80-1E3A5F?style=flat-square" alt="2026 하계방학 개인 공부" /></sub>

[Dive into Deep Learning](https://d2l.ai/)의 수식과 algorithm을 PyTorch로 재구성한 학습 repository.

- Linear Regression과 Classification부터 CNN, RNN, Attention, Transformer까지 modern deep learning의 핵심 model을 scratch부터 구현
- Low-level algorithm과 PyTorch abstraction을 비교하며 tensor shape, data flow, training behavior 검증

---

## Technical Stack

### AI & Experimentation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### Backend & Data

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

### Infrastructure & Development

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:F472B6,25:DB2777,50:6D28D9,75:1E1B4B,100:0B0614&height=160&section=footer"
    width="100%"
    alt="Footer"
  />
</p>
