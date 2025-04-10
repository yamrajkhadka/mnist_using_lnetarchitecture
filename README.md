# 🖥️ MNIST Digit Classification using LeNet

A deep learning project implementing the **LeNet-5 Convolutional Neural Network (CNN)** to classify handwritten digits from the **MNIST dataset** using TensorFlow and Keras. The model achieves high accuracy and includes functionality to predict custom images.

---

## 📌 Table of Contents
- [📌 Table of Contents](#-table-of-contents)
- [📜 About the Project](#-about-the-project)
- [🚀 Features](#-features)
- [🛠 Tech Stack & Dependencies](#-tech-stack--dependencies)
- [📂 Project Structure](#-project-structure)
- [⚡ Installation & Usage](#-installation--usage)
- [🏗 Model Architecture](#-model-architecture)
- [📊 Training Results](#-training-results)


---

## 📜 About the Project
This project trains and evaluates a **LeNet CNN model** to classify digits from the **MNIST dataset**. Additionally, it allows users to make predictions on **custom images** by preprocessing and feeding them into the trained model.

---

## 🚀 Features
✅ **LeNet CNN Model** implemented using TensorFlow & Keras  
✅ **Trained on the MNIST dataset** achieving ~99.55% accuracy  
✅ **Custom Image Prediction** using OpenCV & Matplotlib  
✅ **Visualization** of model performance and predictions  
✅ **Easy-to-use scripts** for training and inference  

---

## 🛠 Tech Stack & Dependencies
- **Language:** Python  
- **Libraries:** TensorFlow, NumPy, OpenCV, Matplotlib  

**Install dependencies:**
```bash
pip install tensorflow numpy opencv-python matplotlib
📂 Project Structure
bash
Copy
Edit
📂 mnist-lenet
├── model.py                 # Defines and trains the LeNet model
├── predict.py               # Loads model & makes predictions on new images
├── README.md                # Project documentation
├── requirements.txt         # Dependencies list
⚡ Installation & Usage
🔹 1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/yourusername/mnist-lenet.git
cd mnist-lenet
🔹 2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
🔹 3. Train the Model
bash
Copy
Edit
python model.py
This will train the LeNet model on the MNIST dataset.

🔹 4. Make a Prediction on a Custom Image
bash
Copy
Edit
python predict.py --image path/to/image.jpg
Replace path/to/image.jpg with the path of your custom image.

🏗 Model Architecture (LeNet-5)
Layer Type	Filters	Kernel Size	Activation
Conv2D	6	(5,5)	Tanh
Avg Pooling	-	(2,2)	-
Conv2D	16	(5,5)	Tanh
Avg Pooling	-	(2,2)	-
Flatten	-	-	-
Dense (FC1)	120	-	Tanh
Dense (FC2)	84	-	Tanh
Output Layer	10	-	Softmax
📊 Training Results
The model was trained for 10 epochs and achieved the following results:

Training Accuracy: ~99.55%

Test Accuracy: ~98.13%




