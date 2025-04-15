# DMD_Driver_action
Multi-Modal Driver Monitoring System using 3D Deep Learning Models
This project presents a multi-modal driver monitoring system that utilizes deep learning models to assess driving safety in real-time. It integrates three key visual modalities—Driver Actions, Gaze Direction, and Hands on the Wheel—each processed through dedicated 3D convolutional neural networks (CNNs) based on ResNet and MobileNet architectures.

The system computes danger scores from each modality, aggregates them using weighted fusion, and classifies the driving behavior as Safe or Unsafe. It includes threshold optimization, alarm triggering, and evaluation using multiple metrics such as accuracy, F1-score, ROC AUC, and confusion matrix analysis. The models are fine-tuned using real-world video datasets and enhanced with data augmentation to improve generalization.
