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
- **[2024-12-27]** [Yiduo Li](https://github.com/Leeeufo02) added the content of the dataset section
- **[2024-12-27]** [Fei Lin](https://github.com/linfei-mise) and [Yonglin Tian](https://github.com/Hub-Tian) curated this list and published the first version.

> If you have any questions or suggestions, please feel free to open an [issue](https://github.com/Hub-Tian/UAVs_Meet_LLMs/issues) or contact us via [email](yonglin.tian@ia.ac.cn).

---

## Introduction
This repository accompanies our work on **"UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility"**.  
Here, we primarily store various **tables** referenced in the survey/overview paper. These tables focus on:

- Summarization of typical **LLMs, VLMs, and VFMs**  
- Awesome works on **Fundation Models based UAV Systems**  
- **UAV-oriented Datasets** across multiple application domains

> **Note**: The goal is to provide a structured, easy-to-navigate resource for researchers interested in the intersection of UAVs and Large Language Models.

---

## Table of Contents

- [Preliminaries for UAVs](#preliminaries-for-uavs)
  - [Typical configurations of UAV](#typical-configurations-of-uav)
  - [UAV Swarm Path Planning Method](#uav-swarm-path-planning-method)
  - [UAV Swarm Task Allocation](#uav-swarm-task-allocation)
  - [UAV Swarm Communication architecture](#uav-swarm-communication-architecture)
  - [UAV Swarm Formation Control Algorithm](#uav-swarm-formation-control-algorithm)

- [Summarization of LLMs, VLMs, and VFMs](#summarization-of-llms-vlms-and-vfms)
  - [LLMs](#llms)
  - [VLMs](#vlms)
  - [VFMs](#vfms)

- [General-domain Datasets for UAV](#general-domain-datasets-for-uav)
  - [Environmental Perception](#environmental-perception)
  - [Event Recognition](#event-recognition)
  - [Object Tracking](#object-tracking)
  - [Action Recognition](#action-recognition)
  - [Navigation and Localization](#navigation-and-localization)

- [Domain-specific Datasets for UAV](#domain-specific-datasets-for-uav)
  - [Transportation](#transportation)
  - [Remote Sensing](#remote-sensing)
  - [Agriculture](#agriculture)
  - [Industry](#industry)
  - [Emergency Response](#emergency-response)
  - [Military](#military)
  - [Wildlife](#wildlife)
  - [Drone Detection](#drone-detection)

- [Open Platforms for UAVs](#open-platforms-for-uavs)

- [Summary of Methods and Models](#summary-of-methods-and-models)
  - [Visual Perception](#visual-perception)
  - [VLN](#vln)
  - [Planning](#planning)
  - [Flight Control](#flight-control)
  - [Infrastructures](#infrastructures)

---
## Preliminaries for UAVs

### Typical configurations of UAV

| **Category**           | **Characteristics**                                                                             | **Advantages**                                             | **Disadvantages**                                      |
|------------------------|-------------------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------|
| **Fixed-wing UAV**      | Fixed wings generate lift with forward motion.                                                  | High speed, long endurance, stable flight.                 | Cannot hover, high demands for takeoff/landing areas.   |
| **Multirotor UAV**      | Multiple rotors provide lift and control.                                                      | Low cost, easy operation, capable of VTOL and hovering.    | Limited flight time, low speed, small payload capacity. |
| **Unmanned Helicopter** | Single or dual rotors allow vertical take-off and hovering.                                    | High payload capacity, good wind resistance, long endurance, VTOL. | Complex structure, higher maintenance cost, slower than fixed-wing UAVs. |
| **Hybrid UAV**          | Combines fixed-wing and multirotor capabilities.                                                | Flexible missions, long endurance, VTOL.                   | Complex mechanisms, higher cost.                       |
| **Flapping-wing UAV**   | Uses clap-and-fling mechanism for flight.                                                      | Low noise, high propulsion efficiency, high maneuverability. | Complex analysis and control, limited payload capacity. |
| **Unmanned Airship**    | Aerostat aircraft with gasbag for lift.                                                         | Low cost, low noise.                                      | Low speed, low maneuverability, highly affected by wind. |

### UAV Swarm Path Planning Method

|               **Category**               |            **Examples**           | **References**                                                                 |
|:----------------------------------------:|:--------------------------------:|:--------------------------------------------------------------------------------:|
| **Intelligent optimization algorithm** |       Ant Colony Algorithm       | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5498477)        |
|                                          |         Genetic Algorithm        | [Ref](https://www.worldscientific.com/doi/abs/10.1142/S0218213017600089)     |
|                                          |   Simulated Annealing Algorithm  | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8483993)        |
| **Mathematical programming**           | mixed integer linear programming | [Ref](https://journals.sagepub.com/doi/abs/10.1177/0954410015609361)          |
|                                          |       nonlinear programming      | [Ref](https://arc.aiaa.org/doi/abs/10.2514/6.2006-6199)                      |
| **AI based method**                    |           Deep Learning          | [Ref](https://www.sciencedirect.com/science/article/abs/pii/S1270963820311172?via%3Dihub) |
|                                          |      Reinforcement Learning      | [Ref](https://doi.org/10.1016/j.ast.2021.107052)                             |


### UAV Swarm Task Allocation

| **Category**                      | **Examples**                            | **References**                                                                                   |
|:----------------------------------:|:---------------------------------------:|:------------------------------------------------------------------------------------------------:|
| **Heuristic Algorithm**          | Particle Swarm Optimization Algorithm   | [Ref](https://arc.aiaa.org/doi/abs/10.2514/6.2008-6837)                                      |
|                                    | Genetic Algorithm                       | [Ref](https://ieeexplore.ieee.org/abstract/document/9483937)                                  |
|                                    | Simulated Annealing Algorithm           | [Ref](https://iopscience.iop.org/article/10.1088/1742-6596/2246/1/012081/meta)                |
| **AI Based Algorithm**           | Reinforcement Learning                  | [Ref](https://doi.org/10.1016/j.ast.2019.06.024)                                              |
|                                    | Artificial Neural Network               | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670550)                      |
| **Mathematical Programming Methods** | Mixed Integer Programming              | [Ref](https://doi.org/10.2514/6.2004-6410)                                                   |
| **Market Mechanism Based Method** | Auction Based Algorithm                 | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7813107)                       |
|                                    | Consensus Based Bundle Algorithm        | [Ref](https://doi.org/10.3390/s20082307)                                                     |
|                                    | Contract Net Protocol                   | [Ref](https://doi.org/10.3390/s22124486)                                                     |

### UAV Swarm Communication architecture

|                **Category**               |                      **References**                      |
|:-----------------------------------------:|:--------------------------------------------------------:|
|     infrastructure-based architectures    | [Ref](https://und.edu/research/rias/_files/docs/swarm_ieee.pdf) |
| Flying Ad-hoc Network (FANET) Architectur | [Ref](https://doi.org/10.1016/j.adhoc.2012.12.004)              |

### UAV Swarm Formation Control Algorithm

|            **Category**            |                  **Example**                 |                                  **References**                                 |
|:----------------------------------:|:--------------------------------------------:|:-------------------------------------------------------------------------------:|
| **Centralized Control**   |               Virtual Structure              |     [Ref](https://ascelibrary.org/doi/abs/10.1061/(ASCE)AS.1943-5525.0000351)          |
|                                    |           Leader-Follower Approaches         |     [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=680621)             |
| **Decentralized Control** |     Decentralized Model Prediction Method    | [Ref](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=1429425)                |
| **Distributed Control**   |                Behavior Method               |     [Ref](https://intapi.sciendo.com/pdf/10.1515/ama-2016-0015)                        |
|                                    |               Consistency Method             | [Ref](https://doi.org/10.3390/drones7030185)                                           |

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
|                       | DINO                                  | [Zhang et al.](https://github.com/IDEA-Research/DINO)                   |
|                       | Grounding-DINO                        | [Liu et al.](https://github.com/IDEA-Research/GroundingDINO)            |
|                       | DINOv2                                | [Meta AI Research](https://github.com/facebookresearch/dinov2)          |
|                       | AM-RADIO                              | [NVIDIA](https://github.com/NVlabs/RADIO)                               |
|                       | DINO-WM                               | [Zhou et al.](https://dino-wm.github.io/)                               |
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
|                       | SEEM                                  | [Zou et al.](https://github.com/UX-Decoder/Segment-Everything-Everywhere-All-At-Once)   |
|                       | Seal                                  | [Liu et al.](https://github.com/youquanl/Segment-Any-Point-Cloud)        |
|                       | LISA                                  | [Lai et al.](https://github.com/dvlabresearch/LISA)                      |
| **Depth Estimation**  | ZoeDepth                              | [Bhat et al.](https://github.com/isl-org/ZoeDepth)                       |
|                       | ScaleDepth                            | [Zhu et al.](https://ruijiezhu94.github.io/ScaleDepth/)                  |
|                       | Depth Anything                        | [Yang et al.](https://depth-anything.github.io)                          |
|                       | Depth Anything V2                     | [Yang et al.](https://depth-anything-v2.github.io/)                      |
|                       | Depth Pro                             | [Apple](https://github.com/apple/ml-depth-pro)                           |

## General-domain Datasets for UAV

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


### Object Tracking

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

### Action Recognition

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [Aeriform in-action](https://surbhi-31.github.io/Aeriform-in-action/) | 2023     | Video                                 | 32 videos, 13 types of action, 55,477 frames, 40,000 callouts.                                           |
| [MEVA](https://mevadata.org/)                               | 2021     | Video, Infrared video, GPS, Point cloud | Total 9,300 hours of video, 144 hours of activity notes, 37 activity types, over 2.7 million GPS track points. |
| [UAV-Human](https://github.com/SUTDCV/UAV-Human)            | 2021     | Video, Night-vision video, Fisheye video, Depth video, Infrared video, Skeleton | 67,428 videos (155 types of actions, 119 subjects), 22,476 frames of annotated key points (17 key points), 41,290 frames of people re-recognition (1,144 identities), 22,263 frames of attribute recognition (such as gender, hat, backpack, etc.). |
| [MOD20](https://asankagp.github.io/mod20/)                  | 2020     | Video                                 | 20 types of action, 2,324 videos, 503,086 frames.                                                         |
| [NEC-DRONE](https://www.nec-labs.com/research/media-analytics/projects/unsupervised-semi-supervised-domain-adaptation-for-action-recognition-from-drones/) | 2020     | Video                                 | 5,250 videos containing 256 minutes of action videos involving 19 actors and 16 action categories.         |
| [Drone-Action](https://asankagp.github.io/droneaction/)      | 2019     | Video                                 | 240 HD videos, 66,919 frames, 13 types of action.                                                          |
| [UAV-GESTURE](https://asankagp.github.io/uavgesture/)        | 2019     | Video                                 | 119 videos, 37,151 frames, 13 types of gestures, 10 actors.                                                |

### Navigation and Localization

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [CityNav](https://water-cookie.github.io/city-nav-proj/)    | 2024     | Image, Text                           | 32,000 natural language descriptions and companion tracks.                                                   |
| [CNER-UAV](https://github.com/zhhvvv/CNER-UAV)              | 2024     | Text                                  | 12,000 labeled samples containing 5 types of address labels (e.g., building, unit, floor, room, etc.).       |
| [AerialVLN](https://github.com/AirVLN/AirVLN)                | 2023     | Simulator path, Text                  | 25 city-level scenes, 8,446 paths, 3 natural language descriptions per path, totaling 25,338 instructions.   |
| [DenseUAV](https://github.com/Dmmm1997/DenseUAV)            | 2023     | Image                                 | Training: 6,768 UAV images, 13,536 satellite images. Test: 2,331 UAV query images, 4,662 satellite images.    |
| [map2seq](https://map2seq.schumann.pub/dataset/download/)    | 2022     | Image, Text, Map path                 | 29,641 panoramic images, 7,672 navigation instruction texts.                                                |
| [VIGOR](https://github.com/Jeff-Zilence/VIGOR)              | 2021     | Image                                 | 90,618 aerial images, 238,696 street panorama images.                                                       |
| [University-1652](https://github.com/layumi/University1652-Baseline) | 2020     | Image                                 | 1,652 university buildings, 72 universities, 50,218 training images, 37,855 UAV query images, 701 satellite query images, and 21,099 ordinary & 5,580 street view images. |


## Domain-specific Datasets for UAV

### Transportation

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


### Remote Sensing

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

### Drone Detection

| **Name**                                                   | **Year** | **Types**                             | **Amount**                                                                                                 |
|------------------------------------------------------------|----------|---------------------------------------|------------------------------------------------------------------------------------------------------------|
| [DroneRFa](https://data.mendeley.com/datasets/f4c2b4n755/1) | 2024     | RF signal                             | It includes 24 types of UAV signals (9 types of outdoor acquisition and 15 types of indoor acquisition) and 1 type of background signals, covering 3 ISM frequency bands. |
| [IDTDSAT](https://www.scidb.cn/en/detail?dataSetId=720626420933459968) | 2019     | Infrared image, Trajectory            | Infrared image sequence of 22 segments, total number of frames 16,177, total number of targets 16,944, 30 tracks; image resolution 256 × 256 pixels. |
| [DTDAOTRES](https://www.scidb.cn/en/detail?dataSetId=720626420979597312) | 2019     | Radar                                 | 15 segments of 8.76 GB.                                                                                     |

## Open Platforms for UAVs

| **Name**                                                   | **Paper**                                                        |
|------------------------------------------------------------|------------------------------------------------------------------|
| [AirSim](https://microsoft.github.io/AirSim/) | Airsim: High-fidelity visual and physical simulation for autonomous vehicles |
| [Carla](https://carla.org/) | CARLA: An open urban driving simulator |
| [NVIDIA Isaac Sim](https://developer.nvidia.com/isaac/sim) |  |
| [AerialVLN Simulator](https://github.com/AirVLN/AirVLN) | Aerialvln: Vision-and-language navigation for uavs |
| [Embodied City](https://embodied-city.fiblab.net/) | EmbodiedCity: A Benchmark Platform for Embodied Agent in Real-world City Environment |

## Summary of Methods and Models

### Visual Perception

| Title              | Type         | Publication        | Code            |
|--------------------|-------------|--------------------|-----------------|
| Li et al. (A Benchmark for UAV-View Natural Language-Guided Tracking)       | VFM         | [ _MDPI_ ](https://www.mdpi.com/2079-9292/13/9/1706)      | [ _GitHub_ ](https://github.com/Lich-King000/UAVNLT)  |
| Ma et al. (Applying Unsupervised Semantic Segmentation to High-Resolution UAV Imagery for Enhanced Road Scene Parsing)       | VFM         | [ _Arxiv_ ](https://arxiv.org/abs/2402.02985)      | - |
| Limberg et al. (Leveraging YOLO-World and GPT-4V LMMs for Zero-Shot Person Detection and Action Recognition in Drone Imagery)  | VFM+VLM     | [ _Arxiv_ ](https://arxiv.org/abs/2404.01571)      | - |
| Kim et al. (Weather-Aware Drone-View Object Detection Via Environmental Context Understanding)      | VLM+VFM     | [ _ICIP 2024_ ](https://ieeexplore.ieee.org/abstract/document/10647388?casa_token=5WOlhDhGgSMAAAAA:nwp96nnFaZE9U3t5XnZmLPYr9f3Lw1YUKx6w4qyKx5F6Gzwa9uwmMUsKc2IX6gdvomLZ7Dcf9l9u)      | - |
| LGNet (Shooting condition insensitive unmanned aerial vehicle object detection)           | VFM         | [ _Expert Systems with Applications_ ](https://www.sciencedirect.com/science/article/pii/S0957417424000861?casa_token=3A-yp3URHJ4AAAAA:MHJXhYWUpX_mZMUggAo5oSa9FxpJsYdqbo940lZj-gfb5XuPOHAEdMQ1ZiyTEXir1kQUfjQMRA)      | - |
| Sakaino et al. (Dynamic Texts From UAV Perspective Natural Images)  | VLM+VFM     | [ _ICCV 2023_ ](https://openaccess.thecvf.com/content/ICCV2023W/OpenSUN3D/html/Sakaino_Dynamic_Texts_From_UAV_Perspective_Natural_Images_ICCVW_2023_paper.html)      | -  |
| COMRP (Unsupervised semantic segmentation of high-resolution UAV imagery for road scene parsing)           | VFM         | [ _Arxiv_ ](https://arxiv.org/abs/2402.02985)      | [ _GitHub_ ](https://github.com/CHDyshli/unsupervised-road-parsing)  |
| CrossEarth (CrossEarth: Geospatial Vision Foundation Model for Domain Generalizable Remote Sensing Semantic Segmentation)      | VFM         | [ _Arxiv_ ](https://arxiv.org/abs/2410.22629)      | [ _GitHub_ ](https://github.com/Cuzyoung/CrossEarth)  |
| TanDepth (TanDepth: Leveraging Global DEMs for Metric Monocular Depth Estimation in UAVs)        | VFM         | [ _Arxiv_ ](https://arxiv.org/abs/2409.05142)      | [ _GitHub_ ](https://github.com/hrflr/uavid-3d-scenes)  |
| DroneGPT (DroneGPT: Zero-shot Video Question Answering For Drones)        | VLM+LLM+VFM | [ _CVDL 2024_ ](https://dl.acm.org/doi/abs/10.1145/3653804.3654608?casa_token=CtmHh5WiSTQAAAAA:3D70U8Z_CHJ1jrx9u4zduBfCi91JI3lFGVA3ZhCDQVOgEcSEaYuzGxKLWHX7fE6a3YviSkjat4mPug)      | - |
| de Zarzà et al. (Socratic video understanding on unmanned aerial vehicles) | LLM         | [ _Procedia Computer Science_ ](https://www.sciencedirect.com/science/article/pii/S1877050923011560)      | - |
| AeroAgent (Agent as Cerebrum, Controller as Cerebellum: Implementing an Embodied LMM-based Agent on Drones)       | VLM         | [ _Arxiv_ ](https://arxiv.org/abs/2311.15033)      | -  |
| RS-LLaVA (Rs-llava: A large vision-language model for joint captioning and question answering in remote sensing imagery)        | VLM         | [ _MDPI_ ](https://www.mdpi.com/2072-4292/16/9/1477)      | -  |
| GeoRSCLIP (RS5M and GeoRSCLIP: A large scale vision-language dataset and a large vision-language model for remote sensing)       | VFM         | [ _IEEE Transactions on Geoscience and Remote Sensing_ ](https://ieeexplore.ieee.org/abstract/document/10679571?casa_token=TyNG8Ytg_mIAAAAA:byAkV0_chtOVtdNjFaTmNA3EZIMH-cLQ38SP-CmAFrKcoPRyuNCx9DGqq54f1kOb32g7I3P5rHxRDw)      | [ _GitHub_ ](https://github.com/om-ai-lab/RS5M)  |
| SkyEyeGPT (Skyeyegpt: Unifying remote sensing vision-language tasks via instruction tuning with large language model)       | VFM+LLM     | [ _Arxiv_ ](https://arxiv.org/abs/2401.09712)      | [ _GitHub_ ](https://github.com/ZhanYang-nwpu/SkyEyeGPT)  |

### VLN

| Title                | Type         | Publication       | Code           |
|----------------------|-------------:|-------------------|----------------|
| NaVid (Navid: Video-based vlm plans the next step for vision-and-language navigation)            | VFM+LLM       | [ _Arxiv_ ](https://arxiv.org/abs/2402.15852)     | - |
| VLN-MP (Why Only Text: Empowering Vision-and-Language Navigation with Multi-modal Prompts)           | VFM           | [ _Arxiv_ ](https://arxiv.org/abs/2406.02208)     | [ _GitHub_ ](https://github.com/honghd16/VLN-MP) |
| Gao et al. (Aerial Vision-and-Language Navigation via Semantic-Topo-Metric Representation Guided LLM Reasoning)       | VFM+LLM       | [ _Arxiv_ ](https://arxiv.org/abs/2410.08500)     | - |
| MGP (CityNav: Language-Goal Aerial Navigation Dataset with Geographic Information)              | LLM+VFM       | [ _Arxiv_ ](https://arxiv.org/abs/2406.14240)     | [ _GitHub_ ](https://github.com/water-cookie/citynav) |
| UAV Navigation LLM (Towards Realistic UAV Vision-Language Navigation: Platform, Benchmark, and Methodology) | LLM+VFM     | [ _Arxiv_ ](https://arxiv.org/abs/2410.07087)     | [ _GitHub_ ](https://prince687028.github.io/OpenUAV/) |
| GOMAA-Geo (GOMAA-Geo: GOal Modality Agnostic Active Geo-localization)        | LLM+VFM       | [ _Arxiv_ ](https://arxiv.org/abs/2406.01917)     | [ _GitHub_ ](https://github.com/mvrl/GOMAA-Geo/tree/main) |
| NavAgent (NavAgent: Multi-scale Urban Street View Fusion For UAV Embodied Vision-and-Language Navigation)         | LLM+VFM+VLM   | [ _Arxiv_ ](https://arxiv.org/abs/2411.08579)     | - |
| ASMA (ASMA: An Adaptive Safety Margin Algorithm for Vision-Language Drone Navigation via Scene-Aware Control Barrier Functions)             | LLM+VFM       | [ _Arxiv_ ](https://arxiv.org/abs/2409.10283)     | - |
| Zhang et al. (Demo Abstract: Embodied Aerial Agent for City-level Visual Language Navigation Using Large Language Model)     | VFM+LLM       | [ _IPSN 2024_ ](https://ieeexplore.ieee.org/abstract/document/10577302?casa_token=n2FU0mxrCvoAAAAA:E86JlA4m98x2f09d0VZ5199dx8gH-kxUfVA2LU7rjWd5s4alCDoQdHH67Vc5gbhnSI_W1tQNjdpHLA)     | - |
| Chen et al. (Vision-Language Navigation for Quadcopters with Conditional Transformer and Prompt-based Text Rephraser)      | LLM           | [ _MMAsia 2023_ ](https://dl.acm.org/doi/abs/10.1145/3595916.3626450?casa_token=fGnueKEkiZsAAAAA:roEaZ3SHZ8UW9-i2vy_5pv_mwLlDVv4cL-MHxuGNQCKlOg9PuaX_vsUZ6WiRz4lOnJbCq-DxKycZGg)     | - |
| CloudTrack (CloudTrack: Scalable UAV Tracking with Cloud Semantics)       | VFM+VLM       | [ _Arxiv_ ](https://arxiv.org/abs/2409.16111)     | - |
| NEUSIS (NEUSIS: A Compositional Neuro-Symbolic Framework for Autonomous Perception, Reasoning, and Planning in Complex UAV Search Missions)           | VFM+VLM       | [ _Arxiv_ ](https://arxiv.org/abs/2409.10196)     | - |
| Say-REAPEx (Say-REAPEx: An LLM-Modulo UAV Online Planning Framework for Search and Rescue)       | LLM           | [ _Openreview_ ](https://openreview.net/forum?id=9WdUqvE03f)     | - |

### Planning

| Title          | Type         | Publication       | Code           |
|----------------|-------------:|-------------------|----------------|
| TypeFly (Typefly: Flying drones with large language model)     | LLM          | [ _Arxiv_ ](https://arxiv.org/abs/2312.14950)     | - |
| SPINE (SPINE: Online Semantic Planning for Missions with Incomplete Natural Language Specifications in Unstructured Environments)       | LLM+VFM+VLM  | [ _Arxiv_ ](https://arxiv.org/abs/2410.03035)     | - |
| LEVIOSA (LEVIOSA: Natural Language-Based Uncrewed Aerial Vehicle Trajectory Generation)     | LLM          | [ _MDPI_ ](https://www.mdpi.com/2079-9292/13/22/4508)     | [ _GitHub_ ](https://github.com/sesem738/Leviosa) |
| TPML (TPML: Task Planning for Multi-UAV System with Large Language Models)        | LLM          | [ _ICCA 2023_ ](https://ieeexplore.ieee.org/abstract/document/10591846?casa_token=xa1KFvlHFzUAAAAA:LBGOwvV_4iUcNLewToZCjFnr5aIUnReWyTvKyZsuY_nnGsk_eh8u1TW6MHpQ1NEF5pO-VPzAVovAuHA)     | - |
| REAL (Real: Resilience and adaptation using large language models on autonomous aerial robots)        | LLM          | [ _Arxiv_ ](https://arxiv.org/abs/2311.01403)     | - |
| Liu et al. (Multi-Agent Formation Control Using Large Language Models)  | LLM          | [ _Techrxiv_ ](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172954477.70259514)     | - |

### Flight Control

| Title             | Type | Publication       | Code           |
|-------------------|-----:|-------------------|----------------|
| PromptCraft (Chatgpt for robotics: Design principles and model abilities)    | LLM  | [ _IEEE Access_ ](https://ieeexplore.ieee.org/abstract/document/10500490)     | [ _GitHub_ ](https://github.com/microsoft/PromptCraft-Robotics) |
| Zhong et al. (A safer vision-based autonomous planning system for quadrotor uavs with dynamic obstacle trajectory prediction and its application with llms)   | LLM  | [ _WACV 2024_ ](https://openaccess.thecvf.com/content/WACV2024W/LLVM-AD/html/Zhong_A_Safer_Vision-Based_Autonomous_Planning_System_for_Quadrotor_UAVs_With_WACVW_2024_paper.html)     | - |
| Tazir et al. (From words to flight: Integrating openai chatgpt with px4/gazebo for natural language-based drone control)   | LLM  | [ _WCSE 2023_ ](https://www.researchgate.net/profile/Mohamed-Lamine-Tazir/publication/372028642_From_Words_to_Flight_Integrating_OpenAI_ChatGPT_with_PX4Gazebo_for_Natural_Language-Based_Drone_Control/links/64a2ef5295bbbe0c6e0dda04/From-Words-to-Flight-Integrating-OpenAI-ChatGPT-with-PX4-Gazebo-for-Natural-Language-Based-Drone-Control.pdf)     | - |
| Phadke et al. (Integrating Large Language Models for UAV Control in Simulated Environments: A Modular Interaction Approach)  | LLM  | [ _Arxiv_ ](https://arxiv.org/abs/2410.17602)     | - |
| EAI-SIM (EAI-SIM: An Open-Source Embodied AI Simulation Framework with Large Language Models)        | LLM  | [ _ICCA 2024_ ](https://ieeexplore.ieee.org/abstract/document/10591865?casa_token=Q8xpKHwtDaAAAAAA:d8MNPpg5Q86ZlC9NkMcbPOZ58K_ZewmAHOOjC8KTgHL6VODSyYUdhoQUcOHyUOLl6NH79L_fkcBxa6Y)     | [ _GitHub_ ](https://github.com/PengICS/eai_sim) |
| TAIiST (TAIiST CPS-UAV at the SBFT Tool Competition 2024)         | LLM  | [ _SBFT 2024_ ](https://dl.acm.org/doi/abs/10.1145/3643659.3643936)     | [ _GitHub_ ](https://github.com/Trusted-AI-in-System-Test) |
| Swarm-GPT (Swarm-gpt: Combining large language models with safe motion planning for robot choreography design)      | LLM  | [ _Arxiv_ ](https://www.dynsyslab.org/wp-content/papercite-data/pdf/jiao-neurips23.pdf)     | - |
| FlockGPT (FlockGPT: Guiding UAV Flocking with Linguistic Orchestration)       | LLM  | [ _Arxiv_ ](https://arxiv.org/abs/2405.05872)     | - |
| CLIPSwarm (CLIPSwarm: Generating Drone Shows from Text Prompts with Vision-Language Models)      | VFM  | [ _Arxiv_ ](https://arxiv.org/abs/2403.13467)     | - |

### Infrastructures

| Title             | Type    | Publication       | Code           |
|-------------------|--------:|-------------------|----------------|
| DTLLM-VLT (DTLLM-VLT: Diverse Text Generation for Visual Language Tracking Based on LLM)      | VFM+LLM | [ _CVPR 2024_ ](https://openaccess.thecvf.com/content/CVPR2024W/VDU/html/Li_DTLLM-VLT_Diverse_Text_Generation_for_Visual_Language_Tracking_Based_on_CVPRW_2024_paper.html)     | - |
| Yao et al. (Can llm substitute human labeling? a case study of fine-grained chinese address entity recognition dataset for uav delivery)     | LLM     | [ _Companion Proceedings of the ACM Web Conference 2024_ ](https://dl.acm.org/doi/abs/10.1145/3589335.3651446?casa_token=mJzJVbxcOSUAAAAA:TUrPUIvFd7m7-LyBbn0UZ2-8ZuOgdUUGTHO3-TvQj1zrdd_HqIcz_Zbud7NuS8n6aVSKNM6pr3d3ue0)     | [ _GitHub_ ](https://github.com/zhhvvv/CNER-UAV) |
| GPG2A (Cross-View Meets Diffusion: Aerial Image Synthesis with Geometry and Text Guidance)          | LLM     | [ _Arxiv_ ](https://arxiv.org/abs/2408.04224)     | [ _GitLap_ ](https://gitlab.com/vail-uvm/GPG2A) |
| AeroVerse (AeroVerse: UAV-Agent Benchmark Suite for Simulating, Pre-training, Finetuning, and Evaluating Aerospace Embodied World Models)      | VLM+LLM | [ _Arxiv_ ](https://arxiv.org/abs/2408.15511)     | - |
| Tang et al. (Defining and Evaluating Physical Safety for Large Language Models)    | LLM     | [ _Arxiv_ ](https://arxiv.org/abs/2411.02317)     | [ _Hugging face_ ](https://huggingface.co/datasets/TrustSafeAI/llm_physical_safety_benchmark) |
| Xu et al. (Emergency Networking Using UAVs: A Reinforcement Learning Approach with Large Language Model)      | LLM     | [ _IPSN 2024_ ](https://ieeexplore.ieee.org/abstract/document/10577381?casa_token=Mmd9-ZDptTUAAAAA:q6shHGKcyH-748YODzx40WlYoLaswZcNK9Ik0z741pTnZX1inG9G0nQm5eBuaMnUl7T9eGgBdszs)     | - |
| LLM-RS (Real-time Integration of Fine-tuned Large Language Model for Improved Decision-Making in Reinforcement Learning)         | LLM     | [ _IJCNN 2024_ ](https://ieeexplore.ieee.org/abstract/document/10650538?casa_token=nT06OMN91ZEAAAAA:rqTAbczP0wz615qxgPtIitMnscaFSUoA_Vs5hJ58uiVGXu4gNEqntpK9AfYfVXq89-JsZsIO_Vfh)     | - |
| Pineli et al. (Evaluating Voice Command Pipelines for Drone Control: From STT and LLM to Direct Classification and Siamese Networks)  | LLM     | [ _Arxiv_ ](https://arxiv.org/abs/2407.08658)     | - |

## Contributors
We want to thank the following contributors for creating, maintaining, and curating the tables in this repository:

- **Yonglin Tian** 
- **Fei Lin** 
- **Yiduo Li**
- **Tengchao Zhang**  
- **Xuan Fu**

If you have any questions about this repository, feel free to get in touch with **Yonglin Tian** [📧](mailto:yonglin.tian@ia.ac.cn) or **Fei Lin** [📧](mailto:feilin@ieee.org).  

*(If you would like to contribute to this repo, please open an Issue or Pull Request.)*

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Hub-Tian/UAVs_Meet_LLMs&type=Date)](https://star-history.com/#Hub-Tian/UAVs_Meet_LLMs&Date)

---

## Citation
If you find this repository useful, please consider citing this paper:

```bibtex
@misc{tian2025uavs_meet_llms,
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
    Yutong Wang and
    Chunwei Tian and
    Bai Li and
    Yisheng Lv and
    Levente Kovács and
    Fei-Yue Wang
  },
  year={2025},
  note={Under review / In preparation},
}
```
 
---

## License
This project is licensed under the [MIT License](LICENSE).


