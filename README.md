# Facial Occlusion Classification for Restricted Environments

**Team IntelliSense**
*ICT 3212 - Introduction to Intelligent Systems*
*Rajarata University of Sri Lanka*

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange?style=flat&logo=tensorflow)
![Status](https://img.shields.io/badge/Status-Implementation_Phase-green)

---

## 📌 Project Overview
Security in restricted environments like ATMs, bank vaults, and examination centers faces challenges due to facial occlusions. Offenders often use helmets or masks to hide their identity, while others use medical masks for health reasons.

This project implements an **Automated Image Classification System** using Deep Learning to differentiate between these occlusion types. The system aims to assist security monitoring by classifying individuals into specific categories based on facial visibility.

## 🎯 Objectives
* **Dataset Creation:** Develop a labeled dataset for three categories: *Face with Mask*, *Face with Helmet*, and *Clear Face*.
* **Model Development:** Design and train a Convolutional Neural Network (CNN) based on the **MobileNet** architecture.
* **Evaluation:** Assess model performance using Accuracy, Precision, Recall, and F1-Score.
* **Prototype:** Develop a system to upload images and display classification results with confidence scores.

## 📂 Dataset Classes
The system classifies images into three predefined categories:
1.  **Clear Face**: No occlusion.
2.  **Face with Mask**: Proper usage of medical/fabric masks.
3.  **Face with Helmet**: Full-face motorcycle helmets or similar coverings.

## 🛠️ Technologies Used
* **Programming Language:** Python
* **Deep Learning Frameworks:** TensorFlow, Keras
* **Image Processing:** OpenCV, NumPy, Matplotlib
* **Development Environment:** Google Colab / Jupyter Notebook

## 👥 Team Members

| Name                       | Registration No | Index No |
| :---                       | :---            | :---     |
| **T.H.M. Thilakarathna**   | ICT/2022/104    | 5707     |
| **S.H.M.P.K. Senadheera**  | ICT/2022/123    | 5725     |
| **H.M.S.S.W. Bandara**     | ICT/2022/145    | 5946     |
| **A.K.A. Sanjula**         | ICT/2022/093    | 5696     |
| **S.M.S.C. Seneviratne**   | ICT/2022/086    | 5690     |

## 🚀 How to Run
1.  Clone this repository.
2.  Upload the `Dataset` folder to your Google Drive.
3.  Open the `IntelliSense_Implementation.ipynb` file in Google Colab.
4.  Mount the drive and run the cells to train the model.

---
