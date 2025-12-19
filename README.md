# Brain Tumor Detection using Deep Learning

This project focuses on detecting **brain tumors from MRI images** using **Deep Learning techniques**. A **Convolutional Neural Network (CNN)** model is trained to classify MRI scans as **tumor** or **non-tumor**, helping in early and accurate diagnosis.



## Project Overview

Brain tumor detection through manual inspection of MRI scans is time-consuming and error-prone. This project automates the detection process using **TensorFlow and Keras**, enabling faster and more reliable classification of MRI images.

The complete implementation is provided with data preprocessing, model training, evaluation, and prediction.



##  Technologies Used

- Python  
- TensorFlow  
- Keras  
- NumPy  
- OpenCV  
- Matplotlib  



## Dataset

- MRI brain images
- Two classes:
  - **Tumor**
  - **No Tumor**
- Images are resized and normalized before training

*(Dataset path can be updated inside the notebook as required)*

---

## Methodology

1. Load and preprocess MRI images  
2. Normalize image pixel values  
3. Build a CNN model using Keras  
4. Train the model on labeled data  
5. Evaluate performance using accuracy  
6. Predict tumor presence on new MRI images  



## Model Architecture

- Convolutional layers for feature extraction  
- MaxPooling layers for dimensionality reduction  
- Fully connected (Dense) layers for classification  
- Sigmoid activation for binary classification  



##  Results

- The trained CNN model successfully classifies MRI images
- Achieves good accuracy on validation data
- Capable of predicting tumor presence in unseen images


##  How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/brain-tumor-detection.git
   
   ```
2. Navigate to the project directory
   
   ```bash

   cd brain-tumor-detection

   ```


3. Open the notebook
  
  ```bash

   jupyter notebook brain-tumor-detection-project.ipynb

  ```


4. Run all cells sequentially
   

## Future Improvements

-Use transfer learning (VGG16, ResNet, EfficientNet)

-Improve accuracy with data augmentation

-Add multi-class tumor classification

-Deploy as a web application
