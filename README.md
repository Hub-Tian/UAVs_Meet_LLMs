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
- [Summary of Methods and Models](#summary-of-methods-and-models)
- [UAV-oriented Datasets on Environmental Perception & Event Recognition & Detection](#uav-oriented-datasets-on-environmental-perception--event-recognition--detection)
- [UAV-oriented Datasets on Object Tracking](#uav-oriented-datasets-on-object-tracking)
- [UAV-oriented Datasets on Action Recognition](#uav-oriented-datasets-on-action-recognition)
- [UAV-oriented Datasets on Navigation and Localization](#uav-oriented-datasets-on-navigation-and-localization)
- [UAV-oriented Datasets on Transportation](#uav-oriented-datasets-on-transportation)
- [UAV-oriented Datasets on Remote Sensing](#uav-oriented-datasets-on-remote-sensing)
- [UAV-oriented Datasets on Agriculture & Industry & Emergency Response & Military & Wildlife](#uav-oriented-datasets-on-agriculture--industry--emergency-response--military--wildlife)

---

## Summarization of LLMs, VLMs, and VFMs

| **Category** | **Subcategory**         | **Model Name**                                                 | **Institution / Author**                                                                              |
|:------------:|:-----------------------:|:--------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------:|
| **LLMs**     | **General**            | GPT-3, GPT-3.5, GPT-4                                          | [OpenAI](https://openai.com)                                                                          |
|              |                         | Claude 2, Claude 3                                             | [Anthropic](https://www.anthropic.com)                                                                |
|              |                         | Mistral series                                                 | [Mistral AI](https://www.mistral.ai)                                                                  |
|              |                         | PaLM series, Gemini series                                     | [Google Research](https://ai.google)                                                                  |
|              |                         | LLaMA, LLaMA2, LLaMA3                                          | [Meta AI](https://ai.meta.com)                                                                        |
|              |                         | Vicuna                                                         | [Vicuna Team](https://vicuna.lmsys.org)                                                               |
|              |                         | Qwen series                                                    | [Qwen Team, Alibaba Group](https://github.com/QwenLM)                                                 |
|              |                         | InternLM                                                       | [Shanghai AI Laboratory](https://github.com/InternLM/InternLM)                                        |
|              |                         | BuboGPT                                                        | [Bytedance](https://github.com/magic-research/bubogpt)                                                |
|              |                         | ChatGLM                                                        | [Zhipu AI](https://github.com/THUDM)                                                                  |
|              |                         | DeepSeek series                                               | [DeepSeek](https://github.com/deepseek-ai)                                                            |
| **VLMs**     | **General**            | GPT-4V, GPT-4o, GPT-4o mini, GPT o1-preview                    | [OpenAI](https://openai.com)                                                                          |
|              |                         | Claude 3 Opus, Claude 3.5 Sonnet                               | [Anthropic](https://www.anthropic.com)                                                                |
|              |                         | Step-2                                                         | [Jieyue Xingchen](https://www.stepfun.com/)                                                           |
|              |                         | LLaVA, LLaVA-1.5, LLaVA-NeXT                                   | [Liu et al.](https://github.com/haotian-liu/LLaVA)                                                    |
|              |                         | MoE-LLaVA                                                      | [Lin et al.](https://github.com/PKU-YuanGroup/MoE-LLaVA)                                              |
|              |                         | LLaVA-CoT                                                      | [Xu et al.](https://github.com/PKU-YuanGroup/LLaVA-CoT)                                               |
|              |                         | Flamingo                                                       | [Alayrac et al.](https://github.com/mlfoundations/open_flamingo)                                      |
|              |                         | BLIP                                                           | [Li et al.](https://github.com/salesforce/BLIP)                                                       |
|              |                         | BLIP-2                                                         | [Li et al.](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)                             |
|              |                         | InstructBLIP                                                   | [Dai et al.](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)                     |
|              | **Video Understanding** | LLaMA-VID                                                     | [Li et al.](https://github.com/dvlab-research/LLaMA-VID)                                              |
|              |                         | IG-VLM                                                         | [Kim et al.](https://github.com/imagegridworth/IG-VLM)                                                |
|              |                         | Video-ChatGPT                                                  | [Maaz et al.](https://github.com/mbzuai-oryx/Video-ChatGPT)                                           |
|              |                         | VideoTree                                                      | [Wang et al.](https://github.com/Ziyang412/VideoTree)                                                 |
|              | **Visual Reasoning**    | X-VLM                                                          | [Zeng et al.](https://github.com/zengyan-97/X-VLM)                                                    |
|              |                         | Chameleon                                                      | [Lu et al.](https://chameleon-llm.github.io/)                                                         |
|              |                         | HYDRA                                                          | [Ke et al.](https://hydra-vl4ai.github.io/)                                                           |
|              |                         | VISPROG                                                        | [PRIOR @ Allen Institute for AI](https://prior.allenai.org/projects/visprog)                          |
| **VFMs**     | **General**            | CLIP                                                           | [OpenAI](https://github.com/OpenAI/CLIP)                                                              |
|              |                         | FILIP                                                          | Yao et al.                                                                                             |
|              |                         | RegionCLIP                                                     | [Microsoft Research](https://github.com/microsoft/RegionCLIP)                                         |
|              |                         | EVA-CLIP                                                       | [Sun et al.](https://github.com/baaivision/EVA/tree/master/EVA-CLIP)                                  |
|              | **Object Detection**    | GLIP                                                           | [Microsoft Research](https://github.com/microsoft/GLIP)                                               |
|              |                         | DINO                                                           | Zhang et al.                                                                                           |
|              |                         | Grounding-DINO                                                 | [Liu et al.](https://github.com/IDEA-Research/GroundingDINO)                                          |
|              |                         | DINOv2                                                         | [Meta AI Research](https://github.com/facebookresearch/dinov2)                                        |
|              |                         | AM-RADIO                                                       | [NVIDIA](https://github.com/NVlabs/RADIO)                                                             |
|              |                         | DINO-WM                                                        | Zhou et al.                                                                                            |
|              |                         | YOLO-World                                                     | [Cheng et al.](https://github.com/AILabCVC/YOLO-World)                                                |
|              | **Image Segmentation**  | CLIPSeg                                                        | [Lüdecke and Ecker](https://github.com/timojl/clipseg)                                                |
|              |                         | SAM                                                            | [Meta AI Research, FAIR](https://segment-anything.com)                                                |
|              |                         | Embodied-SAM                                                   | [Xu et al.](https://github.com/xuxw98/ESAM)                                                           |
|              |                         | Point-SAM                                                      | [Zhou et al.](https://github.com/zyc00/Point-SAM)                                                     |
|              |                         | Open-Vocabulary SAM                                            | [Yuan et al.](https://www.mmlab-ntu.com/project/ovsam/)                                               |
|              |                         | TAP                                                            | [Pan et al.](https://github.com/baaivision/tokenize-anything)                                         |
|              |                         | EfficientSAM                                                   | [Xiong et al.](https://yformer.github.io/efficient-sam/)                                             |
|              |                         | MobileSAM                                                      | [Zhang et al.](https://github.com/ChaoningZhang/MobileSAM)                                            |
|              |                         | SAM 2                                                          | [Meta AI Research, FAIR](https://ai.meta.com/sam2/)                                                   |
|              |                         | SAMURAI                                                        | [University of Washington](https://github.com/yangchris11/samurai)                                    |
|              |                         | SegGPT                                                         | [Wang et al.](https://github.com/baaivision/Painter)                                                  |
|              |                         | Osprey                                                         | [Yuan et al.](https://github.com/CircleRadon/Osprey)                                                  |
|              |                         | SEEM                                                           | Zou et al.                                                                                             |
|              |                         | Seal                                                           | [Liu et al.](https://github.com/youquanl/Segment-Any-Point-Cloud)                                     |
|              |                         | LISA                                                           | [Lai et al.](https://github.com/dvlabresearch/LISA)                                                   |
|              | **Depth Estimation**    | ZoeDepth                                                       | [Bhat et al.](https://github.com/isl-org/ZoeDepth)                                                    |
|              |                         | ScaleDepth                                                     | [Zhu et al.](https://ruijiezhu94.github.io/ScaleDepth/)                                               |
|              |                         | Depth Anything                                                 | [Yang et al.](https://depth-anything.github.io)                                                       |
|              |                         | Depth Anything V2                                              | [Yang et al.](https://depth-anything-v2.github.io/)                                                   |
|              |                         | Depth Pro                                                      | [Apple](https://github.com/apple/ml-depth-pro)                                                        |


## Summary of Methods and Models
*(Coming soon: table showcasing the summary of various methods and models.)*

## UAV-oriented Datasets on Environmental Perception & Event Recognition & Detection
*(Coming soon: detailed table and references.)*

## UAV-oriented Datasets on Object Tracking
*(Coming soon.)*

## UAV-oriented Datasets on Action Recognition
*(Coming soon.)*

## UAV-oriented Datasets on Navigation and Localization
*(Coming soon.)*

## UAV-oriented Datasets on Transportation
*(Coming soon.)*

## UAV-oriented Datasets on Remote Sensing
*(Coming soon.)*

## UAV-oriented Datasets on Agriculture & Industry & Emergency Response & Military & Wildlife
*(Coming soon.)*

---

## Contributors
We want to thank the following contributors for creating, maintaining, and curating the tables in this repository:

- **Yonglin Tian** 
- **Fei Lin** 
- **Yiduo Li**  
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


