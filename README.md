# Face Mask Detection System

A real-time face mask detection system built using Python, OpenCV, and a Convolutional Neural Network (CNN). This project can detect faces in a live video stream from a webcam and classify whether the person is wearing a mask or not.

# 🚀 Features

· Real-time Detection: Processes webcam feed live to detect faces.
· Mask Classification: Accurately classifies between "Mask" and "No Mask".
· Haar Cascade for Face Detection: Uses OpenCV's pre-trained model for efficient face detection.
· Deep Learning Model: Implements a custom CNN for robust image classification.

# 🛠 Technologies Used

· Python 3
· OpenCV (for computer vision and face detection)
· TensorFlow / Keras (for building and training the CNN model)
· NumPy (for numerical operations)
· Matplotlib (for plotting - if used during training)

# 🖥 How to Run

1. Ensure you are in the project directory and your virtual environment is activated.
2. Run the main Python script:
   bash
   python FACE_DETECTION.PY
   
3. The webcam will activate. A window will open showing the live video feed.
4. The system will draw a bounding box around any detected face and display a label:
   · "Mask" in Green if a mask is detected.
   · "No Mask" in Red if no mask is detected.
5. To exit the application, press the 'q' key.

# 🧠 How It Works

1. Face Detection: The live video frame is processed using the Haar Cascade classifier to identify and locate faces.
2. Preprocessing: Each detected face region is extracted, resized, and normalized to match the input format required by the CNN model.
3. Classification: The preprocessed face is fed into the trained CNN model, which predicts the probability of a mask being present.
4. Output: Based on the model's prediction, the corresponding label and bounding box color are drawn on the video frame in real-time.

# 📝 Model Training (Overview)

The Convolutional Neural Network was likely trained on a dataset comprising two classes:

· With Mask
· Without Mask

The model architecture typically consists of:

· Convolutional Layers for feature extraction.
· Pooling Layers for dimensionality reduction.
· Fully Connected Layers for final classification.

# Author

# Sohail

· GitHub: @Sohai16306180329
