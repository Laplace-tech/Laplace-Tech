<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:07111F,20:102A43,42:155E75,65:38BDF8,84:93C5FD,100:E0F2FE&height=280&section=header&text=LAPLACE%20TECH&fontSize=62&fontColor=F8FAFC&fontAlignY=37&animation=fadeIn&desc=Medical%20Imaging%20AI%20%C2%B7%20Deep%20Learning%20%C2%B7%20Research%20Engineering&descSize=17&descAlignY=58"
    width="100%"
    alt="Laplace Tech header"
  />
</p>

<div align="center">

### Undergraduate AI Researcher

From mathematical foundations to reproducible experiments and working systems.

[![MediScope](https://img.shields.io/badge/Featured-MediScope-155E75?style=for-the-badge)](https://github.com/Laplace-tech/capstone-cxr)
[![CheXpert](https://img.shields.io/badge/Research-CheXpert-38BDF8?style=for-the-badge)](https://github.com/Laplace-tech/CheXpert)
[![Maverick](https://img.shields.io/badge/Learning-Maverick-7B2CBF?style=for-the-badge)](https://github.com/Laplace-tech/maverick)

</div>

## Profile

- Medical Image Analysis와 Deep Learning 중심의 학부 연구
- Dataset policy, model training, evaluation, explainability, deployment를 잇는 end-to-end pipeline 설계
- 수식과 algorithm을 직접 구현하고 Tensor shape와 training behavior까지 검증하는 학습 방식

## Research interests

| Area | Focus |
|---|---|
| Medical Image Analysis | Chest X-ray multi-label classification |
| Explainable AI | Grad-CAM 기반 prediction evidence visualization |
| Model Evaluation | AUROC, AUPRC, class-wise threshold tuning, error analysis |
| Representation Learning | CNN, RNN, Attention, Transformer architecture |
| Research Engineering | Reproducible experiment pipeline과 service integration |

## Featured work

### [MediScope · Chest X-ray Reading Assist System](https://github.com/Laplace-tech/capstone-cxr)

DenseNet121 multi-label classification과 Grad-CAM을 결합한 Chest X-ray 판독 보조 prototype.

- Project direction, AI architecture, core inference pipeline
- React/Vite, Spring Boot, FastAPI, PostgreSQL, Docker Compose 기반 service integration
- 2026 한국정보기술학회 하계종합학술대회 대학생 논문경진대회 우수논문상 은상

### [CheXpert · Research and Model PoC](https://github.com/Laplace-tech/CheXpert)

CheXpert-small 기반의 재현 가능한 medical imaging experiment pipeline.

- DenseNet121를 이용한 5개 finding의 multi-label classification
- U-Ignore, U-Ones, U-Zeros uncertainty policy 비교
- BCEWithLogitsLoss와 `pos_weight`, AUROC/AUPRC evaluation, F1 threshold tuning
- Representative U-Ignore model: test mean AUROC **0.8927**, mean AUPRC **0.6494**
- Image-level inference, Grad-CAM visualization, error analysis

### [Maverick · Deep Learning from Scratch](https://github.com/Laplace-tech/maverick)

[Dive into Deep Learning](https://d2l.ai/)의 수식과 algorithm을 PyTorch로 재구성한 학습 기록.

- **159 notebooks**, Chapters 1–11 complete
- Linear models부터 CNN, RNN, Attention, Transformer, Vision Transformer까지 구현
- From-scratch와 framework implementation 비교
- Tensor shape, device, training result를 notebook output으로 검증

## Research pipeline

```text
Dataset policy
    ↓
Preprocessing and label handling
    ↓
Model training and experiment tracking
    ↓
AUROC / AUPRC evaluation
    ↓
Class-wise threshold tuning and error analysis
    ↓
Grad-CAM validation
    ↓
Inference API and service integration
```

## Technical range

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=20232A)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## Academic output

**2026 한국정보기술학회 하계종합학술대회 · 대학생 논문경진대회 우수논문상 은상**

> 딥러닝 기반 흉부 X-ray 판독 보조 시스템: Grad-CAM을 활용한 설명가능한 의료영상 AI

<br />

<p align="center">
  <img
    src="./assets/maverick-wide.png"
    width="100%"
    alt="Maverick night landscape"
  />
</p>

<div align="center">

**Independent thinking. Reproducible work. Evidence before claims.**

</div>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:E0F2FE,22:93C5FD,48:38BDF8,72:155E75,100:07111F&height=150&section=footer"
    width="100%"
    alt="Footer"
  />
</p>
