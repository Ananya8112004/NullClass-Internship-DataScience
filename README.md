# NullClass-Internship-DataScience
This repository contains the tasks completed during my Machine Learning Developer Internship at NullClass (07-07-2025 to 07-09-2025).
The focus of the internship was on grayscale image colorization using deep learning, dataset augmentation, semantic segmentation, and real-time applications.

## 📂 Repository Structure
- **TASK_1_Colorization_Visualization/**
  - `TASK_1.ipynb` → Visualizes intermediate stages of the colorization process  
  - `requirement.txt`  

- **TASK_2_Dataset_Augmentation/**
  - `TASK_2.ipynb` → Uses data augmentation (rotation, flipping, brightness changes) to improve colorization  
  - `requirement.txt`  

- **TASK_3_Semantic_Segmentation_Colorization/**
  - `TASK_3.ipynb` → Targeted colorization of foreground or background using DeepLabV3 segmentation  
  - `requirement.txt`  
  - `images/` → Sample test images  

- **TASK_4_Historical_Colorization/**
  - `TASK_4.ipynb` → Time-based historical image colorization (e.g., 1900s vs 1950s palette)  
  - `requirement.txt`  
  - `images/` → Sample test images  

- **TASK_5_RealTime_Colorization/**
  - `TASK_5.ipynb` → Real-time multi-object colorization with semantic segmentation on video streams  
  - `requirements.txt`  

- **Internship_Report.pdf** → Final internship report  

---

## 📝 Tasks Overview

**Task 1 – Visualizing the Colorization Process**  
- Visualized intermediate stages from grayscale → partial color → final output.  
- Helped understand how the model learns color features.  

**Task 2 – Dataset Augmentation to Improve Colorization**  
- Applied augmentation (rotation, flipping, brightness changes).  
- Improved robustness and consistency of colorization.  

**Task 3 – Semantic Segmentation for Targeted Colorisation**  
- Combined segmentation + colorization.  
- GUI provided for selecting regions to colorize (foreground/background).  

**Task 4 – Time-Based Historical Image Colorization**  
- Classified photos by era (1900s, 1950s, etc.).  
- Applied time-specific color palettes for realistic restoration.  
- GUI allows user to upload photo & choose/override era.  

**Task 5 – Real-Time Multi-Object Colorization**  
- Real-time video colorization using semantic segmentation.  
- GUI for uploading webcam/video streams.  
- Different objects detected and colorized with distinct schemes.  

---

## 📊 Evaluation Metrics
Each model was evaluated using:
- **Accuracy** (≥ 70% achieved where applicable)  
- **Confusion Matrix**  
- **Precision, Recall, F1-score**  

---

## 📥 Datasets
- Publicly available online datasets were used (e.g., COCO, ADE20K, historical photo archives).  
- For testing/demo, 2–3 sample grayscale images are included in the `images/` folder of each task.  

---

## 📑 Internship Report
A detailed internship report covering background, methodology, skills, and outcomes is available in **`Internship_Report.pdf`**.  

---

## 🏆 Acknowledgements
This work was completed as part of my internship at **NullClass**, where I gained hands-on experience in **Computer Vision, Deep Learning, and Real-time AI systems**.
