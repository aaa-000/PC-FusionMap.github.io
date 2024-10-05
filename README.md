<div align="center">
<h1>PC-FusionMap</h1>
<h3>A Novel Point Cloud Generation
and Multimodal Fusion Approach for HD Map
Construction</h3>




Zhenjie Duan <sup>a*</sup>, 
[Yaoming Zhuang](http://faculty.neu.edu.cn/zhuangyaoming/) <sup>a*#</sup>, 
Li Li <sup>a</sup>,
Chengdong Wu <sup>a</sup>,
Zhanlin Liu <sup>b</sup>

<sup>a</sup> Northeastern University, 
<sup>b</sup> AstrumU

<sup>*</sup>Equal contribution. <sup>#</sup>Corresponding author.


<div align="left">
  
## Overview
![pipeline](assets/overview_pipeline.jpg)
High-definition (HD) maps are crucial for autonomous driving, supporting decision-making, control, and localization. However, current map generation methods often rely on single-modality images, which lack depth information and environmental context. To overcome these limitations, we propose PC-FusionMap, a novel approach that generates point cloud modality data and fuses multi-modal and temporal features for accurate and efficient online HD map construction. Our method addresses the shortcomings of existing approaches by leveraging an improved depth estimation module and a supervised labeling strategy to generate point cloud data. We also introduce a multi-modal feature fusion architecture (CFMB) and a temporal fusion network (TFC) to effectively integrate multi-modal and temporal information. The CFMB architecture uses a query mechanism and cross-attention to enhance the complementary performance between modalities, simplifying the fusion process and improving accuracy. The TFC Network models dynamic changes in time series data, further enhancing the accuracy and robustness of online HD map construction. Our approach achieves state-of-the-art results on the nuScenes and the Argoverse2 datasets, surpassing baseline models in both accuracy and stability. Additionally, incorporating our method into existing HD map generation models can lead to substantial performance gains.


## Dataset
We utilized the nuScenes and Argoverse 2 datasets, and the data download and processing procedures are as follows:
- [Prepare Dataset](docs/prepare_dataset.md)








