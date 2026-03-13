# 🐱🐶 Cat vs Dog Image Classifier (Transfer Learning)

This project implements a **Binary Image Classification Model** using **TensorFlow and Transfer Learning with InceptionV3**.

The model classifies whether an image contains a **Cat or Dog**.

---

# 🚀 Project Overview

Deep learning models usually require large datasets and training time.  
To overcome this, we used **Transfer Learning with InceptionV3 pretrained on ImageNet**.

Key Features:

- Transfer Learning using InceptionV3
- Data Augmentation
- Binary Classification
- TensorFlow/Keras
- Training Visualization

---

# 🧠 Model Architecture

Base Model:
InceptionV3 (ImageNet Pretrained)

Custom Layers:

Flatten  
Dense (1024 ReLU)  
Dropout (0.2)  
Dense (1 Sigmoid)

Loss Function:
Binary Crossentropy

Optimizer:
RMSprop

---

# 📂 Dataset Structure

dataset/

train/
cats/
dogs/

validation/
cats/
dogs/

---

# 📊 Training Results

The model was trained for **20 epochs** with data augmentation.

Metrics:

Training Accuracy  
Validation Accuracy  
Training Loss  
Validation Loss

Graphs are generated using **Matplotlib**.

# 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib


# 👨‍💻 Author

Asif  
BS Computer Science Student  
Interested in AI Engineering, Machine Learning and Data Science.

