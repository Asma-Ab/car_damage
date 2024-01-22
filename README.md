<h1 align="center">
  <br>
  Car Damage Assessment App
</h1>

# Car Damage Assessment App

Welcome to the Car Image Analysis Streamlit App! This interactive application allows you to analyze car images using various algorithms, including AI image detection, damage severity assessment, damaged parts detection, and damage type detection.

# Overview

The application consists of several functionalities:

### 1. AI-Generated Image Detection

Determine whether the uploaded image is AI-generated or not.

### 2. Damage Severity Classification

Predict the severity of the damage in the car image. It can be Minor, Moderate, or Severe.

### 3. Damaged Parts Detection

Detect and highlight damaged parts and the damage type in the car image.


# Getting Started

Follow these steps to set up and run the Car Damage Assessment Streamlit App:

1. Clone the repository:

   ```bash
   git clone https://github.com/Asma-Ab/car-damage.git
2. Install the required dependencies:
    ```bash
   pip install -r requirements.txt
3. Run the Streamlit app :
    ```bash
    streamlit run streamlit_app.py
4. Open your browser and navigate to the provided local URL to access the app.

# Models

The application uses the following models:

- **Real OR AI-Generated Image Detection:**
    - Trained models:
      - Convolutional Neural Network (CNN) model
      - Inception V3
      - VGG16

- **Damage Severity Assessment:**
  - The dataset used in this part is: [Car Damage Severity Dataset](https://www.kaggle.com/datasets/prajwalbhamere/car-damage-severity-dataset).
    - Trained models:
      - Inception V3
      - Convolutional Neural Network (CNN) model
      - DenseNet
      - EfficientNet

- **Damaged Parts and Type Detection:**
  - YOLOv8.
  - Detectron2
# Access the Live Streamlit App
 Explore the Car Damage Assessment App hosted on Streamlit **[Car Image Analysis App](https://aiornot.streamlit.app/) 🚀

