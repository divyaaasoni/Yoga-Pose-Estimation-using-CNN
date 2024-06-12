# Yoga-Pose-Estimation-using-CNN
# Table of Contents
*  Overview
*  Features
*  Installation
*  Usage
*  Models
*  Dataset
*  Results
*  Contributing
*  License
*  Acknowledgements

# Overview
This project aims to estimate yoga poses using Convolutional Neural Networks (CNNs). It incorporates histogram equalization for image preprocessing and SHap (SHapley Additive exPlanations) for model interpretability. The primary goal is to create an efficient and accurate model that can be used in fitness applications, virtual yoga classes, or pose correction tools.

# Features
*  Pose Detection: Accurately detects and classifies various yoga poses.
*  Image Preprocessing: Utilizes histogram equalization to enhance image contrast.
*  Model Interpretability: Employs SHap to interpret the model's predictions.
*  Image Upload: Allows users to upload images for pose estimation.
*  Jupyter Notebook: All functionality is encapsulated in an easy-to-use Jupyter Notebook interface.

# Installation
Prerequisites
Python 3.7 or higher
pip package manager

#  Clone the Repository
git clone https://github.com/divyaaasoni/Yoga-Pose-Estimation-using-CNN.git

#  Install Dependencies
pip install tensorflow keras numpy pandas matplotlib scikit-learn opencv-python shap

#  Usage
# Running the Notebook
To run the notebook, open yoga_pose_estimation.ipynb in Jupyter Notebook or Jupyter Lab. Ensure you have the dataset downloaded and properly referenced in the notebook.
jupyter notebook yoga-pose-classifier-scratchcnn.ipynb

#  Models
The model is built using Convolutional Neural Networks (CNN) with a focus on accurately identifying yoga poses. Histogram equalization is used to enhance the contrast of input images, improving the model's performance. SHap is employed to provide explanations for the model's predictions, making it easier to understand which features influence the output.

#  Dataset
The dataset used for this project contains images of various yoga poses and is divided into training and testing sets. You can download the dataset from the following link:
Download Dataset https://drive.google.com/drive/folders/19N_6SR3OMEQsyybJyub2UCOq0l8gnnsX?usp=sharing

#  Results
The model achieves an accuracy of 87.65957446808511 on the test set. Below are some sample predictions:
Additionally, SHap visualizations help interpret the model's predictions

# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

1.  Fork the Project
2.  Create your Feature Branch (git checkout -b feature/YourFeature)
3.  Commit your Changes (git commit -m 'Add some YourFeature')
4.  Push to the Branch (git push origin feature/YourFeature)
5.  Open a Pull Request

#  License
This project is licensed under the MIT License - see the LICENSE file for details.

#  Acknowledgements
-  OpenPose for inspiration on pose estimation techniques.
-  TensorFlow and Keras for the deep learning framework.
-  SHap for model interpretability.
-  The yoga community for providing valuable datasets and feedback.


