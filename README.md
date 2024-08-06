# COVID-19 Face Mask Detector

## Overview

This project involves creating a real-time face mask detection system using Python, OpenCV, and Keras. The system is designed to identify whether a person in a webcam feed is wearing a mask or not. It was developed in response to the World Health Organization’s guidelines on mask-wearing during the COVID-19 pandemic.

## Technologies Used

- **Python**: Programming language used for implementation.
- **OpenCV**: Library for computer vision tasks, including face detection.
- **Keras**: Deep learning library used for building and training the neural network model.

## Project Features

- **Real-time Mask Detection**: Analyzes webcam feed to detect if a person is wearing a mask or not.
- **Model Accuracy**: Trained with a diverse dataset to ensure reliable performance.
- **Customizable**: The model can be retrained with different datasets for improved accuracy or specific use cases.

## Dataset

The model was trained on a dataset consisting of 1376 images:
- **Images with Masks**: 690
- **Images without Masks**: 686

The dataset can be downloaded from [here](URL to dataset).

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

1. **Run the Real-Time Mask Detection**

    ```bash
    python mask_detection.py
    ```

    - This script will open a webcam feed and display whether a person is wearing a mask or not in real-time.

2. **Train the Model**

    ```bash
    python train_model.py
    ```

    - This script trains the face mask detection model using the images in the `./train` and `./test` directories. The trained models will be saved as `model2-{epoch:03d}.model`.



Here are some advantages of the **COVID-19 Face Mask Detector** project that you can include in the `README.md`:

## Advantages

1. **Enhanced Public Health Monitoring**: 
   - The system helps in ensuring compliance with mask-wearing guidelines, which is crucial for preventing the spread of COVID-19 and other respiratory illnesses.

2. **Real-Time Detection**:
   - Provides immediate feedback on mask usage, enabling quick actions in environments where mask compliance is critical, such as public transport, offices, and healthcare facilities.

3. **Scalability and Adaptability**:
   - The model can be retrained with new datasets to adapt to different environments or to improve accuracy. This makes the system versatile for various applications and conditions.

4. **User-Friendly Interface**:
   - The real-time detection script is straightforward and easy to use, with visual indicators (rectangles and text) clearly showing mask-wearing status.

5. **Reduced Manual Monitoring**:
   - Automates the process of checking mask compliance, reducing the need for manual oversight and allowing for efficient monitoring in busy environments.

6. **Educational Value**:
   - Demonstrates the application of computer vision and deep learning in a practical context, providing valuable insights into the development and deployment of machine learning models.

7. **Customizable for Different Needs**:
   - Can be integrated with other systems or modified to fit specific requirements, such as adjusting the detection thresholds or adding additional features like alert systems.

8. **Supports Health Safety Initiatives**:
   - Contributes to ongoing public health efforts by providing a tool that supports mask-wearing adherence, which is a key measure in controlling the spread of infectious diseases.
