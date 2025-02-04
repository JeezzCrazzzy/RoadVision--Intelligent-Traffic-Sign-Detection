# RoadVision--Intelligent-Traffic-Sign-Detection

### 🚀 Traffic Sign Recognition is a deep learning-based system that classifies and detects traffic signs in real time. This project leverages Convolutional Neural Networks (CNNs) to identify road signs with high accuracy, making it useful for autonomous driving and traffic management applications.


### 📌 Features
✅ Deep Learning-Based Classification – Uses CNNs for high-accuracy sign recognition.
✅ Real-Time Detection – Efficiently processes live camera feeds or images.
✅ Robust Data Augmentation – Improves model generalization with diverse training data.
✅ Scalable Deployment – Integrated with Flask & OpenCV for real-time use.
✅ High Accuracy – Achieves 95%+ accuracy on standard traffic sign datasets.

### 🛠 Tech Stack
Deep Learning Frameworks: TensorFlow, Keras, PyTorch
Image Processing: OpenCV, PIL
Dataset: German Traffic Sign Recognition Benchmark (GTSRB)
Backend: Flask (for API deployment)
Programming Language: Python
Deployment: Flask, Docker

### 🚀 Installation & Setup
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/jainharshit2408/Traffic-Sign-Recognition.git
cd Traffic-Sign-Recognition
2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Train the Model (Optional, if retraining is needed)
bash
Copy
Edit
python train.py
4️⃣ Run the Application
bash
Copy
Edit
python app.py
The application will be accessible at http://localhost:5000

### 🔥 Usage
1️⃣ Upload an Image:

Visit http://localhost:5000
Upload a traffic sign image
Get the predicted classification
2️⃣ Use API for Classification:
Send a POST request using Postman or curl:

bash
Copy
Edit
curl -X POST "http://localhost:5000/predict" -F "file=@test_image.jpg"
Response Example:

json
Copy
Edit
{
  "predicted_sign": "Speed Limit 50 km/h",
  "confidence": 97.8
}
🏗 Project Structure
bash
Copy
Edit

### 📦 Traffic-Sign-Recognition
├── 📂 dataset/          # Contains training images
├── 📂 models/           # Pretrained deep learning models
├── 📂 static/           # UI assets (if any)
├── 📂 templates/        # HTML files (if using Flask UI)
├── train.py            # Training script for CNN model
├── app.py              # Flask API for deployment
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation



### 📢 Connect With Me
📧 Email: jayawasthi891@gmail.com

Let me know if you need any modifications! 🚀
