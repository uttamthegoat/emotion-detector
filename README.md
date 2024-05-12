# Real-time Emotion Detection using OpenCV and TensorFlow

This project utilizes OpenCV and TensorFlow to perform real-time emotion detection from video streams or webcam feeds. The model is capable of detecting various facial expressions such as happiness, sadness, anger, surprise, etc., in real-time.

## Installation

Follow these steps to set up the project:

1. **Create a virtual environment** (optional but recommended):
    ```bash
    python3 -m venv mlenv
    venv/bin/activate
    ```

2. **Install required libraries**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the model.ipynb notebook**:
   This notebook contains the code for building the emotion detection model. Run this notebook to train and save the model before running the application.

4. **Run the application**:
    ```bash
    python app.py
    ```

## Usage

Once the application is running, it will capture video from the webcam or video stream and detect emotions in real-time. Detected emotions will be displayed on the screen along with bounding boxes around detected faces.

## Model Details

The emotion detection model used in this project is built using TensorFlow. It has been trained on a dataset containing labeled facial expressions to recognize emotions accurately. The model architecture employs deep learning techniques for efficient and accurate emotion classification.

## Credits

This project was developed by [Your Name] as part of [mention any relevant course, workshop, or personal project].

