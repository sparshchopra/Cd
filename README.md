# Cd readme 
 Medical Image Model Compiler using Genetic Algorithms
This project implements an automatic neural network architecture optimizer for medical image classification, leveraging a Genetic Algorithm (GA) to evolve the best model configurations over generations.

The code supports training on both standard image formats (.png, .jpg, .jpeg) and DICOM (.dcm) files.

🚀 Features
📦 Genetic Algorithm for model hyperparameter tuning and architecture optimization

📊 Multi-class image classification

🏥 DICOM support for medical datasets

🧠 Custom CNN architecture generation

⚙️ Dynamic mutation and crossover strategies

💾 Memory usage monitoring

🧪 Built-in training and validation pipeline

🧰 Requirements
bash
Copy
Edit
pip install pydicom opencv-python-headless psutil
This project also uses:

TensorFlow / Keras

NumPy

OpenCV

Google Colab (for Drive mounting and GPU usage)

📁 Project Structure
bash
Copy
Edit
.
├── main.py
├── /drive
│   └── classifier.v1i.clip/
│       ├── train/
│       └── valid/
Each class should be a folder inside train/ or valid/, containing medical images.
