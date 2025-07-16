# 👁️ Automatic Detection of Diabetic Retinopathy Using CNN

A deep learning-based solution to automatically detect and classify the stages of Diabetic Retinopathy (DR) using retinal fundus images. This project uses Convolutional Neural Networks (CNN), U-Net segmentation, and denoising techniques to achieve high accuracy in DR detection and grading.

---


## 🧠 Introduction

Diabetic Retinopathy (DR) is a diabetes complication that affects the eyes and can lead to blindness. Early detection and treatment can significantly reduce the risk. This project proposes an automated DR detection system using CNN, aiming for accurate, fast, and scalable screening, especially useful in rural or resource-constrained areas.

---

## 🚀 Features

- ✅ Automatic classification of DR using CNN
- 📷 Works with fundus images
- 📊 Accuracy of ~95% for binary and ~85% for multi-class classification
- 🔁 Uses U-Net segmentation for retinal vessel detection
- ⚖️ Includes comparison of ResNet101 and DenseNet121
- 🧠 Built with Theano, Keras, TensorFlow
- 📈 Confusion matrix and accuracy/loss graphs
- 🖼️ GUI using Tkinter for image upload and prediction

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: TensorFlow, Keras, Theano, NumPy, Matplotlib, Pandas, Scikit-learn, OpenCV
- **GUI**: Tkinter
- **Models**: CNN, ResNet101, DenseNet121
- **IDE**: Jupyter Notebook / VS Code

---

## 💻 System Requirements

**Hardware:**
- Minimum i3 Processor
- 4 GB RAM
- 40 GB HDD

**Software:**
- Windows 8 or higher
- Python 3.7+
- Required Python packages: listed in `requirements.txt`

---


## 📦 Modules

- **Data Upload**: Load image dataset
- **Preprocessing**: Resize, normalize, and split into training/testing
- **CNN Training**: Train ResNet101 and DenseNet121
- **Evaluation**: Display confusion matrix and graphs
- **Prediction**: Upload new image and display DR result
- **GUI**: Built using Tkinter

---
```
## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetic-retinopathy-cnn.git
   cd diabetic-retinopathy-cnn

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Organize dataset as:

   Dataset/
     └── train/
         ├── dr/
         └── nodr/
     └── valid/
     └── test/

4. Run the application:

   ```bash
   python main.py
   ```

## 📊 Results

* **Binary Classification Accuracy**: \~95%
* **Multi-class Classification Accuracy**: \~85%
* **Confusion Matrix**: Visualized in Graphical User Interface
* **Prediction Output**: Overlay on test images

---

## 🔮 Future Enhancements

* 📱 Mobile/web integration for real-time screening
* ⚙️ Transfer learning with EfficientNet
* 🔍 Multi-stage DR classification
* 🧠 Explainable AI using Grad-CAM or LIME
* 🔗 Integration with Electronic Health Records (EHR)

---


## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> ⚠️ This project is for educational and research purposes. It is not intended for clinical use without validation.

