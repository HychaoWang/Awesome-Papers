# Awesome-Papers

A curated collection of research papers on video understanding, diffusion models, motion generation, and efficient visual computing.

---

## � Diffusion Models

### 📖 Foundational Works (扩散模型基础)

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| Deep Unsupervised Learning using Nonequilibrium Thermodynamics | ICML 2015 | Jascha Sohl-Dickstein, Eric A. Weiss, Niru Maheswaranathan, Surya Ganguli | [arXiv](https://arxiv.org/abs/1503.03585) |
| Generative Modeling by Estimating Gradients of the Data Distribution | NeurIPS 2019 | Yang Song, Stefano Ermon | [arXiv](https://arxiv.org/abs/1907.05600) |
| Denoising Diffusion Probabilistic Models (DDPM) | NeurIPS 2020 | Jonathan Ho, Ajay Jain, Pieter Abbeel | [arXiv](https://arxiv.org/abs/2006.11239) |
| Denoising Diffusion Implicit Models (DDIM) | ICLR 2021 | Jiaming Song, Chenlin Meng, Stefano Ermon | [arXiv](https://arxiv.org/abs/2010.02502) |
| Score-Based Generative Modeling through Stochastic Differential Equations | ICLR 2021 | Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole | [arXiv](https://arxiv.org/abs/2011.13456) |

### ⚡ Quality & Guidance (质量提升与引导)

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| Improved Denoising Diffusion Probabilistic Models | ICML 2021 | Alex Nichol, Prafulla Dhariwal | [arXiv](https://arxiv.org/abs/2102.09672) |
| Diffusion Models Beat GANs on Image Synthesis | NeurIPS 2021 | Prafulla Dhariwal, Alex Nichol | [arXiv](https://arxiv.org/abs/2105.05233) |
| Classifier-Free Diffusion Guidance | NeurIPS 2021 Workshop | Jonathan Ho, Tim Salimans | [arXiv](https://arxiv.org/abs/2207.12598) |

### 🚀 Fast Sampling & Design Space (加速采样与设计空间)

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps | NeurIPS 2022 | Cheng Lu, Yuhao Zhou, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu | [arXiv](https://arxiv.org/abs/2206.00927) |
| Elucidating the Design Space of Diffusion-Based Generative Models (EDM) | NeurIPS 2022 | Tero Karras, Miika Aittala, Timo Aila, Samuli Laine | [arXiv](https://arxiv.org/abs/2206.00364) |
| High-Resolution Image Synthesis with Latent Diffusion Models (LDM) | CVPR 2022 | Robin Rombach, Andreas Blattmann, Dominik Lorenz, Patrick Esser, Björn Ommer | [arXiv](https://arxiv.org/abs/2112.10752) |

### 📚 Surveys (综述)

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| Diffusion Models: A Comprehensive Survey of Methods and Applications | ACM Computing Surveys 2023 | Ling Yang, Zhilong Zhang, Yang Song, Shenda Hong, Runsheng Xu, Yue Zhao, Wentao Zhang, Bin Cui, Ming-Hsuan Yang | [arXiv](https://arxiv.org/abs/2209.00796) |
| On the Design Fundamentals of Diffusion Models: A Survey | arXiv 2024 | Ziyi Chang, George A. Koulieris, Hubert P. H. Shum | [arXiv](https://arxiv.org/abs/2306.04542) |

### 🔬 Recent Advances (最新进展)

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| Contrastive Conditional-Unconditional Alignment for Long-tailed Diffusion Model | arXiv 2025 | Fang Chen, Alex Villa, Gongbo Liang, Xiaoyi Lu, Meng Tang | [arXiv](https://arxiv.org/abs/2507.09052) |
| A Unified Framework for Diffusion Bridge Problems: Flow Matching and Schrödinger Matching into One | arXiv 2025 | Minyoung Kim | [arXiv](https://arxiv.org/abs/2503.21756) |
| CFG++: Manifold-constrained Classifier Free Guidance for Diffusion Models | NeurIPS 2024 | Hyungjin Chung, Jeongsol Kim, Geon Yeong Park, Hyelin Nam, Jong Chul Ye | [arXiv](https://arxiv.org/abs/2406.08070) |
| Training Class-Imbalanced Diffusion Model Via Overlap Optimization | ICLR 2024 | Divin Yan, Lu Qi, Vincent Tao Hu, Ming-Hsuan Yang, Meng Tang | [arXiv](https://arxiv.org/abs/2402.10821) |

---

## 🎭 Motion & Dance Generation

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| MotionLCM: Real-time Controllable Motion Generation via Latent Consistency Model | ECCV 2024 | Wenxun Dai, Ling-Hao Chen, Jingbo Wang, Jinpeng Liu, Bo Dai, Yansong Tang | [arXiv](https://arxiv.org/abs/2404.19759) |
| EDGE: Editable Dance Generation From Music | CVPR 2023 | Jonathan Tseng, Rodrigo Castellon, C. Karen Liu | [arXiv](https://arxiv.org/abs/2211.10658) |
| Bailando: 3D Dance Generation by Actor-Critic GPT with Choreographic Memory | CVPR 2022 | Li Siyao, Weijiang Yu, Tianpei Gu, Chunze Lin, Quan Wang, Chen Qian, Chen Change Loy, Ziwei Liu | [arXiv](https://arxiv.org/abs/2203.13055) |

---

## 🎬 Efficient Video Understanding

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| MaskVD: Region Masking for Efficient Video Object Detection | arXiv 2024 | Sreetama Sarkar, Gourav Datta, Souvik Kundu, Kai Zheng, Chirayata Bhattacharyya, Peter A. Beerel | [arXiv](https://arxiv.org/abs/2407.12067) |
| Eventful Transformers: Leveraging Temporal Redundancy in Vision Transformers | ICCV 2023 | Matthew Dutson, Yin Li, Mohit Gupta | [arXiv](https://arxiv.org/abs/2308.13494) |
| SparseViT: Revisiting Activation Sparsity for Efficient High-Resolution Vision Transformer | CVPR 2023 | Xuanyao Chen, Zhijian Liu, Haotian Tang, Li Yi, Hang Zhao, Song Han | [arXiv](https://arxiv.org/abs/2303.17605) |
| ByteTrack: Multi-Object Tracking by Associating Every Detection Box | ECCV 2022 | Yifu Zhang, Peize Sun, Yi Jiang, Dongdong Yu, Fucheng Weng, Zehuan Yuan, Ping Luo, Wenyu Liu, Xinggang Wang | [arXiv](https://arxiv.org/abs/2110.06864) |
| BlockCopy: High-Resolution Video Processing with Block-Sparse Feature Propagation and Online Policies | ICCV 2021 | Thomas Verelst, Tinne Tuytelaars | [arXiv](https://arxiv.org/abs/2108.09376) |
| Deep Feature Flow for Video Recognition | CVPR 2017 | Xizhou Zhu, Yuwen Xiong, Jifeng Dai, Lu Yuan, Yichen Wei | [arXiv](https://arxiv.org/abs/1611.07715) |

---

## 🖼️ Image Processing

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| Invertible Image Signal Processing | CVPR 2021 | Yazhou Xing, Zian Qian, Qifeng Chen | [arXiv](https://arxiv.org/abs/2103.15061) |

---

## ⚡ Hardware & Accelerator Modeling

| Title | Venue | Authors | Link |
|-------|-------|---------|------|
| CiMLoop: A Flexible, Accurate, and Fast Compute-In-Memory Modeling Tool | ISPASS 2024 | Tanner Andrulis, Joel S. Emer, Vivienne Sze | [arXiv](https://arxiv.org/abs/2405.07259) |
| Sparseloop: An Analytical Approach To Sparse Tensor Accelerator Modeling | MICRO 2022 | Yannan Nellie Wu, Po-An Tsai, Angshuman Parashar, Vivienne Sze, Joel S. Emer | [arXiv](https://arxiv.org/abs/2205.05826) |
