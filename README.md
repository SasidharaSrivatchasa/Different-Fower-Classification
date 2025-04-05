# Different-Fower-Classification
# 🌸 Flower Classification using Deep Learning

**Project ID:** PRAICP-1008 - Different Flowers Classification

## Business Case

The objective of this project is to develop a deep learning model that can classify five types of flowers using image data. This project demonstrates the use of convolutional neural networks (CNNs) and transfer learning to solve real-world image classification problems. The model can be utilized in fields such as agriculture, education, and mobile plant identification apps.

---

## Project Goal

Develop a robust, generalized deep learning model capable of accurately classifying the following five flower categories:

- Daisy
- Dandelion
- Rose
- Sunflower
- Tulip

---

## Dataset Overview

- The dataset is organized into five directories representing each flower class.
- An 80:20 train-validation split was used.
- Sample images are resized to 150x150 pixels for training.

---

## Tools & Technologies Used

- **Python**
- **Google Colab**
- **TensorFlow / Keras**
- **MobileNetV2** (Pretrained model for transfer learning)

---

## Model Workflow

1. **Data Augmentation** - Performed to enhance dataset and prevent overfitting.
2. **Transfer Learning** - Used MobileNetV2 with pretrained weights (ImageNet).
3. **Dropout Layers** - Applied to reduce overfitting and increase generalization.
4. **Loss Function** - Categorical Crossentropy.
5. **Optimizer** - Adam optimizer for efficient training.
6. **Training Epochs** - Trained for 15 epochs.
7. **Evaluation** - Tracked training and validation accuracy and loss.
8. **Model Saving** - Trained model saved as `.h5` file.

---

## Training Results

- **Final Training Accuracy:** 85.52%
- **Final Validation Accuracy:** 86.84%
- **Final Training Loss:** 0.3736
- **Final Validation Loss:** 0.3903

---

## Challenges Faced

- Dataset was moderately small; data augmentation helped to mitigate overfitting.
- Initial attempts using a custom CNN resulted in overfitting.
- Required careful tuning of Dropout and learning rate to stabilize training.

---

## Conclusion

The model achieved high accuracy and generalization capability with limited data by leveraging transfer learning with MobileNetV2 and image augmentation. It is suitable for deployment in real-world scenarios such as mobile applications and educational tools.

---

## Future Improvements

- Fine-tune more layers of the base MobileNetV2 model.
- Increase training epochs with early stopping.
- Add more flower classes for greater applicability.
- Export model for mobile or web deployment (e.g., TensorFlow Lite).


