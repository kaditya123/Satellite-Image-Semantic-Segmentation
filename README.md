# Satellite-Image-Semantic-Segmentation
### BTP-1

## Very-High-Resolution Semantic Segmentation: Comparative Analysis of LinkNet, Feature Pyramid (FPN) and Pyramid Scene Parsing Network (PSPNet) using the Potsdam Dataset

This study explores the strengths of LinkNet’s innovative training strategy, FPN’s cost-effective feature extraction, and PSPNet’s global context handling. It emphasizes ResNet-{50/35} based backbone encoder architecture trade-offs and investigates different patch size impact (extracted from images) on the performance of segmentation. 

## The Dataset: Potsdam
The ISPRS Potsdam dataset consists of very high-resolution true ortho photo (TOP) tiles, capturing a historic cityscape with intricate urban structures. It comprises 38 high-resolution patches, each measuring 6000 × 6000 pixels, along with corresponding ground truth masks. Focusing exclusively on RGB channels and omitting digital surface models (DSMs), the dataset was systematically partitioned into smaller patches e.g., (512 × 512 pixels) with a non-overlapping stride of 512. This standardized approach ensures consistent training and evaluation while maximizing spatial detail. 
#### The dataset includes 6 land-cover classes: 
    - Impervious surfaces
    - Buildings
    - Low Vegetation
    - Trees
    - Cars
    - Clutter/background
#### Download Link: "https://www.isprs.org/education/benchmarks/UrbanSemLab/Default.aspx"

## The Overview of Models
### 1) LinkNet
       - Abhishek Chaurasia and Eugenio Culurciello. Linknet: Exploiting encoder representations for efficient semantic segmentation. In 2017 IEEE visual communications and
image processing (VCIP), pages 1–4. IEEE, 2017.
![image](https://github.com/user-attachments/assets/29a4762e-8ca8-476a-8d60-d979b4075628)

### 2) 
       - FPNet: Tsung-Yi Lin, Piotr Dollár, Ross Girshick, Kaiming He, Bharath Hariharan, and Serge Belongie. Feature pyramid networks for object detection. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 2117–2125, 2017.
![image](https://github.com/user-attachments/assets/5ef730a7-ebf7-47e4-8c68-9194cf0822c0)

### 3) 
       - PSPNet: Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, and Jiaya Jia. Pyramid scene parsing network. In Proceedings of the IEEE conference on computer vision and pattern recognition, pages 2881–2890, 2017.
![image](https://github.com/user-attachments/assets/3afde5c7-280c-4e36-81e3-2baf870a0e84)


