
# 🌱 Potato Leaf Disease Prediction

This project focuses on detecting and classifying potato leaf diseases using deep learning. By leveraging TensorFlow and Streamlit, the system provides an easy-to-use web interface where users can upload images of potato leaves, and the trained model predicts whether the leaf is healthy or affected by Early Blight or Late Blight. The goal is to assist farmers in diagnosing plant diseases efficiently, leading to improved crop health and yield.


## 🏗️ Features

📷 Image Upload: Users can upload images of potato leaves through the web interface.

🔬 Deep Learning Model: A Convolutional Neural Network (CNN) trained on a dataset of potato leaf images.

🎯 Disease Classification: Predicts if a potato leaf is Healthy, has Early Blight, or Late Blight.

🌍 User-Friendly Web App: Built using Streamlit for an interactive experience.

📊 Real-Time Predictions: Displays classification results instantly.
## 🏗️ Project Structure

```bash
├── Train_potato_disease.ipynb         # Model training notebook
├── Test_plant_disease.ipynb           # Model testing notebook
├── trained_plant_disease_model.keras  # Trained model file
├── web.py                             # Streamlit web app for disease detection
├── plant.jpg                          # Sample plant image
├── requirements.txt                   # Required dependencies
├── settings.json                      # VSCode settings
```
    
## 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/potato-leaf-disease-prediction.git
cd potato-leaf-disease-prediction
```
2. Install dependencies:

```bash
pip install -r requirements.txt
```
3. Run the Streamlit app:

```bash
streamlit run web.py
```
## 🎯 How It Works

1. Upload a potato leaf image.
2. The model analyzes the image and predicts the disease category.
3. The result is displayed on the web interface.
## 📌 Future Improvements

1. Improve model accuracy by training on a larger dataset.
2. Extend support for more plant diseases.
3. Deploy the model as a cloud-based API.
## 📩 Contact

For queries, feel free to reach out at [omkarchoudhury0706@example.com] or open an issue on GitHub.