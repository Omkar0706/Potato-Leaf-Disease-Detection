🌱 Potato Leaf Disease Prediction

📌 Project Overview

This project focuses on detecting and classifying potato leaf diseases using deep learning. By leveraging TensorFlow and Streamlit, the system provides an easy-to-use web interface where users can upload images of potato leaves, and the trained model predicts whether the leaf is healthy or affected by Early Blight or Late Blight. The goal is to assist farmers in diagnosing plant diseases efficiently, leading to improved crop health and yield.

🏗️ Features

📷 Image Upload: Users can upload images of potato leaves through the web interface.
🔬 Deep Learning Model: A Convolutional Neural Network (CNN) trained on a dataset of potato leaf images.
🎯 Disease Classification: Predicts if a potato leaf is Healthy, has Early Blight, or Late Blight.
🌍 User-Friendly Web App: Built using Streamlit for an interactive experience.
📊 Real-Time Predictions: Displays classification results instantly.

🏗️ Project Structure

├── Train_potato_disease.ipynb    # Model training notebook

├── Test_plant_disease.ipynb      # Model testing notebook

├── trained_plant_disease_model.keras  # Trained model file

├── web.py                        # Streamlit web app for disease detection

├── plant.jpg                     # Sample plant image

├── requirements.txt               # Required dependencies

├── settings.json                  # VSCode settings

🛠️ Installation

Clone the repository:

git clone https://github.com/yourusername/potato-leaf-disease-prediction.git

cd potato-leaf-disease-prediction

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run web.py

📜 Dataset

The model is trained on a dataset of potato leaf images, categorized into:

Potato___Healthy

Potato___Early_Blight

Potato___Late_Blight

The dataset is preprocessed and augmented to improve model performance.

🧠 Model Details

Architecture: Convolutional Neural Network (CNN)


Input Image Size: 128x128 pixels


Framework: TensorFlow/Keras


Loss Function: Categorical Crossentropy


Optimizer: Adam


🎯 How It Works

Upload a potato leaf image.

The model analyzes the image and predicts the disease category.

The result is displayed on the web interface.

📌 Future Improvements

Improve model accuracy by training on a larger dataset.

Extend support for more plant diseases.

Deploy the model as a cloud-based API.

📩 Contact

For queries, feel free to reach out at [omkarchoudhury0706.com] or open an issue on GitHub.
