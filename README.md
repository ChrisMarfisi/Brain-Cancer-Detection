NeuroVision is a deep learning based system for detecting and classifying brain tumors from MRI scans. The model determines whether a tumor is present and classifies scans into glioma, meningioma, pituitary, or no tumor. The goal is to support faster and more reliable clinical decision making.

The final model achieved 99.69 percent accuracy on a held out test set of 1,311 MRI images. It produced zero false positives and zero false negatives for the no tumor class, with only four total misclassifications across all classes. These results outperform comparable published and Kaggle based models on the same dataset.

The system is built on an EfficientNetV2B0 architecture pretrained on ImageNet and fine tuned for medical imaging. This architecture provides high accuracy with fewer parameters, enabling efficient training and inference. Additional dense and dropout layers improved generalization.

MRI images were carefully preprocessed and augmented to improve robustness to image quality and orientation. Grad CAM visualizations confirmed that the model focuses on clinically relevant tumor regions when making predictions. Together, these results demonstrate the potential of deep learning to improve accuracy and efficiency in medical imaging workflows.
