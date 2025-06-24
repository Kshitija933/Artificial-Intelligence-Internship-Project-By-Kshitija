
# PROJECT SUMMARY AND OVERVIEW

This repository contains two applied AI projects developed during my internship to explore practical implementations of machine learning and deep learning. 
Each project is built using real-world datasets and demonstrates how AI can solve classification problems in both text and image formats.

---

# 🧠 Handwritten Digit Recognizer (Image Classification)

## 🛠️ What I Did:
- Used the **MNIST Handwritten Digit Dataset** to train a model that recognizes digits (0–9) from images.
- Loaded and preprocessed image data by **normalizing pixel values** and **reshaping** for CNN input.
- Converted digit labels into one-hot encoded format using `to_categorical()`.
- Built a **Convolutional Neural Network (CNN)** using Keras with layers like `Conv2D`, `MaxPooling2D`, and `Dense`.
- Trained the model using the **Adam optimizer** and `categorical_crossentropy` loss.
- Evaluated the model’s performance using test accuracy and saved the trained model for reuse.

## 💡 What I Learned:
- How to prepare image data for training using deep learning techniques.
- Built a practical understanding of **CNNs** and how they extract spatial features from images.
- Importance of **normalization**, **reshaping**, and **label encoding** in deep learning.
- Gained experience in working with **TensorFlow/Keras** for image classification.
- Understood real-world use cases of digit recognition in applications like OCR and form automation.

---

# 📩 Spam Email Classifier (Text Classification)

## 🛠️ What I Did:
- Used the **SMS Spam Collection Dataset** to detect spam messages.
- Cleaned and preprocessed the data using **pandas** by removing unnecessary columns.
- Converted text to numeric form using **CountVectorizer** for feature extraction.
- Trained a **Naive Bayes classifier** to classify messages as spam or not spam (ham).
- Evaluated model accuracy and performance using metrics like **precision**, **recall**, **F1-score**, and **accuracy**.

## 💡 What I Learned:
- How to clean and transform **text data** into machine-readable format.
- Learned about **NLP pipelines**: text preprocessing → vectorization → classification.
- Understood how **supervised learning** models like Naive Bayes can be applied to text.
- Gained skills in evaluating classification models and interpreting their results.
- Applied AI techniques to solve a real-world communication problem: spam detection.
