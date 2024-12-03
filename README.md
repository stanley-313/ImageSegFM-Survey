# Image Segmentation in Foundation Model Era: A Survey
***
This repository complies a collection of resources on image segmentation in foundation model era, 
and will be  continuously updated to track developments in the field. 
Please feel free to submit a pull request if you find any work missing.

## 1. Introduction
Image segmentation is a long-standing challenge in computer vision, studied continuously over several decades, as
 evidenced by seminal algorithms such as N-Cut, FCN, and MaskFormer. With the advent of foundation models (FMs), contemporary
 segmentation methodologies have embarked on a new epoch by either adapting FMs (e.g., CLIP, Stable Diffusion, DINO) for image
 segmentation or developing dedicated segmentation foundation models (e.g., SAM, SAM2). These approaches not only deliver
 superior segmentation performance, but also herald newfound segmentation capabilities previously unseen in deep learning context.
In this survey, we offer an exhaustive
 and timely overview to examine _how foundation models are
 transforming the entire field of image segmentation_ as shown in the following figure:

<p align="center">
  <img src="tasks.png" width="500">
</p>

***

## 2. Segmentation Knowledge Emerges From FMS
Given the emergency capabilities of LLMs, a natural ques
tion arises: Do segmentation properties emerge from FMs? The
 answer is positive, even for FMs not explicitly designed for
 segmentation, such as CLIP, DINO and Diffusion Models. This unlocking a new frontier in image segmentation,
 i.e., acquiring segmentation without any training. The following figure illustrates how to approach this and shows some examples:

<p align="center">
  <img src="segmentation emerge.PNG" width="500">
</p>

- [2.1 Segmentation Emerges from CLIP]()
- [2.2 Segmentation Emerges from DMs]()
- [2.3 Segmentation Emerges from DINO]()

***

## 3. Foundation Model based GIS
- [3.1 Semantic Segmentation]()
  - [3.1.1 CLIP-based Solution]()
  - [3.1.2 DM-based Solution]()
  - [3.1.3 DINO-based Solution]()
  - [3.1.4 SAM-based Solution]()
  - [3.1.5 Composition of FMs]()
- [3.2 Instance Segmentation]()
  - [3.2.1 CLIP-based Solution]()
  - [3.2.2 DM-based Solution]()
  - [3.2.3 DINO-based Solution]()
  - [3.2.4 Composition of FMs]()
- [3.3 Panoptic Segmentation]()
  - [3.3.1 CLIP-based Solution]()
  - [3.3.2 DM-based Solution]()
  - [3.3.3 DINO-based Solution]()
  - [3.3.4 SAM-based Solution]()

***

## 4. Foundation Model based PIS
- [4.1 Interactive Segmentation](4-PIS.md#41-interactive-segmentation)
  - [4.1.1 SAM-based Solution](4-PIS.md#411-sam-based-solution)
- [4.2 Referring Segmentation](4-PIS.md#42-referring-segmentation)
  - [4.2.1 CLIP-based Solution](4-PIS.md#421-clip-based-solution)
  - [4.2.2 DM-based Solution](4-PIS.md#422-dm-based-solution)
  - [4.2.3 LLMs/MLLMs-based Solution](4-PIS.md#423-llmsmllms-based-solution)
  - [4.2.4 Composition of FMs](4-PIS.md#424-composition-of-fms)
- [4.3 Few-shot Segmentation](4-PIS.md#43-few-shot-segmentation)
  - [4.3.1 CLIP-based Solution](4-PIS.md#431-clip-based-solution)
  - [4.3.2 DM-based Solution](4-PIS.md#432-dm-based-solution)
  - [4.3.3 DINO-based Solution](4-PIS.md#433-dino-based-solution)
  - [4.3.4 SAM-based Solution](4-PIS.md#434-sam-based-solution)
  - [4.3.5 LLMs/MLLMs-based Solution](4-PIS.md#435-mllms-based-solution)
  - [4.3.6 In-Context Segmentation](4-PIS.md#436-in-context-segmentation)
## Citation

If you find our survey and repository useful, please consider citing our paper:
```bibtex
@article{zhou2024SegFMSurvey
    title={Image Segmentation in Foundation Model Era: A Survey},
    author={Zhou, Tianfei and Xia, Wang and Zhang, Fei and Chang, Boyu and Wang, Wenguan and Yuan, Ye and Konukoglu, Ender and Cremers, Daniel},
    journal={arXiv preprint arXiv:2408.12957},
    year={2024},
}
```
