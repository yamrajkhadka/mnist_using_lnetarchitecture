# MNIST Digit Classification using LeNet

This project implements a **LeNet CNN model** to classify handwritten digits from the **MNIST dataset**. It also includes a script for making predictions on custom images.

## 🚀 Features
✅ **LeNet Architecture** implemented with TensorFlow & Keras  
✅ **MNIST Dataset** for training & evaluation  
✅ **Custom Image Prediction** using OpenCV & Matplotlib  
✅ **Visualization** of model predictions & confidence scores  

---

## 📂 Project Structure
├── model.py # Defines and trains the LeNet model ├── predict.py # Loads model & makes predictions on new images ├── README.md # Project documentation ├── requirements.txt # Dependencies list

yaml
Copy
Edit

---

## 🔧 Installation & Usage
1️⃣ **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/mnist-lenet.git
   cd mnist-lenet
2️⃣ Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Train the model

bash
Copy
Edit
python model.py
4️⃣ Make a prediction on a custom image

bash
Copy
Edit
python predict.py --image path/to/image.jpg
🏗 Model Architecture (LeNet)
Conv Layer 1: 6 filters (5x5), tanh

Avg Pooling 1

Conv Layer 2: 16 filters (5x5), tanh

Avg Pooling 2

Fully Connected 1: 120 neurons, tanh

Fully Connected 2: 84 neurons, tanh

Output Layer: 10 neurons, softmax

📊 Training Results
Training Accuracy: ~99.55%

Test Accuracy: ~98.13%

🛠 Dependencies
tensorflow

numpy

opencv-python

matplotlib

Install using:

bash
Copy
Edit
pip install tensorflow numpy opencv-python matplotlib
