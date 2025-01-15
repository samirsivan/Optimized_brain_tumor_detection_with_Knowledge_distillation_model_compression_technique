# Knowledge Distillation for Optimized_brain_tumor_detection 
Welcome to the Knowledge Distillation for Optimized_brain_tumor_detection! This project demonstrates the application of knowledge distillation, where a large, powerful teacher model (InceptionV3) transfers its knowledge to a smaller, student model (custom CNN), making it more efficient while retaining high performance.

# Project Overview
Knowledge distillation is a training paradigm in deep learning that transfers knowledge from a large teacher model to a smaller student model. The aim is to optimize the student model for efficiency without compromising too much on accuracy.

This project focuses on:

Teacher Model: InceptionV3, a powerful pretrained model.
Student Model: A custom lightweight CNN designed for improved computational efficiency.
Dataset: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

# Knowledge Distillation Diagram:

![Screenshot 2025-01-15 064509](https://github.com/user-attachments/assets/06602d3a-ecdd-4cc8-a1f7-d10494092fd5)

# Teacher Vs Student Result: Before and After KD:
## Confusion Matrices

![Screenshot 2025-01-15 064134](https://github.com/user-attachments/assets/c08e94f0-7595-4d90-a029-8d928658d016)
![Screenshot 2025-01-15 064149](https://github.com/user-attachments/assets/aedaf21a-8c4f-49fe-b414-074a0770ac86)

## Classification Report
![Screenshot 2025-01-15 064046](https://github.com/user-attachments/assets/32ed4ec0-a378-4a51-8010-4b63a1002a21)
