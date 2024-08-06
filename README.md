# COVID-19 Face Mask Detector

## Overview

This project involves creating a real-time face mask detection system using Python, OpenCV, and Keras. The system is designed to identify whether a person in a webcam feed is wearing a mask or not. It was developed in response to the World Health Organization’s guidelines on mask-wearing during the COVID-19 pandemic.

## Technologies Used

- **Python**: High-level programming language used for development.
- **OpenCV**: Library used for computer vision tasks.
- **Keras**: High-level neural networks API, used for model training.

## Project Features

- **Real-time Mask Detection**: Detects mask-wearing status from live webcam feed.
- **High Accuracy**: Model trained with a comprehensive dataset to ensure reliable performance.

## Dataset

The model was trained on a dataset containing 1376 images:
- **Images with Masks**: 690
- **Images without Masks**: 686

You can download the dataset from [here](URL to dataset).

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/COVID-19-Face-Mask-Detector.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd COVID-19-Face-Mask-Detector
    ```

3. **Install Required Packages**

    Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

    Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

    Make sure `requirements.txt` includes:

    ```
    opencv-python
    keras
    tensorflow
    numpy
    ```

## Usage

1. **Run the Application**

    ```bash
    python mask_detection.py
    ```

2. **Observe the Output**

    - The application will open a webcam feed.
    - It will display whether a person is wearing a mask or not in real-time.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request. Make sure to include a detailed description of your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- Thanks to the developers of OpenCV and Keras for their powerful libraries.
- Dataset sources: [Insert any dataset sources or acknowledgements here]

## Contact

For any questions or feedback, please contact me at [your.email@example.com].

