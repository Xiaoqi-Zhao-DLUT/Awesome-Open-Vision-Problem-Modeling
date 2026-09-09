# Awesome-Open-Vision-Problem-Modeling
⭐Practical New Tasks and Inspiring Modeling Solutions for Diverse Open Vision Problems⭐

---

### 2026 | Ancient Chinese Character Image Restoration | CVPR Findings

**LWTformer: A Detail-Aware, Learnable Wavelet-Transformer for Ancient Chinese Character Image Restoration**  
<sup>Wentao Ruan, Xinhui Li, Zhan Cheng, Cunhang Fan, Libao Tian, Zhao Lv</sup>  
[Paper](https://openaccess.thecvf.com/content/CVPR2026F/html/Ruan_LWTformer_A_Detail-Aware_Learnable_Wavelet-Transformer_for_Ancient_Chinese_Character_Image_CVPRF_2026_paper.html)/[Code](https://github.com/INWLY/LWTformer)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/4ba9e31c-5bf0-4e39-b2f0-0e33f4553286" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/2eeaec12-48fd-4d75-a288-cb512e9a767c" /> |
| :---: | :---: |
| **Task:** Ancient Chinese character image restoration under erosion, abrasion, fractures, and noise while preserving fine strokes and glyph structures. | **Modeling:** Learnable wavelet-transformer that separates structural and stroke-detail frequencies via 2D-DWT, with structure-aware and wavelet-aware attention for detail-preserving restoration. |

**Datasets:**
* *Oracle Bone Inscription Dataset:* 1,758 paired images of real damaged oracle bone inscriptions.
* *Warring States Period Chu Bamboo Slip Character Dataset (WSC41K):* 41,218 paired Warring States Chu bamboo-slip character images with easy, medium, hard, and mixed degradation levels.


### 2026 | Unripe Tomato Segmentation | AgriEngineering

**CMAE-Unet: A Study on a U-Net-Based Model for Semantic Segmentation of Unripe Tomato Images**  
<sup>Jianhua Zheng, Huanghui Zhao, Xiaoshan Ma, Guiming Huang, Yongshen Liang, Jinfang Liu, Zhaoxi Luo, Yuanlan Ye, Jianru Chen</sup>  
[Paper](https://doi.org/10.3390/agriengineering8090353)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/7caee216-8de9-4f24-88ca-360481ef8a68" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/7a36e7d1-e8dd-4f9b-a0ed-55028deb4fd2" /> |
| :---------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Unripe tomato segmentation under green-on-green camouflage, occlusion, and weak boundaries in natural field scenes. | **Modeling:** U-Net-based semantic segmentation with global-local attention, frequency-domain camouflage suppression, and directional edge enhancement. |


### 2026 | PCB Design Understanding | ICLR

**PCB-Bench: Benchmarking LLMs for Printed Circuit Board Placement and Routing**  
<sup>Jindong Li, Lianrong Chen, Bin Yang, Jiadong Zhu, Ying Wang, Yuzhe Ma, Menglin Yang</sup>  
[Paper](https://openreview.net/forum?id=Q5QLu7XTWx)/[Code](https://github.com/digailab/PCB-Bench)/[Project](https://digailab.github.io/PCB-Bench/)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/3ce8a3d8-730c-4aee-b6be-61e90b680e4f" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/20714254-f095-4fdf-8992-16a1bdd82bdc" /> |
| :-----------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** PCB placement and routing understanding through textual, multimodal, and real-world EDA design reasoning. | **Modeling:** LLM/MLLM-based engineering reasoning over text, PCB layout images, and EDA screenshots under a unified zero-shot evaluation protocol. |


### 2026 | Sky Segmentation | MLKE
**SkySeg-Net: Sky Segmentation-Based Row-Terminal Recognition in Trellised Orchards**  
<sup>Haiyang Gu, Yong Wang, Huaiyang Liu, Tong Tian, Changxing Geng, Yun Shi</sup>  
[Paper](https://www.mdpi.com/2504-4990/8/2/46)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/60c9548a-bc0d-49aa-b267-9a48de2cf37f" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/3ca6033e-ba6e-47e3-b3a0-5ae044d162ee" /> |
|:------------------------------------------------:|:------------------------------------------------:|
| **Task:** Sky-region segmentation for row-terminal recognition in trellised orchards. | **Modeling:** Pixel-level sky segmentation with an enhanced multi-scale U-Net, using ResNeSt, CBAM, and PPM to infer row-terminal positions from sky-area changes. |


### 2026 | Waste Segmentation | ICML
**Towards Effective Waste Segmentation for Automated Waste Recycling in Cluttered Background**  
<sup>Mamoona Javaid, Mubashir Noman, Abdul Hannan, Shah Nawaz, Mustansar Fiaz, Sajid Ghuffar</sup>  
[Paper](https://arxiv.org/abs/2606.13587)/[Code](https://github.com/techmn/ewsegnet)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/20262a82-413c-40bf-b9f2-d1c5cbb3a1a2" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/0170ea50-43d9-4f14-8748-ae7b3d499613" /> |
|:------------------------------------------------:|:------------------------------------------------:|
| **Task:** Waste object segmentation for automated waste recycling in cluttered backgrounds, aiming to accurately segment recyclable or removable waste objects from complex conveyor-belt scenes with heavy occlusion, deformation, and background clutter. | **Modeling:** The recycling scene is formulated as a pixel-level waste segmentation problem. The proposed network cascades spatial-domain modeling for localized structural dependencies and spectral-domain modeling for global contextual relationships, while an auxiliary feature enhancement module strengthens object boundaries and blob-like target regions for robust segmentation in cluttered scenarios. |


### 2026 | Microstructure Image Segmentation | IJCAI
**IPSM-Bench: A New Intermediate Phase Segmentation Benchmark in Microstructure Images of Zinc-Based Absorbable Biomaterials**  
<sup>Jinglin Xu, Shangyan Zhao, Jiabo Wang, Xinghong Mu, Yulong Lei, Jiacheng Zhang, Hongbo Sun, Yageng Li</sup>  
[Paper](https://arxiv.org/abs/2606.11001)/[Code&Dataset](https://github.com/AgileMotionTeam/IPSM-Bench)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/5cc8a404-e94d-4084-98c7-8cd45d8dcd52" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/eb8c2fe2-e6f3-4000-a355-4ed6fbb40a83" /> |
|:------------------------------------------------:|:------------------------------------------------:|
| **Task:** Intermediate phase segmentation in zinc-based absorbable biomaterial microstructure images. | **Modeling:** Pixel-level microstructure segmentation with IPSM-Bench; SCoP-SAM guides SAM using spatial context priors from gradient and grayscale cues. |


### 2025 | Ground-based Cloud Image Segmentation | arXiv
**MPCM-Net: A Multi-scale Network that Integrates Partial Attention Convolution with Mamba for Ground-based Cloud Image Segmentation**  
<sup>Penghui Niu, Jiashuai She, Taotao Cai, Yajuan Zhang, Ping Zhang, Junhua Gu, Jianxin Li</sup>  
[Paper](https://arxiv.org/html/2511.11681)/[Code](https://github.com/she1110/CSRC)

| <img width="400" alt="image" src="https://github.com/user-attachments/assets/78cc2a02-d963-45fe-ac2c-ea407289fe3b" /> | <img width="400" alt="image" src="https://github.com/user-attachments/assets/e739d703-9515-428c-a8d5-0367c64f66fd" /> |
| :----------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Fine-grained ground-based cloud image segmentation with four classes (white cloud, gray cloud, sun, and background) for photovoltaic power forecasting. | **Modeling:** Encoder-decoder segmentation with multi-scale partial attention convolution and Mamba-based decoding for cloud boundary and scale-aware feature modeling. |


### 2025 | Historical Map Segmentation | ICDAR  
**Few-Shot Segmentation of Historical Maps via Linear Probing of Vision Foundation Models**  
<sup>Rafael Sterzinger, Marco Peer, Robert Sablatnig</sup>  
[Paper](https://arxiv.org/abs/2101.02144)

| <img width="400" src="https://github.com/user-attachments/assets/ba145210-e2c4-41dd-9966-eb728bab95ac" /> | <img width="400" src="https://github.com/user-attachments/assets/cb164428-a394-44c6-84ff-339deec9d31a" /> |
|:------------------------------------------------:|:------------------------------------------------:|
| **Task:** Historical map segmentation, aiming to parse scanned historical maps and segment meaningful cartographic or geographic elements such as railways, vineyards, and building blocks from visually heterogeneous map styles. | **Modeling:** The scanned historical map is treated as an image and its symbolic geographic content is converted into pixel-level semantic regions. |


### 2025 | MDD | ICCV
**MDD: A Dataset for Text-and-Music Conditioned Duet Dance Generation**  
<sup>Prerit Gupta, Jason Alexander Fotso-Puepi, Zhengyuan Li, Jay Mehta, Aniket Bera</sup>  
[Paper](https://arxiv.org/abs/2508.16911)/[Code](https://gprerit96.github.io/mdd-page/)

| <img src="images/MDD-task.png" width="800"/> | <img src="images/MDD-result.png" width="1400"/>                                                                                                                                                                           |
| :------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Text-to-Duet for generating coordinated partner movements from a text description and music, and Text-to-Dance Accompaniment for synthesizing context-aware follower motion given the leader’s motion, music and text description.                                               | **Modeling:**  [MDM](https://arxiv.org/abs/2209.14916)/[InterGen](https://arxiv.org/abs/2304.05684)/[Duolando](https://arxiv.org/abs/2403.18811)

 ### 2025 | NRCD | IGARSS
**Non-Registration Change Detection: A Novel Change Detection Task and Benchmark Dataset**  
<sup>Zhe Shan, Lei Zhou, Liu Mao, Shaofan Chen, Chuanqiu Ren, Xia Xie</sup>  
[Paper](https://arxiv.org/abs/2505.09939)/[Code](https://github.com/ShanZard/NRCD)

| <img src="images/NRCD-task.png" width="400"/> | <img src="images/NRCD-result.png" width="400"/>                                                                                                                                                                           |
| :------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:**  Non-registration change detection.                                            | **Modeling:**  General change detection models.


### 2025 | MOSPA | arXiv
**MOSPA: Human Motion Generation Driven by Spatial Audio**  
<sup>Shuyang Xu, Zhiyang Dou, Mingyi Shi, Liang Pan, Leo Ho, Jingbo Wang, Yuan Liu, Cheng Lin, Yuexin Ma, Wenping Wang, Taku Komura</sup>  
[Paper](https://arxiv.org/abs/2507.11949)

| <img src="images/MOSPA-task.png" width="800"/> | <img src="images/MOSPA-result.png" width="400"/>                                                                                                                                                                           |
| :------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Human motion generation task centered on spatial audio-driven human motion synthesis.                                               | **Modeling:**  A diffusion-based generative framework (MOSPA)  captures the relationship between body motion and spatial audio through
 an effective fusion mechanism. |


### 2025 | EMind | arXiv
**EMind: A Foundation Model for Multi-task Electromagnetic Signals Understanding**  
<sup>Luqing Luo, Wenjin Gui, Yunfei Liu, Ziyue Zhang, Yunxi Zhang, Fengxiang Wang, Zonghao Guo, Zizhi Ma, Xinzhu Liu, Hanxiang He, Jinhai Li, Xin Qiu, Wupeng Xie, Yangang Sun</sup>  
[Paper](https://www.arxiv.org/pdf/2508.18785)/[Code](https://github.com/GabrielleTse/EMind)

| <img src="https://github.com/user-attachments/assets/2773c716-018e-41bc-808c-d62d1bc38ef7" width="800"/> | <img src="https://github.com/user-attachments/assets/54f84b54-a0c3-4965-be0c-2d4d68786ad2" width="400"/>                                                                                                                                                                           |
| :------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Multi-task Electromagnetic Signals Understanding.                                              | **Modeling:** EMind, an electromagnetic signals foundation model that bridges large scale pretraining and the unique nature of this modality based on the proposed first unified and largest standardized electromagnetic signal dataset covering multiple signal types and tasks. |

### 2025 | GraphDoc | ICLR
**Graph-based Document Structure Analysis**  
<sup>Yufan Chen, Ruiping Liu, Junwei Zheng, Di Wen, Kunyu Peng, Jiaming Zhang, Rainer Stiefelhagen</sup>  
[Paper](https://arxiv.org/pdf/2403.14442)/[Code](https://github.com/yufanchen96/GraphDoc)

| <img src="images/GraphDoc-task.png" width="800"/> | <img src="images/GraphDoc-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Graph-based Document Structure Analysis. | **Modeling:** Document Relation Graph Generator(DRGG) combines object detection with relation prediction, capturing both spatial and logical relatioins between document elements.|

### 2025 | Paper2Poster | arXiv
**Paper2Poster: Towards Multimodal Poster Automation from Scientific Papers**  
<sup>Wei Pang, Kevin Qinghong Lin, Xiangru Jian, Xi He, Philip Torr</sup>  
[Paper](https://arxiv.org/abs/2505.21497)/[Code](https://github.com/Paper2Poster/Paper2Poster)

| <img src="images/Paper2Poster-task.png" width="800"/> | <img src="images/Paper2Poster-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Automatic academic poster generation from long-context scientific papers. | **Modeling:**  PosterAgent, a visual-in-the-loop multi-agent pipeline with parsing, binary-tree layout planning, and iterative VLM-guided rendering refinement.|


### 2025 | DiffSensei | CVPR
**DiffSensei: Bridging Multi-Modal LLMs and Diffusion Models for Customized Manga Generation**  
<sup>Jianzong Wu, Chao Tang, Jingbo Wang, Yanhong Zeng, Xiangtai Li, Yunhai Tong</sup>  
[Paper](https://arxiv.org/abs/2412.07589)/[Code](https://github.com/jianzongwu/DiffSensei)

| <img src="images/DiffSensei-task.png" width="400"/> | <img src="images/DiffSensei-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Customized manga generation with dynamic multi-character control from text. | **Modeling:**  Diffusion–MLLM hybrid framework using a text-compatible identity adapter and masked cross-attention for precise character and layout control.|


### 2025 | LLada | ICCV
**Where, What, Why: Towards Explainable Driver Attention Prediction**  
<sup> Yuchen Zhou, Jiayu Tang, Xiaoyan Xiao, Yueyao Lin, Linkai Liu, Zipeng Guo, Hao Fei, Xiaobo Xia, Chao Gou</sup>  
[Paper](https://arxiv.org/pdf/2506.23088)/[Code](https://github.com/yuchen2199/Explainable-Driver-Attention-Prediction)

| <img src="images/LLada-task.png" width="400"/> | <img src="images/LLada-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Explainable Driver Attention Prediction that identifies where drivers look, what they attend to, and why. | **Modeling:**  LLada, an LLM-driven framework integrating pixel-level attention, semantic parsing, and causal reasoning in an end-to-end model.|

### 2025 | DiffHDR | AAAI  
**Predicting the Original Appearance of Damaged Historical Documents**  
<sup> Zhenhua Yang, Dezhi Peng, Yongxin Shi, Yuyi Zhang, Chongyu Liu, Lianwen Jin</sup>  
[Paper](https://arxiv.org/pdf/2412.11634)/[Code](https://github.com/yeungchenwa/HDR)

| <img src="images/DiffHDR-task.png" width="400"/> | <img src="images/DiffHDR-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Historical Document Repair to reconstruct the original appearance of damaged historical texts. | **Modeling:**  Diffusion-based DiffHDR with semantic–spatial guidance and character perceptual loss for coherent restoration.|


### 2025 | Rose4D | CVPR  
**Birth and Death of a Rose**  
<sup> Chen Geng, Yunzhi Zhang, Shangzhe Wu, Jiajun Wu</sup>  
[Paper](https://arxiv.org/abs/2412.05278)

| <img src="images/Rose4D-task.png" width="400"/> | <img src="images/Rose4D-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Generation of temporally evolving 3D object intrinsics from pretrained 2D models. | **Modeling:**  Neural Template–guided temporal-state distillation from 2D diffusion features for consistent multi-view, multi-time rendering.|


### 2025 | GFlow | AAAI  
**GFlow: Recovering 4D World from Monocular Video**  
<sup> Shizun Wang, Xingyi Yang, Qiuhong Shen, Zhenxiang Jiang, Xinchao Wang</sup>  
[Paper](https://arxiv.org/pdf/2405.18426)/[Code](https://github.com/littlepure2333/gflow)

| <img src="images/GFlow-task.png" width="400"/> | <img src="images/GFlow-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** 4D scene reconstruction from a single monocular video without camera parameters. | **Modeling:**  2D-prior-guided 4D Gaussian flow with alternating pose and dynamics optimization.|

### 2025 | VecFormer | arXiv  
**Point or Line? Using Line-based Representation for Panoptic Symbol Spotting in CAD Drawings**  
<sup> Xingguang Wei∗, Haomin Wang∗, Shenglong Ye, Ruifeng Luo, Yanting Zhang, Lixin Gu, Jifeng Dai, Yu Qiao, Wenhai Wang, Hongjie Zhang</sup>  
[Paper](https://arxiv.org/pdf/2505.23395)

| <img src="images/VecFormer-task.png" width="400"/> | <img src="images/VecFormer-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Computer-aided design (CAD) drawings. | **Modeling:** Type-agnostic and expressive line-based representation.|

### 2025 | SimGen | arXiv  
**SIMGEN: A DIFFUSION-BASED FRAMEWORK FOR SIMULTANEOUS SURGICAL IMAGE AND SEGMENTATION MASK GENERATION**  
<sup> Aditya Bhat, Rupak Bose, Chinedu Innocent Nwoye, Nicolas Padoy</sup>  
[Paper](https://arxiv.org/pdf/2501.09008)

| <img src="images/SimGen-task.png" width="400"/> | <img src="images/SimGen-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:** Simultaneous generation of surgical images and corresponding segmentation masks. | **Modeling:** Diffusion-based framework with cross-correlation priors and Canonical Fibonacci Lattice for aligned image–mask synthesis.|

### 2024 | PanAf20K | IJCV
**PanAf20K: A Large Video Dataset for Wild Ape Detection and Behaviour Recognition**  
<sup>Otto Brookes, Majid Mirmehdi, Colleen Stephens, Samuel Angedakin,
 Katherine Corogenes, Dervla Dowd, Paula Dieguez, Thurston C. Hicks,
 Sorrel Jones, Kevin Lee, Vera Leinert, Juan Lapuente,
 Maureen S. McCarthy, Amelia Meier, Mizuki Murai, Emmanuelle Normand,
 Virginie Vergnes, Erin G. Wessling, Roman M. Wittig, Kevin Langergraber,
 Nuria Maldonado, Xinyu Yang, Klaus Zuberb¨uhler, Christophe Boesch,
 Mimi Arandjelovic, Hjalmar K¨uhl, Tilo Burghardt
 </sup>  
[Paper](https://arxiv.org/pdf/2401.13554)/[Code](https://obrookes.github.io/panaf.github.io/)

| <img src="images/PanAf20K-task.png" width="800"/> | <img src="images/PanAf20K-result.png" width="400"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task:**  Wild Ape Detection and Behaviour Recognition. | **Modeling:** Object Detection + Behavioural Action Recognition.|

### 2024 | NIGHTTIME OPTICAL FLOW | ICLR  
**EXPLORING THE COMMON APPEARANCE-BOUNDARY ADAPTATION FOR NIGHTTIME OPTICAL FLOW**  
<sup>Hanyu Zhou, Yi Chang, Haoyue Liu, Wending Yan, Yuxing Duan, Zhiwei Shi, Luxin Yan</sup>  
[Paper](https://arxiv.org/abs/2401.17642)

| <img src="images/NightFlow-task.png" width="400"/> | <img src="images/NightFlow-result.png" width="500"/> |
|:--------------------------------------------------:|:--------------------------------------------------:|
| **Task Definition:** Nighttime optical flow estimation. | **Modeling:** Cross-domain motion alignment. |

### 2024 | OVCoser | ECCV  
**Open-Vocabulary Camouflaged Object Segmentation**  
<sup> Youwei Pang*, Xiaoqi Zhao*, Jiaming Zuo, Lihe Zhang, Huchuan Lu</sup>  
[Paper](https://arxiv.org/pdf/2405.19423)/[Code](https://github.com/YouweiPang/OVCOS)

| <img src="images/OVCoser-task.png" width="400"/> | <img src="images/OVCoser-result.png" width="500"/> |
|:---------------------------------------------:|:----------------------------------------------:|
| **Task:** open-vocabulary camouflaged object segmentation. | **Modeling:**  open-set recognition and camouflage-aware segmentation. |

### 2024 | PaSCo | CVPR  
**PaSCo: Urban 3D Panoptic Scene Completion with Uncertainty Awareness**  
<sup>Anh-Quan Cao, Angela Dai, Raoul de Charette</sup>  
[Paper](https://arxiv.org/pdf/2312.02158)/[Code](https://astra-vision.github.io/PaSCo/)

| <img src="images/PaSCo-task.png" width="400"/> | <img src="images/PaSCo-result.png" width="400"/> |
|:---------------------------------------------:|:----------------------------------------------:|
| **Task:** Urban 3D panoptic scene completion with instance-level understanding and uncertainty estimation. | **Modeling:**  Hybrid mask-based PSC with MIMO ensembling for voxel- and instance-wise uncertainty. |

### 2024 | PBD | CVPR  
**Towards Automatic Power Battery Detection: New Challenge, Benchmark Dataset and Baseline**  
<sup>Xiaoqi Zhao*, Youwei Pang*, Zhenyu Chen, Qian Yu, Lihe Zhang, Hanqi Liu, Jiaming Zuo, Huchuan Lu</sup>  
[Paper](https://arxiv.org/pdf/2312.02528v2)/[Code](https://github.com/Xiaoqi-Zhao-DLUT/X-ray-PBD)

| <img src="images/PBD-task.png" width="400"/> | <img src="images/PBD-result.png" width="400"/> |
|:---------------------------------------------:|:----------------------------------------------:|
| **Task:** Fine-grained detection of battery plates from X-ray/CT images. | **Modeling:**  Multi-dimensional collaborative framework (point, line, number). |

### 2023 | Crater Detection | arXiv
**Deep Learning based Systems for Crater Detection: A Review**
<sup>Atal Tewari, K. Prateek, Amrita Singh, Nitin Khanna</sup>
[Paper](https://arxiv.org/abs/2310.07727)

| <img src="https://github.com/user-attachments/assets/5bb8f1bb-930c-402c-b8fb-295bd35ea426" width="500"/> |                                          <img src="https://github.com/user-attachments/assets/ee46af4a-9ddf-4322-9375-de0b4dc86b6e" height="200"/>                                           |
| :------------------------------------------------------------------------------------------------------- | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Task:** Crater detection on lunar digital elevation maps (DEMs).                                       | **Modeling:** It can be formulated as candidate-region classification, crater-mask segmentation with post-processing, or direct object detection for estimating crater locations and sizes. |

NOTE: *The planetary data mainly used for crater detection are digital orthophoto maps (DOMs), digital elevation maps (DEMs), and near IR images. These data’s characteristics differ from one another, such as DOMs and infrared images are affected by sun angle and cause highlight and shadow patterns. In contrast, DEMs are unaffected but lack complex terrain information.*

### 2023 | WireSegHR | CVPR  
**Automatic High Resolution Wire Segmentation and Removal**  
<sup>Mang Tik Chiu, Xuaner Zhang, Zijun Wei, Yuqian Zhou, Eli Shechtman, Connelly Barnes, Zhe Lin, Florian Kainz, Sohrab Amirghodsi, Humphrey Shi</sup>  
[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Chiu_Automatic_High_Resolution_Wire_Segmentation_and_Removal_CVPR_2023_paper.pdf)/[Code](https://github.com/adobe-research/auto-wire-removal)

| <img src="images/WireSeg-task.png" width="500"/> | <img src="images/WireSeg-result.png" width="500"/> |
|:-------------------------------------------------:|:-------------------------------------------------:|
| **Task:**  Wire segmentation in high-res images. | **Modeling:**  Thin-structure semantic segmentation. |

### 2023 | TSI | arXiv  
**Traffic Sign Interpretation in Real Road Scene**  
<sup>Chuang Yang, Kai Zhuang, Mulin Chen, Haozhao Ma, Xu Han, Tao Han, Changxing Guo, Han Han, Bingxuan Zhao, Qi Wang</sup>  
[Paper](https://arxiv.org/pdf/2311.10793)

| <img src="images/TSI-task.png" width="400"/> | <img src="images/TSI-result.png" width="500"/> |
|:-----------------------------------------------:|:-----------------------------------------------:|
| **Task:** Traffic sign interpretation. | **Modeling:** Textual interpretation of traffic scenarios via logical reasoning. |

### 2022 | IOD | CVPR  
**Explore Spatio-temporal Aggregation for Insubstantial Object Detection: Benchmark Dataset and Baseline**  
<sup>Kailai Zhou, Yibo Wang, Tao Lv, Yunqian Li, Linsen Chen, Qiu Shen*, Xun Cao*</sup>  
[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhou_Explore_Spatio-Temporal_Aggregation_for_Insubstantial_Object_Detection_Benchmark_Dataset_and_CVPR_2022_paper.pdf)/[Code](https://github.com/CalayZhou/IOD-Video)

| <img src="images/IOD-task.png" width="400"/> | <img src="images/IOD-result.png" width="600"/> |
|:---------------------------------------------:|:---------------------------------------------:|
| **Task:**  Insubstantial object detection. | **Modeling:** Voxel-based shift field models motion and spatial uncertainty. |

### 2022 | CCSE | arXiv  
**Instance Segmentation for Chinese Character Stroke Extraction, Datasets and Benchmarks**  
<sup>Lizhao Liu*, Kunyang Lin, Shangxin Huang, Zhongli Li, Chao Li, Yunbo Cao, and Qingyu Zhou</sup>  
[Paper](https://arxiv.org/pdf/2210.13826)/[Code](https://github.com/lizhaoliu-Lec/CCSE)

| <img src="images/CCSE-task.png" width="400"/> | <img src="images/CCSE-result.png" width="600"/> |
|:------------------------------------------------:|:------------------------------------------------:|
| **Task:**  Chinese character stroke extraction. | **Modeling:** Stroke-level instance segmentation. |
