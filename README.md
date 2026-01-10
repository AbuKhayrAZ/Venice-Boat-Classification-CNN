# 🚤 Venice Boat Classification using Deep Learning

## 📌 Project Overview
This project involves building a Convolutional Neural Network (CNN) to classify different types of boats found in Venice. Utilizing **TensorFlow** and **Keras**, the model processes image data to identify distinct boat categories, aiding in automated maritime traffic monitoring.

## 🛠️ Tech Stack
* **Deep Learning:** TensorFlow, Keras (Conv2D, MaxPooling, Dropout)
* **Data Processing:** Pandas, NumPy, ImageDataGenerator
* **Visualization:** Matplotlib, Seaborn
* **Platform:** Google Colab, VsCode

## 📂 Project Structure
* **Data Exploration:** Analysis of image variance across different boat categories (Gondolas, Vaporettos, etc.).
* **Model Engineering:** Development of a multi-class CNN classifier.
* **Visualization:** Plotting training vs. validation accuracy/loss to monitor convergence.

* ## 🧠 Model Architecture
The model utilizes a deep architecture featuring:
* **Convolutional Layers:** To extract spatial features from the boat structures.
* **Batch Normalization:** To accelerate training and provide stability.
* **Dropout (0.5):** To ensure the model generalizes well to new images of the Venice canals.
* **Softmax Output:** For multi-class classification across 6+ boat categories.
* 
## 📊 Key Results
* **Model Architecture:** Custom CNN with Sequential layers.
* **Validation Accuracy:** ~68% (0.68)
* **Key Features:**
    * Implemented data augmentation to improve model generalization.
    * Utilized categorical cross-entropy loss for multi-class classification.
    * Visualized training loss and accuracy curves to monitor overfitting.

## 🔑 Key Insights
* Achieved robust classification by handling variations in lighting and water reflections.
* Demonstrated proficiency in data pipelining, from raw image loading to one-hot encoding labels.

## 🚀 How to Run
1.  Click the "Open in Colab" button at the top of the notebook file.
2.  Upload your dataset to the runtime or mount Google Drive.
3.  Run all cells to train the model or load the saved weights.

---
*Created by **Azeez Ajibola** - [LinkedIn](https://linkedin.com/in/azeez-ajibola)
