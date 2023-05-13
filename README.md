# Awesome-Video-Instance-Segmentation
A list of video instance segmentation (VIS) papers 

## Contents

- [Introduction](#Introduction)
- [Datasets](#Datasets)
- [2023](#2023)

---
# Awesome Video Instance Segmentation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list of Video Instance Segmentation (VIS) Research Papers.
Any suggestion stars ⭐ , comments & sharing 😀 are welcome!!

```diff
- 2023.05.10: Recent papers (from 2023) 
- Welcome to add if any information is missed. 
```
---

## <span id = "Introduction"> **Introduction** </span>
**Video Instance Segmentation** aims at **detecting, segmenting, and tracking every pixel of object instances simultaneously in a given video.** 

**Video Instance Segmentation** (VIS) methods can be categorized as online, Semi-Online or Offline methods. 
- ***Online methods***  take as input a video frame by frame, detecting and segmenting objects per frame while tracking instances and optimizing results
across frames.
- ***Offline methods***  in contrast, take the whole video as input and generate the instance sequence of the entire video with a single step.
- ***Semi-online*** that focus on placing multiple frames in a short clip to strengthen intra-clip tracking similar to offline methods.
---

## <span id = "Datasets"> **Datasets** </span>
- **Youtube VIS 2019 (YTVIS 2019)**   : The 2019 version was used for [“the 2nd large-scale video object segmentation challenge”](https://youtube-vos.org/challenge/2019/) at ICCV 2019.
-** Youtube VIS 2021 (YTVIS 2021)**   : The 2021 version was used for [“the 3rd large-scale video object segmentation challenge”](https://youtube-vos.org/challenge/2021/) at ICCV 2021.



## <span id = "2023"> **2023** </span>
|PAPER TITLE|YEAR|VENUE|PROBLEM|TRACKING|DATASET|PAPER LINK|GITHUB LINK|PROJECT LINK|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|
| | | |(Universal / Task)|(Online / Offline)| | | | |
| Universal Instance Perception as Object Discovery and Retrieval |2023|CVPR|Universal - VIS, VOS, MOTS| Online, and post-processing free|Youtube-VIS  2019, OVIS|[Link](https://arxiv.org/pdf/2303.06674v1.pdf)|[Link](https://github.com/MasterBin-IIAU/UNINEXT)| |
|MDQE: Mining Discriminative Query Embeddings to Segment Occluded Instances on Challenging Videos|2023|CVPR|VIS|Semi-Online|YouTube-VIS 2021,OVIS |[Link](https://arxiv.org/pdf/2303.14395.pdf)|[Link](https://github.com/minghanli/mdqe_cvpr2023)| |
|Mask-Free Video Instance Segmentation|2023|CVPR|VIS| |YouTube-VIS 2019/2021, OVIS, BDD100K,MOTS |[Link](https://arxiv.org/pdf/2303.15904.pdf)|[Link](https://github.com/syscv/maskfreevis)| |
|Tube-Link: A Flexible Cross Tube Baseline for Universal Video Segmentation|2023|CVPR|Universal- VSS,VIS,VPS|Online/Semi-Online|YouTube-VIS 2019/2021,VIPSeg, KITTI-STEP |[Link](https://arxiv.org/pdf/2303.12782v1.pdf)|[Link](https://github.com/lxtGH/Tube-Link) (Code Not Available Yet)| |
|Video Instance Segmentation in an Open-World|2023|CVPR|VIS - Unseen Categories| | |[Link](https://arxiv.org/pdf/2304.01200v1.pdf)|[Link](https://github.com/OmkarThawakar/OWVISFormer)| |
|InstMove: Instance Motion for Object-centric Video Segmentation|2023|CVPR|VIS, VOS| Online |SOTA OVIS, YouTubeVIS 2022, DAVIS 2017|[Link](https://arxiv.org/pdf/2303.08132.pdf)|[link](https://github.com/wjf5203/VNext/tree/main/projects/InstMove) (No code available yet. To be released in the VNEXT repository) | |
|TarViS: A Unified Approach for Target-based Video Segmentation|2023|CVPR|Universal - VIS, VOS, PET,VPS|Semi-Online|KITTI-STEP, CityscapesVPS, VIPSeg, YouTubeVIS 2019/2021, DAVIS 2017, BURST|[Link](https://arxiv.org/pdf/2301.02657.pdf)|[Link](https://github.com/Ali2500/TarViS)| |
|A Generalized Framework for Video Instance Segmentation|2023|CVPR|VIS|Semi-Online/Offline|YouTube-VIS 2019/2021,OVIS|[Link](https://arxiv.org/pdf/2211.08834.pdf)|[Link](https://github.com/miranheo/GenVIS)| |

**2022**
|PAPER TITLE|YEAR|VENUE|PROBLEM|TRACKING|DATASET|PAPER LINK|GITHUB LINK|PROJECT LINK|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|
| | | |(Universal / Task)|(Online / Offline)| | | | |
|Masked-attention Mask Transformer for Universal Image Segmentation|2022|CVPR|VIS|Offline|YTVIS 2019|[Link](https://arxiv.org/pdf/2112.01527.pdf)|[Link](https://bowenc0221.github.io/mask2former/)| |
|Instance As Identity: A Generic Online Paradigm for Video Instance Segmentation|2022|ECCV|VIS| | |[Link](https://arxiv.org/pdf/2208.03079v2.pdf)| |[Link](https://paperswithcode.com/paper/instanceformer-an-online-video-instance)|
|Temporally Efficient Vision Transformer for Video Instance Segmentation|2022|CVPR| | | |[Link]([https://link-url-here.org](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Temporally_Efficient_Vision_Transformer_for_Video_Instance_Segmentation_CVPR_2022_paper.pdf))| | |
|InstanceFormer: An Online Video Instance Segmentation Framework|2022|ECCV| | | |[Link](https://arxiv.org/pdf/2208.10547v1.pdf)|[Link](https://github.com/rajatkoner08/InstanceFormer)| |
|TIVE: A Toolbox for Identifying Video Instance Segmentation Errors|2022|Arxiv|VIS Metric| | |[Link](https://arxiv.org/pdf/2210.08856v1.pdf)| | |
|STC: Spatio-Temporal Contrastive Learning for Video Instance Segmentation|2022|ECCV Workshop| | | |[Link](https://link.springer.com/chapter/10.1007/978-3-031-25069-9_35)| | |

**2021**
|PAPER TITLE|YEAR|VENUE|PROBLEM|TRACKING|DATASET|PAPER LINK|GITHUB LINK|PROJECT LINK|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|
| | | |(Universal / Task)|(Online / Offline)| | | | |
|Prototypical Cross-Attention Networks for Multiple Object Tracking and Segmentation|2021|NEURIPS|VIS|PCAN| |[Link](https://papers.nips.cc/paper/2021/file/093f65e080a295f8076b1c5722a46aa2-Paper.pdf)| | |
|Spatial Feature Calibration and Temporal Fusion for Effective One-stage Video Instance Segmentation|2021|CVPR| | | |[Link](http://www4.comp.polyu.edu.hk/~cslzhang/papers.htm)|[Link](https://github.com/MinghanLi/STMask)| |
|Crossover Learning for Fast Online Video Instance Segmentation|2021|ICCV| | | |[Link](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Crossover_Learning_for_Fast_Online_Video_Instance_Segmentation_ICCV_2021_paper.pdf)|[Link](https://github.com/hustvl/CrossVIS)| |
| | | | | | | | | |
| | | | | | | | | |
