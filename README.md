# Pothole Detection System

This program utilizes computer vision to detect potholes in roads. 

## Details

Uses Python with openCV, Trained on over 600 images using YOLOv8. 

## Installation and usage

1) Clone the repository

    ```bash
    git clone https://github.com/Gurmukh-Singh-4253/PotholeDetection.git 
    cd PotholeDetection
    ```

2) Enable python virtual environment (Recommended)

    ```bash
    python -m venv venv
    source venv/bin/activate   # ./venv/Scripts/activate on Windows
    ```

3) Install the requirements

    ```bash
    pip install -r requirements.txt
    ```

4) Edit the cv2.VideoCapture() function call to use the source footage (leave 0 to use the webcam)

    ```python
    # Replace path/to/file by actual path or 0 to use webcam footage
    cap = cv2.VideoCapture("path/to/file")   
    ```

5) Run the main file to start the pothole detection

    ```bash
    python main.py
    ```

## Performance and Metrics

-- TODO: add Performance and Metrics
