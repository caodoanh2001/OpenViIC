# OpenViIC: A Novel Benchmark for Evaluating Image Captioning in Vietnamese

## Introduction

The implementation of the paper "OpenViIC: A Novel Benchmark for Evaluating Image Captioning in Vietnamese."

This repository includes a link to access our OpenViIC dataset and our implementation of state-of-the-art captioning models in this dataset. The OpenViIC dataset is the first Vietnamese open-domain dataset for evaluating image captioning; it includes 13,100 images with over 60,000 annotated captions. The images' contexts are related to Vietnam scenes and people, which are diverse.

![](https://i.imgur.com/OvhHxSn.png)

### Members

1. **BSc. Doanh C. Bui**, Faculty of Software Engineering, University of Information Technology, VNU-HCM
2. **BSc. Hieu Nghia Nguyen**, Faculty of Information Science and Engineering, University of Information Technology, VNU-HCM.
3. **MSc. Nguyen D. Vo**, Multimedia Laboratory, University of Information Technology, VNU-HCM.
4. **Dr. Khang Nguyen**, University of Information Technology, VNU-HCM.

And we thank the student team from the Faculty of Software Engineering and the volunteers who contribute high-quality captions. We really appreciate their contributions.

## Implementation

As reported in the paper, we create the largest Vietnamese dataset for evaluating image captioning and run state-of-the-art models to evaluate their performance. 07 models are used to conduct experiments: 

- Original Transformer (NeurIPS, 2017)
- AoANet (CVPR, 2019)
- ORT (NeurIPS, 2019)
- M2 Transformer (CVPR, 2020)
- DLCT (AAAI, 2021)
- RSTNet (CVPR, 2021)
- MDSANet (TMM, 2022)

All implementations, checkpoints, and results are reported in this repository.