# Mamba-Papers-Hub [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![](resources/mamba.jpeg)

🔥 Mamba has proven its exceptional performance across diverse domains, often rivaling, and occasionally outperforming, state-of-the-art Transformer models. This repository presents a curated compilation of papers focusing on Mamba, complemented by accompanying code implementations. Additionally, it includes a variety of supplementary resources such as videos and blogs discussing about Mamba.


## Table of Content

- [Awesome-Mamba ](#awesome-mamba)
  - [Papers](#papers)
  - [Video Tutorials](#video-tutorials)
  - [Blogs](#blogs)
  - [Contributing](#contributing)

## Milestone Papers

|  Date  |       keywords       |    Institute    | Paper                                                                                                                                                                               | Code |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: |
| 2023-12 |     Mamba     |      Carnegie Mellon & Together AI     | [Mamba: Linear-Time Sequence Modeling with Selective State Spaces](https://arxiv.org/abs/2312.00752) |  [[Github]](https://github.com/state-spaces/mamba) |
| 2024-01 |     MambaByte     |      Cornell University     | [MambaByte: Token-free Selective State Space Model](https://arxiv.org/html/2401.13660v1) |  [[Github]]() |
| 2024-01 |     Vision Mamba     |      Huazhong University of Science and Technology, Horizon Robotics, Beijing Academy of Artificial Intelligence     | [Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model](https://arxiv.org/pdf/2401.09417v1.pdf) |  [[Github]](https://github.com/hustvl/vim) |
| 2024-01 |     SegMamba     |      The Hong Kong University of Science and Technology & Beijing Academy of Artificial Intelligence     | [SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation ](https://arxiv.org/pdf/2401.13560v2.pdf) |  [[Github]](https://github.com/ge-xing/segmamba) |
| 2024-01 |       MoE-Mamba       |      University of Warsaw      | [MoE-Mamba: Efficient Selective State Space Models with Mixture of Experts](https://arxiv.org/abs/2401.04081)   |  [[Github]](https://github.com/llm-random/llm-random) |
| 2024-01 |         U-Mamba         |      Vector Institute for AI & University of Toronto      | [U-Mamba: Enhancing Long-range Dependency for Biomedical Image Segmentation](https://arxiv.org/abs/2401.04722) |   [[Github]](https://github.com/bowang-lab/U-Mamba) |
| 2024-01 |         Vivim         |      The Hong Kong University of Science and Technology      | [Vivim: a Video Vision Mamba for Video Object Segmentation ](https://arxiv.org/pdf/2401.14168v1.pdf) |   [[Github]](https://github.com/scott-yjyang/vivim) |
| 2024-01 |         VMamba         |      University of Chinese Academy of Sciences, HUAWEI Inc. & PengCheng Lab      | [VMamba: Visual State Space Model](https://arxiv.org/pdf/2401.10166.pdf) |   [[Github]](https://github.com/MzeroMiko/VMamba) |
 2024-01 |         MambaTab         |       University of Kentucky       | [MambaTab: A Simple Yet Effective Approach for Handling Tabular Data](https://arxiv.org/pdf/2401.08867.pdf) |   [[Github]]() |
| 2024-02 |         Graph-Mamba         |      University of Toronto      | [Graph-Mamba: Towards Long-Range Graph Sequence Modeling with Selective State Spaces ](https://browse.arxiv.org/pdf/2402.00789.pdf) |   [[Github]](https://github.com/bowang-lab/Graph-Mamba) |
| 2024-02 |         Swin-UMamba         |      Paul C. Lauterbur Research Center for Biomedical Imaging      | [Swin-UMamba: Mamba-based UNet with ImageNet-based pretraining](https://arxiv.org/pdf/2402.03302.pdf) |   [[Github]](https://github.com/jiarunliu/swin-umamba) |
| 2024-02 |         BlackMamba         |      Zyphra       | [BlackMamba: Mixture of Experts for State-Space Models](https://arxiv.org/pdf/2402.03302.pdf) |   [[Github]]() |
| 2024-02 |         MambaFormer          |      KRAFTON & Seoul National University       | [Can Mamba Learn How to Learn? A Comparative Study on In-Context Learning Tasks](https://arxiv.org/pdf/2402.04248.pdf) |   [[Github]]() |
| 2024-02 |         U-shaped Vision Mamba         |      Nanjing University       | [U-shaped Vision Mamba for Single Image Dehazing](https://arxiv.org/pdf/2402.04139.pdf) |   [[Github]](https://github.com/zzr-idam) |
| 2024-02 |         MambaMorph         |       Beihang University       | [MambaMorph: a Mamba-based Backbone with Contrastive Feature Learning for Deformable MR-CT Registration](https://arxiv.org/pdf/2401.13934.pdf) |   [[Github]]() |
| 2024-02 |         nnMamba         |       Shenzhen Research       | [nnMamba: 3D Biomedical Image Segmentation, Classification and Landmark Detection with StateSpace Model](https://arxiv.org/pdf/2402.03526.pdf) |   [[Github]](https://github.com/lhaof/nnMamba) |
| 2024-02 |         Graphs with State Space Models         |              | [Graph Mamba: Towards Learning on Graphs with State Space Models](https://arxiv.org/pdf/2402.08678.pdf) |   [[Github]]() |
| 2024-02 |         Vision Mamba UNet         |       Shanghai Jiao Tong University       | [VM-UNet: Vision Mamba UNet for Medical Image Segmentation](https://arxiv.org/pdf/2402.02491.pdf) |   [[Github]](https://github.com/JCruan519/VM-UNet) |
| 2024-02 |         P-Mamba         |       Institute of Intelligent Software       | [P-Mamba: Marrying Perona Malik Diffusion with Mamba for Efficient Pediatric Echocardiographic Left Ventricular Segmentation](https://arxiv.org/pdf/2402.08506.pdf) |   [[Github]]() |
| 2024-02 |         FD-Vision Mamba         |       Nanjing University of Science and Technology       | [FD-Vision Mamba for Endoscopic Exposure Correction](https://arxiv.org/pdf/2402.08506.pdf) |   [[Github]](https://github.com/zzr-idam/FDVM-Net) |
| 2024-02 |         Semi-Mamba-UNet         |        University of Oxford       | [Semi-Mamba-UNet: Pixel-Level Contrastive Cross-Supervised Visual Mamba-based UNet for Semi-Supervised Medical Image Segmentation](https://arxiv.org/pdf/2402.07245.pdf) |   [[Github]](https://github.com/ziyangwang007/Mamba-UNet) |
| 2024-02 |         Mamba-ND         |        University of California, Los Angeles       | [Mamba-ND: Selective State Space Modeling for Multi-Dimensional Data](https://arxiv.org/pdf/2402.05892.pdf) |   [[Github]]() |
| 2024-02 |         Mamba-Diffusion         |        Kunlun Inc.       | [Scalable Diffusion Models with State Space Backbone](https://arxiv.org/pdf/2402.05608.pdf) |   [[Github]]( https://github.com/feizc/DiS) |
| 2024-02 |         Hierarchical Mamba         |        Carnegie Mellon University & Meta       | [Hierarchical State Space Models for Continuous Sequence-to-Sequence Modeling](https://arxiv.org/abs/2402.10211) |   [[Github]](https://hiss-csp.github.io/) |
| 2024-02 |         Res-VMamba         |        National Taiwan University       | [Res-VMamba: Fine-Grained Food Category Visual Classification Using Selective State Space Models with Deep Residual Learning](https://arxiv.org/abs/2402.15761) |   [[Github]](https://github.com/ChiShengChen/ResVMamba) |
| 2024-02 |         PointMamba         |        Huazhong University of Science & Technology       | [PointMamba: A Simple State Space Model for Point Cloud Analysis](https://arxiv.org/abs/2402.10739) |   [[Github]](https://github.com/LMD0311/PointMamba) |
| 2024-02 |         MambaIR         |        Tsinghua University & Shenzhen University       | [MambaIR: A Simple Baseline for Image Restoration with State-Space Model](https://arxiv.org/pdf/2402.15648.pdf) |   [[Github]](https://github.com/csguoh/MambaIR) |
| 2024-02 |         Pan-Mamba         |        Chinese Academy of Sciences       | [Pan-Mamba: Effective Pan-Sharpening with State Space Model](https://arxiv.org/pdf/2402.12192.pdf) |   [[Github]](https://github.com/alexhe101/Pan-Mamba) |
| 2024-02 |         Weak-Mamba-UNet         |         University of Oxford       | [Weak-Mamba-UNet: Visual Mamba Makes CNN and ViT Work Better for Scribble-based Medical Image Segmentation](https://arxiv.org/pdf/2402.10887.pdf) |   [[Github]](https://github.com/ziyangwang007/Mamba-UNet) |
| 2024-02 |         DenseMamba         |         Huawei       | [DenseMamba: State Space Models with Dense Hidden Connection for Efficient Large Language Models](https://arxiv.org/pdf/2403.00818.pdf) |   [[Github]](https://github.com/WailordHe/DenseSSM) |
| 2024-03 |         Mamba4Rec         |         Texas A&M University       | [Mamba4Rec: Towards Efficient Sequential Recommendation with Selective State Space Models](https://arxiv.org/pdf/2403.03900.pdf) |   [[Github]](https://github.com/chengkai-liu/mamba4rec) |
| 2024-03 |         MiM-ISTD: Mamba-in-Mamba         |         Alibaba Group       | [MiM-ISTD: Mamba-in-Mamba for Efficient Infrared Small Target Detection](https://arxiv.org/pdf/2403.02148.pdf) |   [[Github]](https://github.com/txchen-USTC/MiM-ISTD) |
| 2024-03 |         Point Could Mamba         |         Wuhan University       | [Point Could Mamba: Point Cloud Learning via State Space Model](https://arxiv.org/pdf/2403.00762.pdf) |   [[Github]](https://github.com/zhang-tao-whu/PCM) |
| 2024-03 |         Hidden Attention of Mamba        |          Tel Aviv University       | [The Hidden Attention of Mamba Models](https://arxiv.org/pdf/2403.01590.pdf) |   [[Github]](https://github.com/AmeenAli/HiddenMambaAttn) |
| 2024-03 |         MED-MAMBA        |          Guangzhou Medical University       | [MEDMAMBA: VISION MAMBA FOR MEDICAL IMAGE CLASSIFICATION](https://arxiv.org/pdf/2403.03849.pdf) |   [[Github]](https://github.com/YubiaoYue/MedMamba) |
| 2024-03 |         MamMIL        |          Tsinghua University       | [MamMIL: Multiple Instance Learning for Whole Slide Images with State Space Models](https://arxiv.org/pdf/2403.05160.pdf) |   [[Github]]() |
| 2024-03 |         MambaLithium        |          Ji Hua Laboratory       | [MambaLithium: Selective state space model for remaining-useful-life, state-of-health, and state-of-charge estimation of lithium-ion batteries](https://arxiv.org/pdf/2403.05430.pdf) |   [[Github]](https://github.com/zshicode/MambaLithium) |
| 2024-03 |         LightM-UNet        |          Key Laboratory       | [LightM-UNet: Mamba Assists in Lightweight UNet for Medical Image Segmentation](https://arxiv.org/pdf/2403.05246.pdf) |   [[Github]](https://github.com/MrBlankness/LightM-UNet) |
| 2024-03 |         MambaMIL        |          Hong Kong University       | [MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology](https://arxiv.org/pdf/2403.06800.pdf) |   [[Github]](https://github.com/isyangshu/MambaMIL) |
| 2024-03 |         VideoMamba        |          OpenGVLab & Shenzhen Institute       | [VideoMamba: State Space Model for Efficient Video Understanding](https://arxiv.org/abs/2403.06977) |   [[Github]](https://github.com/OpenGVLab/VideoMamba) |
| 2024-03 |         LargeMamba-UNet        |           Zhejiang University & University of Illinois Urbana-Champaign       | [Large Window-based Mamba UNet for Medical Image Segmentation:Beyond Convolution and Self-attention](https://arxiv.org/pdf/2403.07332.pdf) |   [[Github]](https://github.com/wjh892521292/LMa-UNet) |
| 2024-03 |         Motion Mamba        |           Monash University & The Australian National University       | [Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM](https://arxiv.org/pdf/2403.07332.pdf) |   [[Github]](https://github.com/steve-zeyu-zhang/MotionMamba/) |
| 2024-03 |         LocalMamba        |           The University of Sydney & University of China       | [LocalMamba: Visual State Space Model with Windowed Selective Scan](https://arxiv.org/pdf/2403.09338.pdf) |   [[Github]](https://github.com/hunto/LocalMamba) |
| 2024-03 |         MambaTalk        |           Tsinghua University       | [MambaTalk: Efficient Holistic Gesture Synthesis with Selective State Space Models](https://arxiv.org/pdf/2403.09471.pdf) |   [[Github]]() |
| 2024-03 |         ClinicalMamba        |           Tsinghua University       | [ClinicalMamba: A Generative Clinical Language Model on Longitudinal Clinical Notes](https://arxiv.org/pdf/2403.05795.pdf) |   [[Github]](https://github.com/whaleloops/ClinicalMamba) |
| 2024-03 |         Video Mamba Suite        |           Nanjing University       | [Video Mamba Suite: State Space Model as a Versatile Alternative for Video Understanding](https://arxiv.org/pdf/2403.09626.pdf) |   [[Github]](https://github.com/OpenGVLab/video-mamba-suite) |
| 2024-03 |         EfficientVMamba        |           The University of Sydney       | [EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba](https://arxiv.org/pdf/2403.09977.pdf) |   [[Github]](https://github.com/TerryPei/EfficientVMamba) |
| 2024-03 |         STG-Mamba        |           University of New South Wales       | [STG-Mamba: Spatial-Temporal Graph Learning via Selective State Space Model](https://arxiv.org/pdf/2403.12418.pdf) |   [[Github]]() |
| 2024-03 |         S-D-Mamba        |           Northeastern University       | [Is Mamba Effective for Time Series Forecasting?](https://arxiv.org/pdf/2403.11144.pdf) |   [[Github]](https://github.com/wzhwzhwzh0921/S-D-Mamba) |
| 2024-03 |         Low-shot-[V]-Mamba        |           Mila - Quebec AI Institute       | [On the low-shot transferability of [V]-Mamba](https://arxiv.org/pdf/2403.10696.pdf) |   [[Github]]() |
| 2024-03 |         ZigMa        |           LMU Munich       | [ZigMa: Zigzag Mamba Diffusion Model](https://arxiv.org/pdf/2403.13802.pdf) |   [[Github]](https://github.com/CompVis/zigma) |
| 2024-03 |         ProMamba        |           Peking University       | [ProMamba: Prompt-Mamba for polyp segmentation](https://arxiv.org/pdf/2403.13660.pdf) |   [[Github]]() |
| 2024-03 |         VL-Mamba        |           The University of Adelaide       | [VL-Mamba: Exploring State Space Models for Multimodal Learning](https://arxiv.org/pdf/2403.13600.pdf) |   [[Github]](https://github.com/ZhengYu518/VL-Mamba) |
| 2024-03 |         H-vmunet        |           Shanghai University        | [H-vmunet: High-order Vision Mamba UNet for Medical Image Segmentation](https://arxiv.org/pdf/2403.13642.pdf) |   [[Github]](https://github.com/wurenkai/H-vmunet) |
| 2024-03 |         Cobra        |           Westlake University & Zhejiang University        | [Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference](https://arxiv.org/pdf/2403.14520.pdf) |   [[Github]](https://github.com/h-zhao1997/cobra) |
| 2024-03 |         SiMBA        |           Microsoft        | [SiMBA: Simplified Mamba-based Architecture for Vision and Multivariate Time series](https://arxiv.org/pdf/2403.15360.pdf) |   [[Github]](https://github.com/badripatro/Simba) |



## Video Tutorials
- [Yannic Kilcher] Mamba Paper Explained [Youtube](https://www.youtube.com/watch?v=9dSkvxS2EB0)
- [Umar Jamil] Mamba and S4 Explained [Youtube](https://www.youtube.com/watch?v=8Q_tqwpTpVU)
- [1littlecoder] MoE-Mamba [Youtube](https://www.youtube.com/watch?v=tZD3-uO0RJ0)
- [AI Coffee Break with Letitia] SSM explained [Youtube](https://www.youtube.com/watch?v=vrF3MtGwD0Y)
- [Samuel Albanie] Mamba - a replacement for Transformers? [Youtube](https://www.youtube.com/watch?v=ouF-H35atOY)
- [hu-po] Video Mamba vs Motion Mamba [Youtube](https://www.youtube.com/watch?v=rzXjKcqkjxM)
- [ Fahd Mirza] Install Mamba - State Space Model [Youtube](https://www.youtube.com/watch?app=desktop&v=SX8OL1DGW-I&embeds_referring_euri=https%3A%2F%2Fprimo.ai%2Ffeature=emb_imp_woyt)


## Blogs
- [Joe El Khoury] What is Mamba? [Medium](https://medium.com/@jelkhoury880/what-is-mamba-845987734ffc)
- [Vishal Rajput] Mamba: Can it replace Transformers? [Medium](https://medium.com/aiguys/mamba-can-it-replace-transformers-fe2032537916)
- [Azhar] Decoding Mamba [Medium](https://medium.com/ai-insights-cobet/decoding-mamba-the-next-big-leap-in-ai-sequence-modeling-ef3908060cb8)
- [Maarten Grootendorst] A Visual Guide to Mamba and State Space Models [Substack](https://maartengrootendorst.substack.com/p/a-visual-guide-to-mamba-and-state)
- [Joe El Khoury] Why Mamba was rejected? [Medium](https://medium.com/@jelkhoury880/why-mamba-was-rejected-9b2f05f2141c)
  


## Contributing

This is an active repository and your contributions are always welcome!


---

If you have any questions do not hesitate to contact me at hitesh.patel945@gmail.com, bhargava1409@gmail.com or karangupta485@gmail.com


