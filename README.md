# P1-Implementation-of-ML-model-for-image-classification
Implementation-of-ML-model-for-image-classification
Implementation-of-ML-model-for-image-classification is a Streamlit app that integrates MobileNetV2 and a CIFAR-10 model for image classification. Users can upload images and receive predictions with confidence scores from either model. It features a sleek navigation bar for easy switching and real-time results, which is ideal for learning and practical use.

Key Features
Dual Model Support:

MobileNetV2 (ImageNet): Recognizes 1,000 different classes from the ImageNet dataset, including everyday objects, animals, and vehicles.
Custom CIFAR-10 Model: Specializes in classifying images into one of ten specific categories such as airplanes, automobiles, and birds.
Intuitive Interface:

Navigation Bar: Seamlessly switch between MobileNetV2 and CIFAR-10 models using a sleek sidebar menu.
Real-Time Classification: Upload an image to receive immediate predictions with confidence scores.
Educational and Practical Use:

Ideal for learning about deep learning models and their performance.
Useful for practical applications where image classification is needed.
Getting Started
Prerequisites
Python 3.7 or later
A web browser
Installation
Clone the repository:

git clone https://github.com/JayRathod341997/DeepLensX.git
cd Implementation-of-ML-model-for-image-classification
Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
Install the required packages:

pip install -r requirements.txt
Start the Streamlit app:

streamlit run app.py
Acknowledgements
Streamlit
TensorFlow
