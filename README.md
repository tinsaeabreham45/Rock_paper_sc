# Rock Paper Scissors Image Classifier

## 📌 Project Overview
This project is a Convolutional Neural Network (CNN) model designed to classify images of hand gestures representing **Rock, Paper, and Scissors**. The model is trained using TensorFlow and Keras and leverages data augmentation to enhance generalization.

## 🛠️ Technologies Used
- **Python**
- **TensorFlow/Keras** for deep learning
- **Matplotlib** for visualization
- **Jupyter Notebook** for experimentation


## 🏗️ Model Architecture
The CNN model consists of:
- Convolutional layers with ReLU activation
- MaxPooling layers for downsampling
- Fully connected dense layers
- Softmax activation for multi-class classification

## 📊 Training & Evaluation
- **Dataset:** Custom dataset of Rock, Paper, and Scissors images
- **Loss Function:** `categorical_crossentropy`
- **Optimizer:** `adam`
- **Metrics:** `accuracy`
- **Data Augmentation:** Used to improve generalization


4. Run the notebook cells to train and evaluate the model.

## 🔍 Results & Performance
- Training accuracy: **~97%**
- Validation accuracy: **Varies (~60-70%)**
- The model slightly overfits, so further fine-tuning is needed.

## 🛠️ Improvements & Next Steps
- Increase dataset size for better generalization.
- Experiment with different CNN architectures (ResNet, MobileNet, etc.).
- Implement transfer learning for better performance.
- Deploy model using Flask or FastAPI.

## 🤝 Contributing
Feel free to fork the repo and improve the model. PRs are welcome!
Please play with it 


