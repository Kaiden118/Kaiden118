<h1 align="center">Hi, I'm Arthur Lu 👋</h1>

<p align="center">
  M.S. Computer Science @ USC &nbsp;|&nbsp; Machine Learning &nbsp;·&nbsp; Software Engineering &nbsp;·&nbsp; Medical Imaging &nbsp;·&nbsp; Generative AI
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/zechuan-lu-6923a1371">
    <img src="https://img.shields.io/badge/LinkedIn-Arthur%20Lu-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:zechuanlu7@gmail.com">
    <img src="https://img.shields.io/badge/Email-zechuanlu7%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

## About

I am a Computer Science master's student at the **University of Southern California**, building software for machine learning and medical imaging. My work includes evidence-grounded LLM agents for training diagnostics, diffusion models for MRI translation, and computer vision systems.

- Interested in reliable ML systems, generative AI, and healthcare applications
- Based in Los Angeles and open to **Summer 2027 Machine Learning / Software Engineering internships**

## Selected Projects

### [RunSleuth | Evidence-Grounded ML Training Diagnosis & Repair Verification](https://github.com/Kaiden118/RunSleuth-Evidence-Grounded-ML-Training-Failure-Diagnosis-and-Repair-Verification)

Built a **Gemini-powered agent with a custom Python tool-calling loop** to inspect PyTorch source code, experiment configurations, and training telemetry. It produces evidence-linked diagnoses, validates targeted repair proposals, and checks recovery through bounded training reruns, with support for excessive learning rates, missing optimizer steps, and healthy-run abstention.

Current work extends training telemetry and optimizer-parameter diagnostics to a **ResNet18 / Camelyon17-WILDS** medical-image classification baseline.

`Python` `PyTorch` `LLM Agents` `Tool Calling` `Pydantic` `ML Systems` `pytest`

### [CMCD | Cross-Modality Conditional Diffusion Model](https://github.com/Kaiden118/Cross-Modality-Conditional-Diffusion-Model)

Developed a PyTorch conditional diffusion model for bidirectional **T1/T2 MRI translation**, combining anatomy-consistent structural guidance, cross-attention, classifier-free guidance, and a composite MSE + L1 + SSIM objective. Achieved up to **0.90 SSIM**, **27.5 dB PSNR**, and **0.986 NCC**, with an open-source training and inference pipeline.

`Python` `PyTorch` `Diffusion Models` `Medical Imaging` `Computer Vision`

### [Multi-Camera 6-DoF Object Pose Tracking System](https://github.com/Kaiden118/MotionCaptureSystem)

Adapted OnePose++ into a multi-sensor pipeline for estimating an object's 3D position and rotation. Built data-collection and preprocessing tools, a Python backend, and Vue.js / JavaScript visualizations for real-time pose tracking.

`Python` `Computer Vision` `Pose Estimation` `Sensor Fusion` `Vue.js`

## Publications

- **CMCD: Conditional Diffusion Model for Medical Image Modality Translation** — First author; ICONIP 2026 (International Conference on Neural Information Processing). [Code](https://github.com/Kaiden118/Cross-Modality-Conditional-Diffusion-Model)
- S. Fan, **Z. Lu**, Z. Yan, and L. Hu. “[Interactions of three berberine mid-chain fatty acid salts with bovine serum albumin (BSA): Spectroscopic analysis and molecular docking](https://doi.org/10.1016/j.ijbiomac.2024.133370).” *International Journal of Biological Macromolecules*, 274(Pt 2), 133370, 2024.

## Technical Skills

**Languages:** Python, C++, C#, Java, JavaScript, SQL  
**Machine Learning & Vision:** PyTorch, TensorFlow, Diffusion Models, Transformers, OpenCV, OpenPose  
**LLM & ML Systems:** Gemini API, Tool Calling, Training Telemetry, Pydantic, pytest  
**Tools & Platforms:** Git, Linux, Weights & Biases, Unity, Vue.js, Raspberry Pi, Arduino
