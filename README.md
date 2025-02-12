# **Deepfake Detection Using CNNs**

## **Overview**
This project focuses on detecting deepfake videos using **Convolutional Neural Networks (CNNs)**. Deepfakes, powered by AI, manipulate videos to create realistic yet fake content, leading to concerns in misinformation, identity fraud, and security breaches. This system aims to detect such manipulated media with high accuracy.

## **Features**
✅ Implements **CNN-based deepfake detection**
✅ Utilizes **Celeb-DF v2 dataset** for training and evaluation
✅ Detects deepfakes by analyzing **blinking patterns, blending artifacts, and facial inconsistencies**
✅ Achieves **95% accuracy** in distinguishing real and fake videos
✅ Uses **OpenCV and TensorFlow/Keras** for processing and training

## **Dataset**
- The **Celeb-DF v2 dataset** was used, which contains an equal distribution of **real and fake videos**.
- Video frames were extracted and resized to **224x224 pixels** for uniform input.

## **Model Architecture**
The CNN model consists of:
- **Three convolutional layers** to extract visual features
- **Fully connected layers** for binary classification (real/fake)
- **Sigmoid activation function** in the output layer for confidence scoring
- **Adam optimizer** and **binary cross-entropy loss function** for efficient learning

## **Implementation Steps**
1. **Preprocessing**: Frames are extracted, resized, and normalized.
2. **Model Training**: CNN is trained using Celeb-DF v2 data.
3. **Evaluation**: The model predicts whether unseen video frames are real or deepfake.
4. **Performance Analysis**: Accuracy and confidence scores are computed.

## **Results**
📌 Achieved **95% accuracy** on the test set.
📌 Successfully detected deepfake videos based on subtle inconsistencies in facial features.
📌 Performance on unseen data confirmed **strong generalization**.

## **Future Enhancements**
🔹 Improve dataset diversity to handle various deepfake techniques
🔹 Experiment with **transformer-based models** for enhanced accuracy
🔹 Integrate detection with **blockchain-based media verification**

## **Tech Stack**
- **Programming Language**: Python
- **Frameworks**: TensorFlow, Keras, OpenCV
- **Tools**: NumPy, Matplotlib, Pandas

## **Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/AhmedFarah5/deepfake-detection-cnn.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the detection script:
   ```bash
   python detect_deepfake.py --input video.mp4
   ```

## **Contributing**
Feel free to open issues or submit pull requests to improve the model or add new features.

## **License**
This project is licensed under the MIT License.

---
🚀 **Developed by Ahmed Farah**


