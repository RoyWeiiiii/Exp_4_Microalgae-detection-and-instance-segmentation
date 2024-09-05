# Translating pixels into identification: Cutting-edge microalgae detection and instance segmentation by leveraging YOLOv8 models 
By Jun Wei Roy Chong, Kuan Shiong Khoo, Huong-Yong Ting, Iwamoto Koji, Zengling Ma, Pau Loke Show

This study harnesses the advanced capabilities of the YOLOv8 model to enhance real-time detection and instance segmentation of microalgae species, specifically Chlorella vulgaris FSP-E, Chlamydomonas reinhardtii, and Spirulina platensis. Comprehensive evaluations revealed that the original RGB dataset provided better detection accuracy compared to augmented and pre-processed datasets. The YOLOv8-n box detection achieved high accuracy with precision, recall, F1 score, mAP50, and mAP50-95 of 0.866, 0.0.871, 0.868, 0.919, and 0.732, respectively. Nonetheless, YOLOv8-n box instance segmentation demonstrated superior performance with precision, recall, F1 score, mAP50, and mAP50-95 of 0.884, 0.914, 0.889, 0.950, and 0.812, respectively. YOLOv8-n outperformed its predecessors YOLOv5-s and YOLOv7, in terms of overall performance with lower computational cost and faster inference speed, yet still able to deliver high accuracy results on densely populated microalgae samples. 

**Keywords:** Microalgae; Detection; Instance segmentation; YOLOv5; YOLOv7; YOLOv8

# Image Dataset Preparation using Roboflow
The preparation of microalgae (_Chlorella vulgaris_ FSP-E, _Chlamydomonas reinhardtii_, and _Spirulina platensis_) dataset "**Detection**" and "**Instance Segmentation**" labelling/ annotation and image pre-processing techniques (Grayscale, Histogram equalisation, Adaptive equalisation) were performed using the "Roboflow platform. 

**Microalgae Detection Ver 1** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Trial 1-4_RGB Dataset" contains Trial_1_RGB, Trial_2_RGB, Trial_3_RGB, and Trial_4_RGB (discussed under section 3.2 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_trial-1-4_rgb/4

**Microalgae Detection Ver 2** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Baseline model_Augmentation_Image processing Dataset" contains RGB_Baseline model-Trial_5_RGB, Grayscale, Grayscale_Adaptive_Equalisation, Grayscale_Histogram_Equalisation, RGB-IMG-Augmentation, and RGB-BB-Augmentation (discussed under section 3.1, 3.3, and 3,4 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_baseline-model_augmentation_image-processing/11

**Microalgae Instance Segmentation** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Instance_Segmentation Dataset" contains Instance Segmentation_RGB, Instance Segmentation_RGB_IMG_Augmentation, and Instance Segmentation_RGB_BB_Augmentation (discussed under section 3.5 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_instance_segmentation/4

# Referencing and citation
If you find _Chlorella vulgaris_ FSP-E, _Chlamydomonas reinhardtii_, and _Spirulina platensis_ Detection and Instance Segmentation useful in your research, please consider citing:
