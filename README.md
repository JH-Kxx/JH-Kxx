<p align="center">
<img src="./assets/profile-banner.svg" width="100%" alt="Junhyeok Kang — Audio, Vision and Generative AI" />
</p>

<div align="center">

### AI Research & Engineering
**Undergraduate Researcher · Department of Medical Artificial Intelligence**  
**Konyang University · South Korea**

I study how AI models **represent, generate, and connect information across modalities**—  
from visual generation and language grounding to audio representation learning.

<p>
<img src="https://img.shields.io/badge/Audio%20Representation-0891B2?style=for-the-badge" alt="Audio Representation" />
<img src="https://img.shields.io/badge/Multimodal%20Learning-7C3AED?style=for-the-badge" alt="Multimodal Learning" />
<img src="https://img.shields.io/badge/Generative%20AI-DB2777?style=for-the-badge" alt="Generative AI" />
<img src="https://img.shields.io/badge/Medical%20AI-2563EB?style=for-the-badge" alt="Medical AI" />
</p>

<a href="mailto:jh55603364@gmail.com"><img src="https://img.shields.io/badge/Email%20Me-EA580C?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Me" /></a>
<a href="https://github.com/JH-Kxx?tab=repositories"><img src="https://img.shields.io/badge/Explore%20Repositories-4F46E5?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repositories" /></a>

<br /><br />

| 📄 Conference Papers | 🏆 Presentation Awards | 🛠 Featured Projects | 🎧 Current Research |
| :---: | :---: | :---: | :---: |
| **3** | **2** | **6** | **Audio Representation** |

<sub>Publications, awards, and projects listed in this profile.</sub>

</div>

---

## 🧭 Research Identity

My work brings together **generative modeling, multimodal understanding, and applied AI systems**. I am interested in both what a model can produce and how its behavior can be examined through controlled comparisons, representation analysis, and practical implementations.

- **Represent:** investigate audio–text and cross-modal alignment.
- **Generate:** synthesize images and explore meaningful transformations in latent space.
- **Verify:** compare generated language with visual evidence.
- **Optimize:** examine the trade-off between model complexity, throughput, and output quality.
- **Integrate:** connect learned models with cameras, sensors, and user-facing applications.

## 🎧 Current Research · Audio Representation Learning

<p>
<img src="https://img.shields.io/badge/Status%3A%20Ongoing%20Research-0891B2?style=for-the-badge" alt="Status: Ongoing Research" />
<img src="https://img.shields.io/badge/Audio%E2%80%93Text%20Alignment-2563EB?style=for-the-badge" alt="Audio–Text Alignment" />
<img src="https://img.shields.io/badge/Cross%E2%80%93Modal%20Retrieval-7C3AED?style=for-the-badge" alt="Cross–Modal Retrieval" />
<img src="https://img.shields.io/badge/Bioacoustics-059669?style=for-the-badge" alt="Bioacoustics" />
</p>

### Learning useful representations from sound

I am currently working on **audio representation learning and multimodal alignment**, with a particular focus on animal sounds and their relationship to text and visual information.

The central question is how to learn audio embeddings that preserve useful semantic information while remaining robust to background noise, non-vocal segments, and variation within a species.

| Research Component | Focus |
| :--- | :--- |
| **Audio–text representation** | Study audio and text embeddings using CLAP / AnimalCLAP baselines and species-related text prompts. |
| **Cross-modal analysis** | Compare image–text, audio–text, and audio–image alignment, including species-level centroid analysis. |
| **Evaluation & transfer** | Examine retrieval performance and generalization using AnimalCLAP and BioVITA data, including unseen-species settings. |
| **Representation diagnostics** | Analyze positive/negative cosine similarity, retrieval ranks, and t-SNE / UMAP projections. |
| **Modeling directions under investigation** | Explore temporal attention pooling, taxonomy-aware contrastive learning, hard-negative sampling, and centroid-based regularization. |

**Evaluation toolkit:** Top-1 / Top-5 retrieval · Recall@K · Mean / Median Rank · Cosine similarity · t-SNE · UMAP

**Research ecosystem:** AnimalCLAP · CLAP · BioVITA · BioCLIP · PyTorch · Ubuntu · CUDA

<sub>Ongoing work: the modeling directions above describe research under exploration, rather than completed or independently validated improvements.</sub>

---

## 🚀 Featured Projects

Six projects across **image generation, vision–language verification, medical monitoring, model efficiency, emotion recognition, and applied machine learning**.

<table>
<tr>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/GENERATIVE%20AI%20%2F%20MEDICAL%20IMAGING-DB2777?style=for-the-badge" alt="GENERATIVE AI / MEDICAL IMAGING" /></p>
<h3>01 / Skin Cancer Image Generation</h3>
<a href="https://github.com/JH-Kxx/skincancer-GAN-Simulation"><img src="https://raw.githubusercontent.com/JH-Kxx/skincancer-GAN-Simulation/main/images/fig6-sefa-1.png" width="440" alt="SeFa semantic direction example 1: visual changes as alpha increases" /><br /><img src="https://raw.githubusercontent.com/JH-Kxx/skincancer-GAN-Simulation/main/images/fig7-sefa-2.png" width="440" alt="SeFa semantic direction example 2: visual changes as alpha increases" /></a>
<p><strong>From image synthesis to semantic latent manipulation.</strong></p>
<p>A skin lesion generation and visual change simulation study using StyleGAN2-ADA, a custom e4e encoder, and SeFa. Real images are projected into W+ space, then moved along semantic directions to explore changes in pigmentation, boundaries, and appearance.</p>
<ul><li>HAM10000: nevus and melanoma image subsets.</li><li>512 × 512 synthesis with StyleGAN2-ADA.</li><li>Custom e4e inversion with a frozen generator.</li><li>SeFa-based semantic direction exploration.</li></ul>
<p><strong>Reported FID:</strong> 106.47 → 31.96<br /><strong>Inversion L2:</strong> 0.0039 · <strong>Training:</strong> 920 kimg</p>
<p><code>StyleGAN2-ADA</code> <code>e4e</code> <code>SeFa</code> <code>LPIPS</code></p>
<p><sub>First-author conference paper · Outstanding Presentation Award</sub></p>
<p><a href="https://github.com/JH-Kxx/skincancer-GAN-Simulation"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-DB2777?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/VISION%E2%80%93LANGUAGE%20%2F%20VERIFICATION-7C3AED?style=for-the-badge" alt="VISION–LANGUAGE / VERIFICATION" /></p>
<h3>02 / VLM Hallucination Detection</h3>
<a href="https://github.com/JH-Kxx/vlm-hallucination-detection"><img src="https://raw.githubusercontent.com/JH-Kxx/vlm-hallucination-detection/main/figures/pipeline.png" width="440" alt="VLM Hallucination Detection project visual" /></a>
<p><strong>Checking generated language against visual evidence.</strong></p>
<p>A verification pipeline that decomposes generated captions into objects, colors, and quantities. It combines caption generation, phrase parsing, object grounding, and attribute checks to produce interpretable token-level highlights.</p>
<ul><li>BLIP2 generates candidate captions; CLIP selects a representative caption.</li><li>spaCy extracts objects and associated attributes.</li><li>GroundingDINO provides object boxes and confidence scores.</li><li>HSV and KMeans support color checks; box counts support quantity checks.</li></ul>
<p><strong>Verification:</strong> Object · Color · Quantity<br /><strong>Output:</strong> Match / Uncertain / Hallucination</p>
<p><code>BLIP2</code> <code>CLIP</code> <code>GroundingDINO</code> <code>spaCy</code> <code>OpenCV</code></p>
<p><sub>COCO 2017 validation images · Notebook implementation</sub></p>
<p><a href="https://github.com/JH-Kxx/vlm-hallucination-detection"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/MEDICAL%20AI%20%2F%20SENSOR%20INTEGRATION-0891B2?style=for-the-badge" alt="MEDICAL AI / SENSOR INTEGRATION" /></p>
<h3>03 / Pressure Ulcer Prevention System</h3>
<a href="https://github.com/JH-Kxx/Ulcer-Prevention-AI-System"><img src="https://raw.githubusercontent.com/JH-Kxx/Ulcer-Prevention-AI-System/main/docs/dashboard/system_demo.png" width="440" alt="Pressure Ulcer Prevention System project visual" /></a>
<p><strong>Connecting body pose, pressure sensing, and monitoring.</strong></p>
<p>A real-time monitoring prototype for pressure ulcer prevention research. The system combines camera-based pose estimation, graph-based keypoint refinement, pressure sensing, and an integrated dashboard.</p>
<ul><li>YOLO Pose estimates body keypoints from RGB frames.</li><li>GCN refines keypoints using body-joint relationships.</li><li>SLP data supports the pose refinement training pipeline.</li><li>Arduino pressure sensing feeds interpolated pressure heatmaps.</li></ul>
<p><strong>Reported PCKh@0.5:</strong> 0.628 → 0.819<br /><strong>Integration:</strong> Camera + Pressure Sensors + Dashboard</p>
<p><code>YOLO Pose</code> <code>GCN</code> <code>PyTorch</code> <code>Arduino</code> <code>OpenCV</code></p>
<p><sub>Training scripts · Inference pipeline · Checkpoints · Sensor firmware</sub></p>
<p><a href="https://github.com/JH-Kxx/Ulcer-Prevention-AI-System"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-0891B2?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/GENERATIVE%20AI%20%2F%20MODEL%20EFFICIENCY-2563EB?style=for-the-badge" alt="GENERATIVE AI / MODEL EFFICIENCY" /></p>
<h3>04 / Lightweight CycleGAN</h3>
<a href="https://github.com/JH-Kxx/Lightweight-CycleGAN"><img src="https://raw.githubusercontent.com/JH-Kxx/Lightweight-CycleGAN/main/assets/result-animal.png" width="440" alt="Lightweight CycleGAN project visual" /></a>
<p><strong>Exploring the balance between image quality and efficiency.</strong></p>
<p>An unpaired grayscale-to-color translation study that compares generator depth, channel width, and depthwise separable convolutions. Architecture variants are evaluated for image quality, model size, and inference throughput.</p>
<ul><li>Residual depth: 9, 6, and 4 blocks.</li><li>Channel width multipliers: ×0.75, ×0.5, and ×0.25.</li><li>Depthwise separable and combined variants.</li><li>PSNR, SSIM, LPIPS, parameter count, and FPS comparisons.</li></ul>
<p><strong>9 → 4 blocks:</strong> 11.37M → 5.48M parameters<br /><strong>FPS:</strong> 169.78 → 272.90 · <strong>SSIM:</strong> 0.816 → 0.852</p>
<p><code>CycleGAN</code> <code>PyTorch</code> <code>Model Compression</code> <code>Ablation Studies</code></p>
<p><sub>Co-first-author conference paper · Outstanding Presentation Award</sub></p>
<p><a href="https://github.com/JH-Kxx/Lightweight-CycleGAN"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/MULTIMODAL%20LEARNING%20%2F%20EMOTION-EA580C?style=for-the-badge" alt="MULTIMODAL LEARNING / EMOTION" /></p>
<h3>05 / Multimodal Emotion Recognition</h3>
<a href="https://github.com/JH-Kxx/Multimodal_Emotion_Classification"><img src="https://raw.githubusercontent.com/JH-Kxx/Multimodal_Emotion_Classification/main/images/flowchart.png" width="440" alt="Multimodal Emotion Recognition project visual" /></a>
<p><strong>Combining visual features with generated language.</strong></p>
<p>A facial emotion classification study combining CNN image features with text features derived from BLIP2 descriptions and CLIP embeddings. Attention-based classifiers are compared with a CNN-only baseline.</p>
<ul><li>VGG16, ResNet18, and DenseNet121 baseline comparison.</li><li>DenseNet121 image features + CLIP text embeddings.</li><li>Attention, self-attention, and cross-attention comparisons.</li><li>Flask demonstration with uploads, predictions, history, and a dashboard.</li></ul>
<p><strong>Reported accuracy:</strong> 76.97% → 82.26%<br /><strong>Absolute improvement:</strong> +5.29 percentage points</p>
<p><code>DenseNet121</code> <code>BLIP2</code> <code>CLIP</code> <code>Attention</code> <code>Flask</code></p>
<p><sub>RAF-DB · Class-wise analysis · Augmentation experiments</sub></p>
<p><a href="https://github.com/JH-Kxx/Multimodal_Emotion_Classification"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-EA580C?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
<td width="50%" valign="top">
<p><img src="https://img.shields.io/badge/APPLIED%20MACHINE%20LEARNING%20%2F%20AGRICULTURE-059669?style=for-the-badge" alt="APPLIED MACHINE LEARNING / AGRICULTURE" /></p>
<h3>06 / Citrus Fruit Yield Prediction</h3>
<a href="https://github.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML"><img src="https://raw.githubusercontent.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML/main/images/heatmap.png" width="440" alt="Citrus Fruit Yield Prediction project visual" /></a>
<p><strong>Turning growth measurements into predictive features.</strong></p>
<p>A yield prediction study using correlation-guided feature engineering and AutoML. Statistical and growth-related features are derived from shoot measurements and evaluated across feature combinations.</p>
<ul><li>Statistical features: mean, variance, differences, extrema, and median.</li><li>Growth features: instability, ratios, imbalance, and log stability.</li><li>MLJAR-Supervised with Random Forest, Extra Trees, and CatBoost.</li><li>Feature-combination experiments evaluated using NMAE.</li></ul>
<p><strong>Reported NMAE:</strong> 0.1016 → 0.0714<br /><strong>Relative reduction:</strong> approximately 29.7%</p>
<p><code>Feature Engineering</code> <code>MLJAR AutoML</code> <code>CatBoost</code></p>
<p><sub>Second-author conference paper · KCSE 2025</sub></p>
<p><a href="https://github.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML"><img src="https://img.shields.io/badge/Explore%20Project%20%E2%86%92-059669?style=for-the-badge&logo=github&logoColor=white" alt="Explore Project →" /></a></p>
</td>
</tr>
</table>

<sub>Numerical results are reported in the linked project repositories and depend on their evaluation settings. Skin lesion generation explores visual changes; it does not establish clinically validated disease progression prediction. The pressure ulcer project is a monitoring research prototype.</sub>

## 📊 Experimental Highlights

| Project | Comparison / Measure | Reported Result |
| :--- | :--- | :--- |
| **Skin Lesion Generation** | StyleGAN2-ADA FID during training ↓ | **106.47 → 31.96** |
| **Lightweight CycleGAN** | Generator parameters: 9 vs. 4 residual blocks ↓ | **11.37M → 5.48M** |
| **Lightweight CycleGAN** | Inference throughput: 9 vs. 4 blocks ↑ | **169.78 → 272.90 FPS** |
| **Lightweight CycleGAN** | PSNR / SSIM / LPIPS: 4-block model | **21.111 / 0.852 / 0.235** |
| **Multimodal Emotion Recognition** | CNN-only vs. CNN + VLM accuracy ↑ | **76.97% → 82.26%** |
| **Pose Refinement** | YOLO Pose vs. YOLO Pose + GCN PCKh@0.5 ↑ | **0.628 → 0.819** |
| **Citrus Yield Prediction** | Baseline vs. engineered-feature NMAE ↓ | **0.1016 → 0.0714** |
| **VLM Hallucination Detection** | Demonstrated verification coverage | **Object · Color · Quantity** |

<sub>Each row belongs to its own experiment; metrics should not be compared across different projects. Qualitative verification coverage is distinguished from quantitative performance.</sub>

---

## 📚 Publications & Awards

### 🥇 Skin Lesion Generation · First Author

**A Study on Time-Series Progression Simulation of Skin Cancer Lesions Based on StyleGAN2**

- **Venue:** KAICTS 2025 Autumn Conference
- **Authorship:** First author
- **Recognition:** Outstanding Presentation Award
- **Research:** StyleGAN2-ADA synthesis, e4e inversion, and SeFa-based latent manipulation
- **Resources:** [Project overview and experimental results ↗](https://github.com/JH-Kxx/skincancer-GAN-Simulation)

### 🥇 Efficient Image Translation · Co-First Author

**Performance Preservation and Processing Speed Improvement of CycleGAN-Based Colorization**

- **Venue:** KAICTS 2025 Autumn Conference
- **Authorship:** Co-first author / equal contribution
- **Recognition:** Outstanding Presentation Award
- **Research:** Generator architecture comparisons for efficient grayscale-to-color translation
- **Resources:** [Study, architecture variants, and results ↗](https://github.com/JH-Kxx/Lightweight-CycleGAN)

### 🌱 Agricultural Machine Learning · Second Author

**Citrus Fruit Yield Prediction Using Correlation-Based Feature Engineering and AutoML**

- **Venue:** KCSE 2025
- **Authorship:** Second author
- **Research:** Growth-related feature engineering and automated model selection
- **Resources:** [Paper and project overview ↗](https://github.com/JH-Kxx/Citrus-Fruit-Yield-Prediction_AutoML)

<sub>Paper titles are presented in English for this profile; consult the linked project materials for original publication details.</sub>

---

## 🧰 Technical Stack

### Languages & Core Frameworks

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Java-E76F00?style=for-the-badge" alt="Java" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
</p>

### Generative AI & Multimodal Models

<p>
<img src="https://img.shields.io/badge/StyleGAN2%E2%80%93ADA-DB2777?style=for-the-badge" alt="StyleGAN2–ADA" />
<img src="https://img.shields.io/badge/CycleGAN-9333EA?style=for-the-badge" alt="CycleGAN" />
<img src="https://img.shields.io/badge/BLIP2-7C3AED?style=for-the-badge" alt="BLIP2" />
<img src="https://img.shields.io/badge/CLIP-2563EB?style=for-the-badge" alt="CLIP" />
<img src="https://img.shields.io/badge/GroundingDINO-0284C7?style=for-the-badge" alt="GroundingDINO" />
<img src="https://img.shields.io/badge/CLAP%20%2F%20AnimalCLAP-0891B2?style=for-the-badge" alt="CLAP / AnimalCLAP" />
<img src="https://img.shields.io/badge/YOLO%20Pose-059669?style=for-the-badge" alt="YOLO Pose" />
<img src="https://img.shields.io/badge/GCN-0D9488?style=for-the-badge" alt="GCN" />
</p>

### Development Environment & Systems

<p>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
<img src="https://img.shields.io/badge/Linux-334155?style=for-the-badge&logo=linux&logoColor=white" alt="Linux" />
<img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
<img src="https://img.shields.io/badge/Windows-0078D4?style=for-the-badge" alt="Windows" />
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/GitHub-4F46E5?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
<img src="https://img.shields.io/badge/Flask-0F766E?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" />
<img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino" />
</p>

<sub>Tools and methods reflect project experience and current research usage.</sub>

## 🎓 Education & Certifications

**Konyang University**  
Department of Medical Artificial Intelligence · Undergraduate Researcher

| Certification | Organization |
| :--- | :--- |
| **Azure AI Fundamentals · AI-900** | Microsoft |
| **Advanced Data Analytics Semi-Professional · ADsP** | Korea Data Agency |
| **NAVER Cloud Platform Certified Associate** | NAVER Cloud |

---

<div align="center">

### Connecting Audio, Vision, and Language

**Research interests:** Audio Representation Learning · Multimodal Alignment · Generative AI · Medical AI

<a href="mailto:jh55603364@gmail.com"><img src="https://img.shields.io/badge/jh55603364%40gmail.com-DB2777?style=for-the-badge&logo=gmail&logoColor=white" alt="jh55603364@gmail.com" /></a>
<a href="https://github.com/JH-Kxx"><img src="https://img.shields.io/badge/JH%E2%80%93Kxx-7C3AED?style=for-the-badge&logo=github&logoColor=white" alt="JH–Kxx" /></a>

<br /><br />

<sub>Junhyeok Kang · Konyang University · South Korea</sub>

</div>
