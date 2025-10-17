👇

🧠 Face Mask Detection using Deep Learning
📘 Overview

The Face Mask Detection project is a deep learning–based system designed to detect whether a person is wearing a face mask or not in real-time. This project leverages Convolutional Neural Networks (CNNs) and OpenCV to classify faces into two categories — "Mask" and "No Mask" — using images or live webcam feeds.

🚀 Features

Real-time face mask detection using a webcam

Pre-trained deep learning model for accurate classification

Detection of multiple faces simultaneously

Fast and efficient using OpenCV and TensorFlow/Keras

Easy-to-use interface

🧩 Tech Stack

Programming Language: Python

Libraries & Frameworks: TensorFlow / Keras, OpenCV, NumPy, Matplotlib

Model: CNN trained on face mask dataset (e.g., Kaggle Face Mask Dataset)

📊 Workflow

Data Collection: Collect and preprocess images of people with and without masks.

Model Training: Train a CNN model to classify mask/no-mask images.

Face Detection: Use OpenCV’s Haar Cascade or DNN to detect faces in frames.

Prediction: Pass each detected face through the trained model.

Display Result: Draw a rectangle and label around the detected face (Mask / No Mask).

🖼️ Example Output

✅ Person with Mask — Green box
❌ Person without Mask — Red box

🧪 How to Run
# Clone the repository
git clone https://github.com/shreyanshPandey1177/face-mask-detection.git
cd face-mask-detection

# Install dependencies
pip install -r requirements.txt

# Run detection script
python detect_mask_video.py

📦 Dataset

You can use:

Kaggle Face Mask Detection Dataset

Or create your own dataset using image scraping tools

💡 Future Improvements

Integration with CCTV or surveillance systems

Mobile-friendly version using TensorFlow Lite

Improved accuracy with transfer learning (e.g., MobileNetV2)

👨‍💻 Author

Shreyansh Pandey
