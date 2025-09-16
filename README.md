# Rock-vs-Mine-Predictor using SONAR 

This is my first machine learning project where i learnt about logistic regression model which is used for binary classification.

## 📖 About

The Rock vs Mine Predictor is a machine learning project aimed at improving underwater navigation and safety for submarines. Submarines rely on sonar signals to identify objects in their path, but distinguishing between harmless rocks and dangerous mines can be challenging, especially in noisy underwater environments.

## 📂 Dataset

The dataset used in this project consists of sonar signal returns collected from underwater objects such as metal mines and rocks. Each sample contains features extracted from sonar reflections, which help the model distinguish between rocks and mines based on their acoustic signatures.

The dataset is sourced from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines,+Rocks)) and includes:
- 208 samples with 60 numerical features each
- Labels indicating whether the object is a rock or a mine

## 🔗 Link to Colab

You can explore and run the **Rock vs Mine Predictor** project directly in Google Colab using the following link:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/15NVu0AEyuqq102IfW9jz-agMcEYdN6St?usp=sharing)


Feel free to make a copy of the notebook and experiment with different algorithms or parameter settings.

## 🧠 Model

The project uses **Logistic Regression** to classify sonar signals as rocks or mines. The model is trained on normalized sonar data and evaluated using accuracy and precision. It provides a lightweight and efficient solution suitable for real-time submarine navigation.

 - The model is trained using labeled sonar signal data.
 - It learns the relationship between the sonar features and the object type (rock or mine).

## 📚 Learned From

This project was inspired by and implemented with guidance from the following YouTube tutorial:

[Click Here to watch the Tutorial](https://youtu.be/fiz1ORTBGpY?si=EeYE1wLjojeVmSgS)
