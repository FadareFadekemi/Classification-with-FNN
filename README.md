# Classification-with-FNN
🧠 Breast Cancer Classification with FNN

This project uses a Feedforward Neural Network (FNN/MLP) built with TensorFlow/Keras to classify breast tumors as malignant or benign using the Breast Cancer Wisconsin dataset.

📂 Dataset

•	569 samples, 30 features

•	Target: 0 = malignant, 1 = benign

•	Source: sklearn.datasets.load_breast_cancer

⚙ Model

•	Input: 30 features

•	Hidden layers: [16 → 8 → 4], ReLU activation

•	Output: 1 neuron, sigmoid activation

•	Loss: Binary Crossentropy

•	Optimizer: Adam

•	Regularization: Dropout + L2, EarlyStopping

📈 Results

•	Training Accuracy: ~0.99

•	Validation Accuracy: ~0.95–0.96

🚀 Run the Project

git clone https://github.com/FadareFadekemi/Classification-with-FNN.git

cd Classification-with-FNN

pip install -r requirements.txt

python train.py

requirements.txt



