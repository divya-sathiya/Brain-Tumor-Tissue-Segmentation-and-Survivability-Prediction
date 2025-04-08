# Brain-Tumor-Tissue-Segmentation-and-Survivability-Prediction

Brain tumors, characterized by abnormal tissue growth, present significant diagnostic and treatment challenges. Early detection and precise diagnosis, primarily through Magnetic Resonance Imaging (MRI), are critical for improving patient outcomes. However, conventional methods relying on manual segmentation and expert interpretation are time-intensive and prone to variability. This project explores a deep learning-based approach leveraging the BraTS 2020 dataset to address two key tasks: tumor segmentation and survival prediction.

The BraTS 2020 dataset, comprising multimodal MRI scans with detailed tumor sub-region annotations, was used to develop two models: a UNet-based architecture for segmentation and a ResNet50-based model for survival classification. The UNet model achieved an accuracy of 89.86\% for segmentation, with the highest accuracy observed in identifying the enhancing tumor core (ET) region. The ResNet50 model, trained on ground truth masks to classify into survival day bins, achieved an accuracy of 65.15\%. When combined, the UNet and ResNet50 models achieved an impressive overall accuracy of 86.92\% after filtering empty masks and 98.31\% after taking the majority vote across a volume.

This work highlights the potential of deep learning to automate MRI analysis, providing a consistent, scalable solution for brain tumor diagnosis and survival estimation. 

#### Project Members: 
* Divya Sathiyamoorthy (ds4221@columbia.edu)
* Smriti Vaidyanathan (sv2785@columbia.edu)
