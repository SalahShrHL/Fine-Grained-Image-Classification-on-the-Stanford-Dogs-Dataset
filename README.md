## 📌 Project Overview
This project explores Fine-Grained Image Classification for distinguishing between visually similar dog breeds. Unlike general classification tasks (e.g., dog vs. cat), the focus is on sub-category recognition using the Stanford Dogs Dataset.

The work compares a custom CNN architecture trained from scratch with a Transfer Learning approach based on the Xception model, showing improved performance after fine-tuning.

## 📊 Performance Results
The fine-tuned Xception model demonstrated robust generalization:
- **Top-1 Accuracy:** 88%
- **Top-3 Accuracy:** 98%
- **Key Insight:** Most misclassifications occurred between visually identical breeds like the *Samoyed* and *Great Pyrenees*, which was analyzed using a Confusion Matrix.

## 🛠️ Tech Stack
- **Frameworks:** TensorFlow, Keras
- **Libraries:** OpenCV (Image processing), Matplotlib (Visualization), Scikit-learn
- **Environment:** Google Colab / GPU acceleration

