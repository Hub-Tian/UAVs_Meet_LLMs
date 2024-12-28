<!-- 
   ================================
   README for "UAVs Meet LLMs"
   ================================
-->

<h1 align="center">
  🚁 UAVs Meet LLMs 🚀
</h1>

<p align="center">
  <!-- 1) Awesome Badge -->
  <a href="https://awesome.re" target="_blank">
    <img src="https://awesome.re/badge.svg" alt="Awesome Badge"/>
  </a>
  
  <!-- 2) Maintain Status Badge -->
  <img src="https://img.shields.io/badge/Maintain-Active-8A2BE2?style=flat-square&logo=github&logoColor=white" alt="Maintain Badge"/>

  <!-- 3) PR's Welcome Badge -->
  <a href="http://makeapullrequest.com" target="_blank">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat" alt="PR's Welcome"/>
  </a>

  <!-- 4) Visitor Badge: replace 'YourGitHubName' with your GitHub username or org name -->
  <a href="https://github.com/Hub-Tian/UAVs_Meet_LLMs" target="_blank">
    <img src="https://visitor-badge.laobi.icu/badge?page_id=YourGitHubName.UAVs_Meet_LLMs&left_color=%239146DE&right_color=%23E6C82D" alt="Visitor Badge"/>
  </a>
</p>

<p align="center">
  <strong>Where Unmanned Aerial Vehicles Take Off and Large Language Models Unfold!</strong>
</p>

<hr/>

<!-- About Section -->
# 🏡About
This repository accompanies the work:  
**UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility** 

This is an active repository, you can watch for the latest advances.  
If you find it useful, please star ⭐ this repo and [cite](#citation) the paper.

---

## 🔥 News
- **[2024-12-28]** This repository is newly launched to explore the synergy between **Unmanned Aerial Vehicles (UAVs)** and **Large Language Models (LLMs)**. We will continually update it with fresh papers, demos, and insights.
- **[2023-12-27]** [Yiduo Li](https://github.com/Leeeufo02) added the content of the dataset section
- **[2023-12-27]** [Fei Lin](https://github.com/linfei-mise) and [Yonglin Tian](https://github.com/Hub-Tian) curated this list and published the first version.

> If you have any questions or suggestions, please feel free to open an [issue](https://github.com/Hub-Tian/UAVs_Meet_LLMs/issues) or contact us via email.

---

## Introduction
This repository accompanies our work on **"UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility"**.  
Here, we primarily store various **tables** referenced in the survey/overview paper. These tables focus on:

- Summarization of **LLMs, VLMs, and VFMs**  
- Summaries of **Methods and Models**  
- **UAV-oriented Datasets** across multiple application domains

> **Note**: The goal is to provide a structured, easy-to-navigate resource for researchers interested in the intersection of UAVs and Large Language Models.

---

## Table of Contents

- [Summarization of LLMs, VLMs, and VFMs](#summarization-of-llms-vlms-and-vfms)
  - [LLMs](#llms)
  - [VLMs](#vlms)
  - [VFMs](#vfms)
- [Summary of Methods and Models](#summary-of-methods-and-models)
  - [Visual Perception](#visual-perception)
  - [Flight Control](#flight-control)
  - [Planning](#planning)
  - [VLN](#vln)
  - [Infrastructures](#infrastructures)
- [UAV-oriented Datasets on Environmental Perception & Event Recognition & Detection](#uav-oriented-datasets-on-environmental-perception--event-recognition--detection)
  - [Environmental Perception](#environmental-perception)
  - [Event Recognition](#event-recognition)
  - [Detection](#detection)
- [UAV-oriented Datasets on Object Tracking](#uav-oriented-datasets-on-object-tracking)
- [UAV-oriented Datasets on Action Recognition](#uav-oriented-datasets-on-action-recognition)
- [UAV-oriented Datasets on Navigation and Localization](#uav-oriented-datasets-on-navigation-and-localization)
- [UAV-oriented Datasets on Transportation](#uav-oriented-datasets-on-transportation)
- [UAV-oriented Datasets on Remote Sensing](#uav-oriented-datasets-on-remote-sensing)
- [UAV-oriented Datasets on Agriculture & Industry & Emergency Response & Military & Wildlife](#uav-oriented-datasets-on-agriculture--industry--emergency-response--military--wildlife)
  - [Agriculture](#agriculture)
  - [Industry](#industry)
  - [Emergency Response](#emergency-response)
  - [Military](#military)
  - [Wildlife](#wildlife)

---

## Summarization of LLMs, VLMs, and VFMs

### LLMs

| **Subcategory** | **Model Name**                            | **Institution / Author**                                         |
|:--------------: |:-----------------------------------------: |:----------------------------------------------------------------:|
| **General**     | GPT-3, GPT-3.5, GPT-4                     | [OpenAI](https://openai.com)                                     |
|                | Claude 2, Claude 3                         | [Anthropic](https://www.anthropic.com)                           |
|                | Mistral series                             | [Mistral AI](https://www.mistral.ai)                             |
|                | PaLM series, Gemini series                 | [Google Research](https://ai.google)                             |
|                | LLaMA, LLaMA2, LLaMA3                      | [Meta AI](https://ai.meta.com)                                   |
|                | Vicuna                                     | [Vicuna Team](https://vicuna.lmsys.org)                          |
|                | Qwen series                                | [Qwen Team, Alibaba Group](https://github.com/QwenLM)            |
|                | InternLM                                   | [Shanghai AI Laboratory](https://github.com/InternLM/InternLM)   |
|                | BuboGPT                                    | [Bytedance](https://github.com/magic-research/bubogpt)           |
|                | ChatGLM                                    | [Zhipu AI](https://github.com/THUDM)                             |
|                | DeepSeek series                            | [DeepSeek](https://github.com/deepseek-ai)                       |

### VLMs

| **Subcategory**       | **Model Name**                                           | **Institution / Author**                                                                   |
|:---------------------:|:--------------------------------------------------------:|:-------------------------------------------------------------------------------------------:|
| **General**           | GPT-4V, GPT-4o, GPT-4o mini, GPT o1-preview              | [OpenAI](https://openai.com)                                                               |
|                       | Claude 3 Opus, Claude 3.5 Sonnet                         | [Anthropic](https://www.anthropic.com)                                                     |
|                       | Step-2                                                  | [Jieyue Xingchen](https://www.stepfun.com/)                                                |
|                       | LLaVA, LLaVA-1.5, LLaVA-NeXT                             | [Liu et al.](https://github.com/haotian-liu/LLaVA)                                         |
|                       | MoE-LLaVA                                               | [Lin et al.](https://github.com/PKU-YuanGroup/MoE-LLaVA)                                   |
|                       | LLaVA-CoT                                               | [Xu et al.](https://github.com/PKU-YuanGroup/LLaVA-CoT)                                    |
|                       | Flamingo                                               | [Alayrac et al.](https://github.com/mlfoundations/open_flamingo)                           |
|                       | BLIP                                                   | [Li et al.](https://github.com/salesforce/BLIP)                                            |
|                       | BLIP-2                                                 | [Li et al.](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)                  |
|                       | InstructBLIP                                           | [Dai et al.](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)          |
| **Video Understanding** | LLaMA-VID                                             | [Li et al.](https://github.com/dvlab-research/LLaMA-VID)                                   |
|                       | IG-VLM                                                 | [Kim et al.](https://github.com/imagegridworth/IG-VLM)                                     |
|                       | Video-ChatGPT                                          | [Maaz et al.](https://github.com/mbzuai-oryx/Video-ChatGPT)                                |
|                       | VideoTree                                             | [Wang et al.](https://github.com/Ziyang412/VideoTree)                                      |
| **Visual Reasoning**  | X-VLM                                                 | [Zeng et al.](https://github.com/zengyan-97/X-VLM)                                         |
|                       | Chameleon                                             | [Lu et al.](https://chameleon-llm.github.io/)                                              |
|                       | HYDRA                                                 | [Ke et al.](https://hydra-vl4ai.github.io/)                                                |
|                       | VISPROG                                               | [PRIOR @ Allen Institute for AI](https://prior.allenai.org/projects/visprog)               |

### VFMs

| **Subcategory**       | **Model Name**                        | **Institution / Author**                                                 |
|:---------------------:|:-------------------------------------:|:-------------------------------------------------------------------------:|
| **General**           | CLIP                                  | [OpenAI](https://github.com/OpenAI/CLIP)                                |
|                       | FILIP                                 | Yao et al.                                                               |
|                       | RegionCLIP                            | [Microsoft Research](https://github.com/microsoft/RegionCLIP)           |
|                       | EVA-CLIP                              | [Sun et al.](https://github.com/baaivision/EVA/tree/master/EVA-CLIP)    |
| **Object Detection**  | GLIP                                  | [Microsoft Research](https://github.com/microsoft/GLIP)                 |
|                       | DINO                                  | Zhang et al.                                                             |
|                       | Grounding-DINO                        | [Liu et al.](https://github.com/IDEA-Research/GroundingDINO)            |
|                       | DINOv2                                | [Meta AI Research](https://github.com/facebookresearch/dinov2)          |
|                       | AM-RADIO                              | [NVIDIA](https://github.com/NVlabs/RADIO)                               |
|                       | DINO-WM                               | Zhou et al.                                                              |
|                       | YOLO-World                            | [Cheng et al.](https://github.com/AILabCVC/YOLO-World)                  |
| **Image Segmentation** | CLIPSeg                               | [Lüdecke and Ecker](https://github.com/timojl/clipseg)                   |
|                       | SAM                                   | [Meta AI Research, FAIR](https://segment-anything.com)                   |
|                       | Embodied-SAM                          | [Xu et al.](https://github.com/xuxw98/ESAM)                              |
|                       | Point-SAM                             | [Zhou et al.](https://github.com/zyc00/Point-SAM)                        |
|                       | Open-Vocabulary SAM                   | [Yuan et al.](https://www.mmlab-ntu.com/project/ovsam/)                  |
|                       | TAP                                   | [Pan et al.](https://github.com/baaivision/tokenize-anything)           |
|                       | EfficientSAM                          | [Xiong et al.](https://yformer.github.io/efficient-sam/)                |
|                       | MobileSAM                             | [Zhang et al.](https://github.com/ChaoningZhang/MobileSAM)              |
|                       | SAM 2                                 | [Meta AI Research, FAIR](https://ai.meta.com/sam2/)                      |
|                       | SAMURAI                               | [University of Washington](https://github.com/yangchris11/samurai)       |
|                       | SegGPT                                | [Wang et al.](https://github.com/baaivision/Painter)                     |
|                       | Osprey                                | [Yuan et al.](https://github.com/CircleRadon/Osprey)                     |
|                       | SEEM                                  | Zou et al.                                                               |
|                       | Seal                                  | [Liu et al.](https://github.com/youquanl/Segment-Any-Point-Cloud)        |
|                       | LISA                                  | [Lai et al.](https://github.com/dvlabresearch/LISA)                      |
| **Depth Estimation**  | ZoeDepth                              | [Bhat et al.](https://github.com/isl-org/ZoeDepth)                       |
|                       | ScaleDepth                            | [Zhu et al.](https://ruijiezhu94.github.io/ScaleDepth/)                  |
|                       | Depth Anything                        | [Yang et al.](https://depth-anything.github.io)                          |
|                       | Depth Anything V2                     | [Yang et al.](https://depth-anything-v2.github.io/)                      |
|                       | Depth Pro                             | [Apple](https://github.com/apple/ml-depth-pro)                           |

## Summary of Methods and Models
### Visual Perception

| Title              | Type         | Publication        | Code            |
|--------------------|-------------|--------------------|-----------------|
| Li et al. (A Benchmark for UAV-View Natural Language-Guided Tracking)       | VFM         | [ _MDPI_ ](https://www.mdpi.com/2079-9292/13/9/1706)      | [ _GitHub_ ](https://github.com/Lich-King000/UAVNLT)  |
| Ma et al. (Applying Unsupervised Semantic Segmentation to High-Resolution UAV Imagery for Enhanced Road Scene Parsing)       | VFM         | [ _Arxiv_ ](https://arxiv.org/abs/2402.02985)      | - |
| Limberg et al. ()  | VFM+VLM     | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| Kim et al. ()      | VLM+VFM     | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| LGNet ()           | VFM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| Sakaino et al. ()  | VLM+VFM     | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| COMRP ()           | VFM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| CrossEarth ()      | VFM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| TanDepth ()        | VFM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| DroneGPT ()        | VLM+LLM+VFM | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| de Zarzà et al. () | LLM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| AeroAgent ()       | VLM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| RS-LLaVA ()        | VLM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| GeoRSCLIP ()       | VFM         | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |
| SkyEyeGPT ()       | VFM+LLM     | [ _Arxiv_ ]()      | [ _GitHub_ ]()  |

### Flight Control

| Title             | Type | Publication       | Code           |
|-------------------|-----:|-------------------|----------------|
| PromptCraft ()    | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Zhong et al. ()   | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Tazir et al. ()   | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Phadke et al. ()  | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| EAI-SIM ()        | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| TAIiST ()         | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Swarm-GPT ()      | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| FlockGPT ()       | LLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| CLIPSwarm ()      | VFM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |

### Planning

| Title          | Type         | Publication       | Code           |
|----------------|-------------:|-------------------|----------------|
| TypeFly ()     | LLM          | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| SPINE ()       | LLM+VFM+VLM  | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| LEVIOSA ()     | LLM          | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| TPML ()        | LLM          | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| REAL ()        | LLM          | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Liu et al. ()  | LLM          | [ _Arxiv_ ]()     | [ _GitHub_ ]() |

### VLN

| Title                | Type         | Publication       | Code           |
|----------------------|-------------:|-------------------|----------------|
| NaVid ()            | VFM+LLM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| VLN-MP ()           | VFM           | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Gao et al. ()       | VFM+LLM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| MGP ()              | LLM+VFM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| UAV Navigation LLM () | LLM+VFM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| GOMAA-Geo ()        | LLM+VFM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| NavAgent ()         | LLM+VFM+VLM   | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| ASMA ()             | LLM+VFM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Zhang et al. ()     | VFM+LLM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Chen et al. ()      | LLM           | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| CloudTrack ()       | VFM+VLM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| NEUSIS ()           | VFM+VLM       | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Say-REAPEx ()       | LLM           | [ _Arxiv_ ]()     | [ _GitHub_ ]() |

### Infrastructures

| Title             | Type    | Publication       | Code           |
|-------------------|--------:|-------------------|----------------|
| DTLLM-VLT ()      | VFM+LLM | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Yao et al. ()     | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| GPG2A ()          | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| AeroVerse ()      | VLM+LLM | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Tang et al. ()    | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Xu et al. ()      | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| LLM-RS ()         | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |
| Pineli et al. ()  | LLM     | [ _Arxiv_ ]()     | [ _GitHub_ ]() |

### UAV Swarm Path Planning Method

|               **Category**               |            **Examples**           | **References**                                                                 |
|:----------------------------------------:|:--------------------------------:|:--------------------------------------------------------------------------------:|
| **_Intelligent optimization algorithm_** |       Ant Colony Algorithm       | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5498477)        |
|                                          |         Genetic Algorithm        | [Ref](https://www.worldscientific.com/doi/abs/10.1142/S0218213017600089)     |
|                                          |   Simulated Annealing Algorithm  | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8483993)        |
| **_Mathematical programming_**           | mixed integer linear programming | [Ref](https://journals.sagepub.com/doi/abs/10.1177/0954410015609361)          |
|                                          |       nonlinear programming      | [Ref](https://arc.aiaa.org/doi/abs/10.2514/6.2006-6199)                      |
| **_AI based method_**                    |           Deep Learning          | [Ref](https://www.sciencedirect.com/science/article/abs/pii/S1270963820311172?via%3Dihub) |
|                                          |      Reinforcement Learning      | [Ref](https://doi.org/10.1016/j.ast.2021.107052)                             |


### UAV Swarm Task Allocation

| **Category**                      | **Examples**                            | **References**                                                                                   |
|:----------------------------------:|:---------------------------------------:|:------------------------------------------------------------------------------------------------:|
| **_Heuristic Algorithm_**          | Particle Swarm Optimization Algorithm   | [Ref](https://arc.aiaa.org/doi/abs/10.2514/6.2008-6837)                                      |
|                                    | Genetic Algorithm                       | [Ref](https://ieeexplore.ieee.org/abstract/document/9483937)                                  |
|                                    | Simulated Annealing Algorithm           | [Ref](https://iopscience.iop.org/article/10.1088/1742-6596/2246/1/012081/meta)                |
| **_AI Based Algorithm_**           | Reinforcement Learning                  | [Ref](https://doi.org/10.1016/j.ast.2019.06.024)                                              |
|                                    | Artificial Neural Network               | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670550)                      |
| **_Mathematical Programming Methods_** | Mixed Integer Programming              | [Ref](https://doi.org/10.2514/6.2004-6410)                                                   |
| **_Market Mechanism Based Method_** | Auction Based Algorithm                 | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7813107)                       |
|                                    | Consensus Based Bundle Algorithm        | [Ref](https://doi.org/10.3390/s20082307)                                                     |
|                                    | Contract Net Protocol                   | [Ref](https://doi.org/10.3390/s22124486)                                                     |


### UAV Swarm Formation Control Algorithm

|            **Category**            |                  **Example**                 |                                  **References**                                 |
|:----------------------------------:|:--------------------------------------------:|:-------------------------------------------------------------------------------:|
| **_    Centralized Control   _**   |               Virtual Structure              |     [Ref](https://ascelibrary.org/doi/abs/10.1061/(ASCE)AS.1943-5525.0000351)          |
|                                    |           Leader-Follower Approaches         |     [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=680621)             |
| **_    Decentralized Control   _** |     Decentralized Model Prediction Method    | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1429425)                |
| **_    Distributed Control   _**   |                Behavior Method               |     [Ref](https://intapi.sciendo.com/pdf/10.1515/ama-2016-0015)                        |
|                                    |               Consistency Method             | [Ref](https://doi.org/10.3390/drones7030185)                                           |

### UAV Emboided Configurations

| **Category**           | **Characteristics**                                                                             | **Advantages**                                             | **Disadvantages**                                      |
|------------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------|
| **Fixed-wing UAV**      | Fixed wings generate lift with forward motion.                                                  | High speed, long endurance, stable flight.                 | Cannot hover, high demands for takeoff/landing areas.   |
| **Multirotor UAV**      | Multiple rotors provide lift and control.                                                      | Low cost, easy operation, capable of VTOL and hovering.    | Limited flight time, low speed, small payload capacity. |
| **Unmanned Helicopter** | Single or dual rotors allow vertical take-off and hovering.                                    | High payload capacity, good wind resistance, long endurance, VTOL. | Complex structure, higher maintenance cost, slower than fixed-wing UAVs. |
| **Hybrid UAV**          | Combines fixed-wing and multirotor capabilities.                                                | Flexible missions, long endurance, VTOL.                   | Complex mechanisms, higher cost.                       |
| **Flapping-wing UAV**   | Uses clap-and-fling mechanism for flight.                                                      | Low noise, high propulsion efficiency, high maneuverability. | Complex analysis and control, limited payload capacity. |
| **Unmanned Airship**    | Aerostat aircraft with gasbag for lift.                                                         | Low cost, low noise.                                      | Low speed, low maneuverability, highly affected by wind. |


## UAV-oriented Datasets on Environmental Perception & Event Recognition & Detection
### Environmental Perception 

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [AirFisheye](https://collaborating.tuhh.de/ilt/airfisheye-dataset) | 2024     | Fisheye image, Depth image, Point cloud, IMU | Over 26,000 fisheye images in total. Data is collected at a rate of 10 frames per second.                   |
| [SynDrone](https://github.com/LTTM/Syndrone)                | 2023     | Image, Depth image, Point cloud       | Contains 72,000 annotation samples, providing 28 types of pixel-level and object-level annotations.        |
| [WildUAV](https://github.com/hrflr/wuav)                   | 2022     | Image, Video, Depth image, Metadata  | Mapping images are provided as 24-bit PNG files, with the resolution of 5280x3956. Video images are provided as JPG files at a resolution of 3840x2160. There are 16 possible class labels detailed. |

### Event Recognition

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [CapERA](https://github.com/yakoubbazi/CapEra)              | 2023     | Video, Text                           | 2864 videos, each with 5 descriptions, totaling 14,320 texts. Each video lasts 5 seconds and is captured at 30 frames/second with a resolution of 640 × 640 pixels. |
| [ERA](https://lcmou.github.io/ERA_Dataset)                 | 2020     | Video                                 | A total of 2,864 videos, including disaster events, traffic accidents, sports competitions, and other 25 categories. Each video is 24 frames/second for 5 seconds. |
| [VIRAT](https://viratdata.org/)                            | 2016     | Video                                 | 25 hours of static ground video and 4 hours of dynamic aerial video. There are 23 event types involved.      |

### Detection

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [DroneRFa](https://data.mendeley.com/datasets/f4c2b4n755/1) | 2024     | RF signal                             | It includes 24 types of UAV signals (9 types of outdoor acquisition and 15 types of indoor acquisition) and 1 type of background signals, covering 3 ISM frequency bands. |
| [IDTDSAT](https://www.scidb.cn/en/detail?dataSetId=720626420933459968) | 2019     | Infrared image, Trajectory            | Infrared image sequence of 22 segments, total number of frames 16,177, total number of targets 16,944, 30 tracks; image resolution 256 × 256 pixels. |
| [DTDAOTRES](https://www.scidb.cn/en/detail?dataSetId=720626420979597312) | 2019     | Radar                                 | 15 segments of 8.76 GB.                                                                                     |

## UAV-oriented Datasets on Object Tracking

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [WebUAV-3M](https://github.com/983632847/WebUAV-3M)         | 2024     | Video, Text, Audio                    | 4,500 videos totaling more than 3.3 million frames with 223 target categories, providing natural language and audio descriptions. |
| [UAVDark135](https://vision4robotics.github.io/project/uavdark135/) | 2022     | Video                                 | 135 video sequences with over 125,000 manually annotated frames.                                              |
| [TNL2K](https://github.com/wangxiao5791509/TNL2K_evaluation_toolkit) | 2022     | Video, Infrared video, Text           | 2,000 video sequences, comprising 1,244,340 frames and 663 words.                                           |
| [VOT-ST2020/VOT-RT2020](https://votchallenge.net/vot2020/dataset.html) | 2020     | Video                                 | 1,000 sequences, each varying in length, with an average length of approximately 100 frames.               |
| [VOT-LT2020](https://votchallenge.net/vot2020/dataset.html) | 2020     | Video                                 | 50 sequences, each with a length of approximately 40,000 frames.                                            |
| [VOT-RGBT2020](https://votchallenge.net/vot2020/dataset.html) | 2020     | Video, Infrared video                 | 50 sequences, each with a length of approximately 40,000 frames.                                            |
| [VOT-RGBD2020](https://votchallenge.net/vot2020/dataset.html) | 2020     | Video, Depth image                    | 80 sequences with a total of approximately 101,956 frames.                                                 |
| [GOT-10K](http://got-10k.aitestunion.com/)                 | 2019     | Image, Video                          | 420 video clips belonging to 84 object categories and 31 motion categories.                                 |
| [DTB70](https://github.com/flyers/drone-tracking)           | 2017     | Video                                 | 70 video sequences, each consisting of multiple video frames, with each frame containing an RGB image at a resolution of 1280x720 pixels. |
| [Stanford Drone](https://cvgl.stanford.edu/projects/uav_data/) | 2016     | Video                                 | 19,000+ target tracks, containing 6 types of targets, about 20,000 target interactions, 40,000 target interactions with the environment, covering 100+ scenes in the university campus. |
| [COWC](https://gdo152.llnl.gov/cowc/)                      | 2016     | Image                                 | 32,716 unique vehicles and 58,247 non-vehicle targets were labeled. Covering 6 different geographical areas. |

---

## UAV-oriented Datasets on Action Recognition

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [Aeriform in-action](https://surbhi-31.github.io/Aeriform-in-action/) | 2023     | Video                                 | 32 videos, 13 types of action, 55,477 frames, 40,000 callouts.                                           |
| [MEVA](https://mevadata.org/)                               | 2021     | Video, Infrared video, GPS, Point cloud | Total 9,300 hours of video, 144 hours of activity notes, 37 activity types, over 2.7 million GPS track points. |
| [UAV-Human](https://github.com/SUTDCV/UAV-Human)            | 2021     | Video, Night-vision video, Fisheye video, Depth video, Infrared video, Skeleton | 67,428 videos (155 types of actions, 119 subjects), 22,476 frames of annotated key points (17 key points), 41,290 frames of people re-recognition (1,144 identities), 22,263 frames of attribute recognition (such as gender, hat, backpack, etc.). |
| [MOD20](https://asankagp.github.io/mod20/)                  | 2020     | Video                                 | 20 types of action, 2,324 videos, 503,086 frames.                                                         |
| [NEC-DRONE](https://www.nec-labs.com/research/media-analytics/projects/unsupervised-semi-supervised-domain-adaptation-for-action-recognition-from-drones/) | 2020     | Video                                 | 5,250 videos containing 256 minutes of action videos involving 19 actors and 16 action categories.         |
| [Drone-Action](https://asankagp.github.io/droneaction/)      | 2019     | Video                                 | 240 HD videos, 66,919 frames, 13 types of action.                                                          |
| [UAV-GESTURE](https://asankagp.github.io/uavgesture/)        | 2019     | Video                                 | 119 videos, 37,151 frames, 13 types of gestures, 10 actors.                                                |

## UAV-oriented Datasets on Navigation and Localization
| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [CityNav](https://water-cookie.github.io/city-nav-proj/)    | 2024     | Image, Text                           | 32,000 natural language descriptions and companion tracks.                                                   |
| [CNER-UAV](https://github.com/zhhvvv/CNER-UAV)              | 2024     | Text                                  | 12,000 labeled samples containing 5 types of address labels (e.g., building, unit, floor, room, etc.).       |
| [AerialVLN](https://github.com/AirVLN/AirVLN)                | 2023     | Simulator path, Text                  | 25 city-level scenes, 8,446 paths, 3 natural language descriptions per path, totaling 25,338 instructions.   |
| [DenseUAV](https://github.com/Dmmm1997/DenseUAV)            | 2023     | Image                                 | Training: 6,768 UAV images, 13,536 satellite images. Test: 2,331 UAV query images, 4,662 satellite images.    |
| [map2seq](https://map2seq.schumann.pub/dataset/download/)    | 2022     | Image, Text, Map path                 | 29,641 panoramic images, 7,672 navigation instruction texts.                                                |
| [VIGOR](https://github.com/Jeff-Zilence/VIGOR)              | 2021     | Image                                 | 90,618 aerial images, 238,696 street panorama images.                                                       |
| [University-1652](https://github.com/layumi/University1652-Baseline) | 2020     | Image                                 | 1,652 university buildings, 72 universities, 50,218 training images, 37,855 UAV query images, 701 satellite query images, and 21,099 ordinary & 5,580 street view images. |


## UAV-oriented Datasets on Transportation
| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [VisDrone](http://aiskyeye.com/home/)                       | 2022     | Video, Image                          | 263 videos, 179,264 frames. 10,209 still images. More than 2,500,000 object instance annotations. The data covers 14 different cities, covering a wide range of weather and light conditions. |
| [ITCVD](https://research.utwente.nl/en/datasets/itcvd-dataset) | 2020     | Image                                 | A total of 173 aerial images were collected, including 135 in the training set with 23,543 vehicles and 38 in the test set with 5,545 vehicles. There is 60% regional overlap between the images, and there is no overlap between the training set and the test set. |
| [UAVid](https://uavid.nl/)                                  | 2020     | Image, Video                          | 30 videos, 300 images, 8 semantic category annotations.                                                     |
| [AU-AIR](https://bozcani.github.io/auairdataset)            | 2020     | Video, GPS, Altitude, IMU, Speed      | 32,823 frames of video, 1920x1080 resolution, 30 FPS, divided into 30,000 training validation samples and 2,823 test samples. The total duration of the 8 videos is about 2 hours, with a total of 132,034 instances, distributed in 8 categories. |
| [iSAID](https://captain-whu.github.io/iSAID/)               | 2020     | Image                                 | Total images: 2,806. Total number of instances: 655,451. Test set: 935 images (not publicly labeled, used to evaluate the server). |
| [CARPK](https://lafi.github.io/LPN/)                        | 2018     | Image                                 | 1448 images, approx. 89,777 vehicles, providing box annotations.                                           |
| [highD](https://levelxdata.com/highd-dataset/)              | 2018     | Video, Trajectory                     | 16.5 hours, 110,000 vehicles, 5,600 lane changes, 45,000 km, totaling approximately 447 hours of vehicle travel data; 4 predefined driving behavior labels. |
| [UAVDT](https://sites.google.com/view/grli-uavdt/)           | 2018     | Video, Weather, Altitude, Camera angle | 100 videos, about 80,000 frames, 30 frames per second, containing 841,500 target boxes, covering 2,700 targets. |
| [CADP](https://ankitshah009.github.io/accident_forecasting_traffic_camera) | 2016     | Video                                 | A total of 5.24 hours, 1,416 traffic accident clips, 205 full-time and space annotation videos. |
| [VEDAI](https://downloads.greyc.fr/vedai)                   | 2016     | Image                                 | 1,210 images (1024 × 1024 and 512 × 512 pixels), 9 types of vehicles, containing about 6,650 targets in total. |


## UAV-oriented Datasets on Remote Sensing
| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [RET-3](https://github.com/ChenDelong1999/RemoteCLIP?utm_source=chatgpt.com) | 2024     | Image, Text                           | Approximately 13,000 samples. Including RSICD, RSITMD and UCM.                                             |
| [DET-10](https://github.com/ChenDelong1999/RemoteCLIP?utm_source=chatgpt.com) | 2024     | Image                                 | In the object detection dataset, the number of objects per image ranges from 1 to 70, totaling about 80,000 samples. |
| [SEG-4](https://github.com/ChenDelong1999/RemoteCLIP?utm_source=chatgpt.com)  | 2024     | Image                                 | The segmented data set covers different regions and resolutions, totaling about 72,000 samples.             |
| [DIOR](http://www.escience.cn/people/gongcheng/DIOR.html)   | 2020     | Image                                 | 23,463 images, containing 192,472 target instances, covering 20 categories, including aircraft, vehicles, ships, bridges, etc., each category contains about 1,200 instances. |
| [TGRS-HRRSD](https://github.com/CrazyStoneonRoad/TGRS-HRRSD-Dataset) | 2019     | Image                                 | Total images: 21,761. 13 categories, including aircraft, vehicles, bridges, etc. The total number of targets is approximately 53,000 targets. |
| [xView](https://xviewdataset.org/)                          | 2018     | Image                                 | There are more than 1 million goals and 60 categories, including vehicles, buildings, facilities, boats and so on, which are divided into seven parent categories and several sub-categories. |
| [DOTA](https://captain-whu.github.io/DOTA/)                 | 2018     | Image                                 | 2806 images, 188, 282 targets, 15 categories.                                                              |
| [RSICD](https://github.com/201528014227051/RSICD_optimal)  | 2018     | Image, Text                           | 10,921 images, 54,605 descriptive sentences.                                                                |
| [HRSC2016](http://www.escience.cn/people/liuzikun/DataSet.html) | 2017     | Image                                 | 3,433 instances, totaling 1,061 images, including 70 pure ocean images and 991 images containing mixed land-sea areas. 2,876 marked vessel targets. 610 unlabeled images. |
| [RSOD](https://github.com/RSIA-LIESMARS-WHU/RSOD-Dataset-)  | 2017     | Image                                 | Contains 4 types of targets (tank, aircraft, overpass, playground) with 12,000 positive samples and 48,000 negative samples. |
| [NWPU-RESISC45](http://pan.baidu.com/s/1mifR6tU)           | 2017     | Image                                 | A total of 31,500 images, covering 45 scene categories, 700 images per category, resolution 256 × 256 pixels, spatial resolution from 0.2m to 30m. |
| [NWPU VHR-10](https://github.com/Gaoshuaikun/NWPU-VHR-10)   | 2014     | Image                                 | 800 high-resolution images, of which 650 contain targets and 150 are background images, covering 10 categories (such as aircraft, ships, bridges, etc.), totaling more than 3,000 targets. |


## UAV-oriented Datasets on Agriculture & Industry & Emergency Response & Military & Wildlife
### Agriculture
| **Name**                                                   | **Year** | **Types**                              | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|----------------------------------------|------------------------------------------------------------------------------------------------------------|
| [WEED-2C](https://github.com/EvertonTetila/WEED2C-Dataset/?tab=readme-ov-file) | 2024     | Image                                  | Contains 4,129 labeled samples covering 2 weed species.                                                     |
| [CoFly-WeedDB](https://github.com/CoFly-Project/CoFly-WeedDB/blob/main/README.md?utm_source=chatgpt.com) | 2023     | Image, Health data                     | Consisting of 201 aerial images, different weed types of 3 disturbed row crops (cotton) and their corresponding annotated images. |
| [Avo-AirDB](https://github.com/LCSkhalid/Avo-AirDB)        | 2022     | Image                                  | 984 high-resolution RGB images (5472 × 3648 pixels), 93 of which have detailed polygonal annotations, divided into 3 to 4 categories (small, medium, large, and background). |

### Industry

| **Name**                                                   | **Year** | **Types**                              | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|----------------------------------------|------------------------------------------------------------------------------------------------------------|
| [UAPD](https://github.com/tantantetetao/UAPD-Pavement-Distress-Dataset) | 2021     | Image                                  | There are 2,401 crack images in the original data and 4,479 crack images after data enhancement.            |
| [InsPLAD](https://github.com/andreluizbvs/InsPLAD/)         | 2023     | Image                                  | 10,607 UAV images containing 17 classes of power assets with a total of 28,933 labeled instances, and defect labels for 5 assets with a total of 402 defect samples classified into 6 defect types. |

### Emergency Response

| **Name**                                                   | **Year** | **Types**                              | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|----------------------------------------|------------------------------------------------------------------------------------------------------------|
| [FloodNet](https://github.com/BinaLab/FloodNet-Supervised_v1.0) | 2021     | Image, Text                            | The whole dataset has 2,343 images, divided into training (~60%), validation (~20%), and test (~20\%) sets. The semantic segmentation labels include: Background, Building Flooded, Building Non-Flooded, Road Flooded, Road Non-Flooded, Water, Tree, Vehicle, Pool, Grass. |
| [AFID](https://purr.purdue.edu/publications/4105/1)         | 2023     | Image                                  | A total of 816 images with resolutions of 2720 × 1536 and 2560 × 1440. Contains 8 semantic segmentation categories. |
| [Aerial SAR](https://www.leadingindia.ai/data-set)          | 2020     | Image                                  | 2,000 images with 30,000 action instances covering multiple human behaviors.                               |

### Military

| **Name**                                                   | **Year** | **Types**                              | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|----------------------------------------|------------------------------------------------------------------------------------------------------------|
| [MOCO](https://github.com/Panlizhi/MOCO)                   | 2024     | Image, Text                            | 7,449 images, 37,245 captions.                                                                             |

### Wildlife

| **Name**                                                   | **Year** | **Types**                              | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|----------------------------------------|------------------------------------------------------------------------------------------------------------|
| [WAID](https://github.com/xiaohuicui/WAID)                 | 2023     | Image                                  | 14,375 UAV images covering 6 species of wildlife and multiple environment types.                           |


---

## Contributors
We want to thank the following contributors for creating, maintaining, and curating the tables in this repository:

- **Yonglin Tian** 
- **Fei Lin** 
- **Yiduo Li**
- **Tengchao Zhang**  
- **Xuan Fu**

If you have any questions about this opinionated list, please get in touch with **Yonglin Tian** 📧: [yonglin.tian@ia.ac.cn](mailto:yonglin.tian@ia.ac.cn) and **Fei Lin** 📧: [feilin@ieee.org](mailto:feilin@ieee.org).  

*(If you would like to contribute to this repo, please open an Issue or Pull Request.)*

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Hub-Tian/UAVs_Meet_LLMs&type=Date)](https://star-history.com/#Hub-Tian/UAVs_Meet_LLMs&Date)

---

## Citation
If you find this repository useful, please consider citing this paper:

```bibtex
@misc{tian2024uavs_meet_llms,
      title={UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility}, 
      author={
        Yonglin Tian and 
        Fei Lin and 
        Yiduo Li and 
        Tengchao Zhang and 
        Qiyao Zhang and 
        Xuan Fu and 
        Jun Huang and 
        Xingyuan Dai and 
        Yisheng Lv and 
        Fei-Yue Wang
      },
      year={2025},
      note={Under review / In preparation},
}
```
 
---

## License
This project is licensed under the [MIT License](LICENSE).


