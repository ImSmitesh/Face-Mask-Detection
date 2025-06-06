![alt text](93715393-a0315b00-fb86-11ea-9e59-8cb610b76318.png)

# Face Mask Detection

## 🧠 Overview

This project utilizes Convolutional Neural Networks (CNNs) to classify images and video frames into three categories:

- **Mask**
- **No Mask**
- **Incorrect Mask**

The model is trained on a custom dataset and can be deployed for real-time face mask detection in various applications.

## 📁 Project Structure

```plaintext

├── data/                       # Dataset directory
│ ├── with_mask/                # Images with mask
│ ├── without_mask/             # Images without mask
├── Model/                      # Trained model 
├── detect_mask_video.py        # Real-time mask detection script
└── train_mask_detector.py      # Script to train the model

```

## ⚙️ Installation

### Clone the repository:

```bash
git clone https://github.com/ImSmitesh/Face-Mask-Detection.git
cd Face-Mask-Detection
```

## 🏃 Usage

### Train the model:

```bash
python python train_mask_detector.py
```

### Detect mask in video stream:

```bash
python detect_mask_video.py
```