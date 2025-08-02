# 🌳 Tree Species Image Classification using CNN

An image classification project aimed at identifying tree species from leaf images using a Convolutional Neural Network (CNN) model built and trained in Google Colab.

---

## 📌 Problem Statement

Manual identification of tree species is time-consuming and requires expert knowledge. This project aims to automate the process using deep learning techniques, specifically CNNs, to classify images of tree leaves into their corresponding species with high accuracy.

---

## 💡 Solution Overview

To address this challenge, we:

- Preprocessed and augmented the dataset of leaf images
- Built a CNN using TensorFlow/Keras
- Trained and validated the model on split data
- Evaluated model performance primarily using accuracy
- Achieved ~90% test accuracy, ensuring the model is reliable for classification tasks

---

## 🧠 Methodology

1. **Platform Used**: Google Colab (for training, evaluation, and visualization)
2. **Data Preprocessing**:
   - Rescaling images
   - Image augmentation (rotation, flip, zoom, etc.)
   - Target size set to 128x128 pixels
3. **Data Split**:
   - **Train**: 80%
   - **Validation**: 20%
4. **Model Architecture**:
   - Convolutional + MaxPooling layers
   - Flatten + Dense layers
   - Activation: ReLU & Softmax
5. **Training**:
   - Optimizer: Adam
   - Loss Function: Categorical Crossentropy
   - Epochs: Tuned for best performance
6. **Evaluation**:
   - Metric Used: Accuracy
   - Achieved close to **90% accuracy** on test data

---

## 🧰 Tools & Technologies Used

| Category           | Details                                       |
|-------------------|-----------------------------------------------|
| **ML Type**        | Supervised Learning                           |
| **Model**          | Convolutional Neural Network (CNN)            |
| **Library/Frameworks** | TensorFlow, Keras, NumPy, Matplotlib      |
| **Dataset**        | Tree species images (leaf photos)            |
| **Environment**    | Google Colab                                  |
| **Evaluation Metric** | Accuracy                                   |

---

## 📈 Results

- Final model accuracy: **~90%**
- Capable of classifying unseen leaf images reliably
- Efficient, scalable, and adaptable for mobile or embedded applications

---

## 📌 Conclusion

This project demonstrates how CNNs can be effectively used to automate biological classification problems. By achieving high accuracy without overfitting, this approach paves the way for integrating deep learning models in environmental monitoring and botanical research.

---

## 🔮 Future Scope

- Deploy as a web/mobile app for real-time classification  
- Add more diverse species to improve generalization  
- Use Grad-CAM to visualize model focus regions  

---

## Drive Link (for dataset and CNN.h5 file)

https://drive.google.com/drive/folders/1E8FQJkblB4L0tKrYr6NWYgqnzpVg4a2s?usp=drive_link

---

## PPT link

https://www.canva.com/design/DAGuvUcMWHw/JSBs_xWosZeiSofzbV--Hg/edit?utm_content=DAGuvUcMWHw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

