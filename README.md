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
Download Link: "https://www.isprs.org/education/benchmarks/UrbanSemLab/Default.aspx"
