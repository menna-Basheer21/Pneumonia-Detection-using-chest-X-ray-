# Pneumonia-Detection-using-chest-X-ray-
This repository contains code and resources for analyzing chest X-ray images to detect and classify pneumonia. The workflow utilizes the Kaggle API to automatically fetch the Chest X-Ray Images (Pneumonia) dataset, which includes chest X-ray scans categorized into NORMAL and PNEUMONIA classes across training, validation, and testing splits
* **Notebook 1: Data Preprocessing & Exploration** – Focuses on downloading the dataset via `kagglehub`, exploring the `NORMAL` and `PNEUMONIA` class distributions, and setting up image data generators for resizing, scaling, and data augmentation.


* **Notebook 2: Model Training & Transfer Learning** – Concentrates on building and training the deep learning architecture using TensorFlow/Keras, leveraging pre-trained models like VGG16 with custom dense layers for image classification.


* **Notebook 3: Evaluation & Interpretability (Grad-CAM)** – Dedicated to evaluating model performance on the test split, generating classification metrics, and utilizing Grad-CAM heatmap visualizations to interpret model focus on the chest X-rays.
