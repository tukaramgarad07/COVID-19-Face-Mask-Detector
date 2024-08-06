# COVID-19 Face Mask Detector

## Overview

This project provides a real-time face mask detection system using Python, OpenCV, and Keras. The system detects whether a person in a webcam feed is wearing a mask or not. It was developed to comply with health guidelines during the COVID-19 pandemic.

## Technologies Used

- **Python**: Programming language used for implementation.
- **OpenCV**: Library for computer vision tasks.
- **Keras**: Library for building and training neural network models.

## Project Features

- **Real-time Mask Detection**: Detects mask-wearing status from live webcam feed.
- **Model Accuracy**: Trained with a comprehensive dataset to ensure high reliability.

## Advantages

- **Utilized a Convolutional Neural Network (CNN)**: Accurately detects and classifies individuals as wearing or not wearing masks in real-time, improving public safety during the pandemic.
- **Implemented OpenCV for Real-Time Processing**: Enables instantaneous detection and alerting for compliance enforcement in public spaces.
- **Employed Data Augmentation Techniques**: Enhances the model’s robustness, ensuring high accuracy and reliability across diverse scenarios and environments.
- **Enhanced Public Health Monitoring**: Assists in ensuring compliance with mask-wearing guidelines, crucial for preventing the spread of COVID-19 and other respiratory illnesses.
- **Scalability and Adaptability**: The model can be retrained with new datasets to adapt to different environments or to improve accuracy.
- **User-Friendly Interface**: Real-time detection script with visual indicators showing mask-wearing status.
- **Reduced Manual Monitoring**: Automates mask compliance checks, reducing the need for manual oversight.
- **Educational Value**: Demonstrates the application of computer vision and deep learning in practical contexts.
- **Customizable for Different Needs**: Can be integrated with other systems or modified for specific requirements.
- **Supports Health Safety Initiatives**: Contributes to public health efforts by providing a tool for mask-wearing adherence.

## Dataset

The model was trained on a dataset consisting of 1376 images:
- **Images with Masks**: 690
- **Images without Masks**: 686

You can download the dataset from [here](URL to dataset).

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/tukaramgarad07/COVID-19-Face-Mask-Detector.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd COVID-19-Face-Mask-Detector
    ```

3. **Create a Virtual Environment**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

4. **Install Required Packages**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**

    ```bash
    python mask_detection.py
    ```

    or

    ```bash
    python train_model.py
    ```

    - `mask_detection.py`: Runs the face mask detection on live webcam feed.
    - `train_model.py`: Used for training the model.

2. **Observe the Output**

    - The application will open a webcam feed.
    - It will display whether a person is wearing a mask or not in real-time.

