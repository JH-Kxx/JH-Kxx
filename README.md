<div align="center">

<sub>GENERATIVE AI &nbsp; / &nbsp; VISION–LANGUAGE &nbsp; / &nbsp; APPLIED COMPUTER VISION</sub>

# JUNHYEOK KANG
### 강준혁 · AI Research & Engineering

**시각 정보를 이해하고, 생성하고, 검증하는 AI를 연구합니다.**

Undergraduate Researcher · Department of Medical Artificial Intelligence  
Konyang University, South Korea

<a href="mailto:jh55603364@gmail.com"><img src="https://img.shields.io/badge/EMAIL-Contact_Me-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/JH-Kxx?tab=repositories"><img src="https://img.shields.io/badge/GITHUB-Explore_Projects-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" /></a>

<br /><br />

**3 Conference Papers** &nbsp; · &nbsp; **2 Outstanding Presentation Awards** &nbsp; · &nbsp; **6 AI Projects**

<sub>프로필에 정리된 논문·수상·프로젝트 기준</sub>

</div>

---

## 01 / Research Focus

모델의 결과를 만드는 것에서 나아가, **왜 개선되는지 실험으로 비교하고 실제 시스템으로 연결하는 과정**에 관심이 있습니다.

| GENERATION | UNDERSTANDING | APPLICATION |
| :--- | :--- | :--- |
| **이미지 생성과 모델 효율화** | **멀티모달 이해와 결과 검증** | **의료 AI와 실시간 시스템** |
| GAN 기반 이미지 변환, 잠재공간 조작, 생성기 경량화 | 이미지–텍스트 특성 결합, 객체·색상·수량 단위 환각 탐지 | 자세 추정, GCN 관절 보정, 압력센서 기반 모니터링 |

## 02 / Selected Projects

<table>
<tr>
<td width="50%" valign="top">

<h3>01 &nbsp; Lightweight CycleGAN</h3>
<p><strong>생성 품질과 처리 효율을 함께 비교한 색상화 연구</strong></p>
<p>Residual block 수, 채널 폭, depthwise convolution을 바꾸며 모델 크기·추론 속도·이미지 품질을 비교했습니다.</p>
<p><code>CycleGAN</code> <code>Model Compression</code> <code>Ablation Study</code></p>
<p><strong>9 → 4 blocks</strong><br />
Parameters: 11.37M → 5.48M<br />
FPS: 169.78 → 272.90<br />
SSIM: 0.816 → 0.852</p>
<p><a href="https://github.com/JH-Kxx/Lightweight-CycleGAN"><strong>Explore research →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>02 &nbsp; VLM Hallucination Detection</h3>
<p><strong>생성된 문장을 이미지의 근거와 대조하는 검증 파이프라인</strong></p>
<p>BLIP2 캡션을 객체·색상·수량 단위로 분해하고, GroundingDINO와 속성 검증을 통해 토큰별 판정 결과를 시각화했습니다.</p>
<p><code>BLIP2</code> <code>CLIP</code> <code>GroundingDINO</code> <code>spaCy</code></p>
<p><strong>Object · Color · Quantity</strong><br />
Caption → Grounding → Verification<br />
Match / Uncertain / Hallucination</p>
<p><a href="https://github.com/JH-Kxx/vlm-hallucination-detection"><strong>Explore pipeline →</strong></a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>03 &nbsp; Skin Lesion Generation</h3>
<p><strong>잠재공간 조작을 통한 피부 병변 외형 변화 시뮬레이션</strong></p>
<p>StyleGAN2-ADA로 병변 이미지를 생성하고, e4e 기반 인버전과 SeFa 의미 방향을 연결해 이미지의 변화를 탐색했습니다.</p>
<p><code>StyleGAN2-ADA</code> <code>e4e</code> <code>SeFa</code></p>
<p><strong>Generation → Inversion → Manipulation</strong><br />
HAM10000 · 512 × 512<br />
Reported FID: 31.96</p>
<p><a href="https://github.com/JH-Kxx/skincancer-GAN-Simulation"><strong>Explore study →</strong></a></p>

</td>
<td width="50%" valign="top">

<h3>04 &nbsp; Pose & Pressure Monitoring</h3>
<p><strong>자세 추정과 압력센서를 연결한 실시간 모니터링 시스템</strong></p>
<p>YOLO 기반 자세 추정, GCN 관절 보정, 센서 압력 히트맵을 결합해 욕창 예방을 위한 모니터링 시스템을 구현했습니다.</p>
<p><code>YOLO Pose</code> <code>GCN</code> <code>Arduino</code></p>
<p><strong>Vision + Sensor + Dashboard</strong><br />
Pose estimation & keypoint refinement<br />
Pressure heatmap visualization</p>
<p><a href="https://github.com/JH-Kxx/Ulcer-Prevention-AI-System"><strong>Explore system →</strong></a></p>

</td>
</tr>
</table>

<sub>수치는 각 저장소에 보고된 실험 결과입니다. 피부 병변 프로젝트는 외형 변화 생성 연구이며, 임상적 진행 예측을 검증한 결과를 의미하지 않습니다.</sub>

### More Work

| Project | Approach | Reported Result |
| :--- | :--- | :--- |
| [**Multimodal Emotion Recognition**](https://github.com/JH-Kxx/Multimodal_Emotion_Classification) | DenseNet121 이미지 특성과 BLIP2·CLIP 텍스트 특성의 Attention 기반 결합 | Accuracy **76.97% → 82.26%** |
| [**Citrus Fruit Yield Prediction**](https://github.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML) | 상관관계 기반 파생변수 설계 및 AutoML | NMAE **0.1016 → 0.0714** |

## 03 / Publications & Recognition

**2025 · KAICTS Autumn Conference**  
**StyleGAN2 기반 피부암 병변의 시계열적 진행 시뮬레이션에 관한 연구**  
제1저자 &nbsp; · &nbsp; **우수발표논문상**  
[Project & Results ↗](https://github.com/JH-Kxx/skincancer-GAN-Simulation)

**2025 · KAICTS Autumn Conference**  
**CycleGAN 기반 색상화 성능 유지와 처리 속도 향상**  
공동 제1저자 &nbsp; · &nbsp; **우수발표논문상**  
[Project & Results ↗](https://github.com/JH-Kxx/Lightweight-CycleGAN)

**2025 · KCSE**  
**상관관계 기반 파생변수 생성과 AutoML을 활용한 감귤 착과량 예측**  
제2저자  
[Paper & Results ↗](https://github.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML)

## 04 / Technical Toolkit

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/Flask-111827?style=flat-square&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white" alt="Arduino" />
<img src="https://img.shields.io/badge/Java-437291?style=flat-square" alt="Java" />
</p>

| Area | Project Experience |
| :--- | :--- |
| **Generative Models** | StyleGAN2-ADA · CycleGAN · e4e Inversion · SeFa |
| **Vision & Language** | BLIP2 · CLIP · GroundingDINO · Attention-based Feature Fusion |
| **Applied Vision** | YOLO Pose · Graph Convolutional Networks · OpenCV |
| **Experiment & Evaluation** | Architecture Ablation · FID · PSNR / SSIM / LPIPS · Params / FLOPs / FPS |
| **System Integration** | Flask · Arduino · Pressure Sensing · Monitoring Dashboard |

<details>
<summary><strong>Certifications</strong></summary>
<br />

- Microsoft Azure AI Fundamentals · **AI-900**
- 데이터분석 준전문가 · **ADsP**
- NAVER Cloud Platform · **Certified Associate**

</details>

---

<div align="center">

<strong>Junhyeok Kang</strong><br />
Generative AI · Vision-Language Models · Applied Computer Vision<br /><br />
<a href="mailto:jh55603364@gmail.com">jh55603364@gmail.com</a> &nbsp; / &nbsp; <a href="https://github.com/JH-Kxx">github.com/JH-Kxx</a>

</div>
