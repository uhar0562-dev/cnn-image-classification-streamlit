# CNN Image Classification and Student Marks Calculator

## 📌 Project Overview
This project consists of two applications developed using Python as part of an assignment.

- **Part A – CNN Image Classification:** A Convolutional Neural Network (CNN) is developed using the MNIST dataset to classify handwritten digits from 0 to 9.
- **Part B – Student Marks Calculator:** A Streamlit web application that calculates a student's total marks, average, percentage, and pass/fail result.

## 🎯 Objectives
- Understand and implement CNN for image classification.
- Preprocess image data and train a deep learning model.
- Evaluate model performance using accuracy and loss.
- Develop an interactive web application using Streamlit.
- Apply Python programming concepts to practical applications.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Streamlit
- Google Colab

## 🧠 Part A: CNN Image Classification

**Dataset:** MNIST Handwritten Digits Dataset

The MNIST dataset contains grayscale images of handwritten digits from 0 to 9.

### Workflow
1. Load the MNIST dataset.
2. Explore the dataset and display sample images.
3. Normalize image pixel values.
4. Reshape images for CNN input.
5. Build a CNN model using convolutional, pooling, and dense layers.
6. Train the model.
7. Evaluate the model using test data.
8. Display predictions and compare actual labels with predicted labels.

## 📚 Part B: Student Marks Calculator

A simple interactive web application developed using Streamlit.

### Features
- Enter student name.
- Enter marks for five subjects.
- Calculate total marks out of 500.
- Calculate average marks.
- Calculate percentage.
- Display pass or fail result.
- Display individual subject marks.
- Validate student name and subject marks.

## 🚀 How to Run

### CNN Notebook
Open the CNN notebook in Google Colab and run the cells sequentially.

### Streamlit Application
Install Streamlit:

```bash
pip install streamlit
```

Run the application:

```bash
streamlit run app.py
```

## 📊 Results
The CNN model predicts handwritten digits from the MNIST dataset. The Student Marks Calculator successfully calculates total marks, average, percentage, and pass/fail status based on the entered marks.

## 📝 Conclusion
This project demonstrates the application of deep learning for image classification and Python-based web application development using Streamlit.

---
**Developed as part of an academic assignment.**
