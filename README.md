# Facetrack: A Facial Detection and Recognition Framework

Facetrack is a facial detection and recognition framework developed using Python and OpenCV. It leverages Haarcascade classifiers for face detection and provides various utilities for image processing, video capture, and facial recognition. This framework can be used for applications like real-time face detection, image normalization, and facial recognition from video streams.

## Project Structure

- **`dbtest1.py`**: Script for testing the database integration with the framework.
- **`demo.py`**: Demonstration script showing how to use the framework for facial detection and recognition.
- **`detect.py`**: Script for detecting faces in images using Haarcascade classifiers.
- **`detect2cams.py`**: Script for detecting faces using two cameras simultaneously.
- **`haarcascade_frontalface_default.xml`**: Haarcascade classifier XML file for frontal face detection.
- **`histeq.py`**: Script for histogram equalization, a technique for improving the contrast of images.
- **`illumnorm.py`**: Script for illumination normalization, which helps in preprocessing images by normalizing their lighting conditions.
- **`imgextractr1.py`**: Script for extracting images from video frames.
- **`lbpcascade_frontalface.xml`**: LBP (Local Binary Patterns) cascade classifier XML file for frontal face detection.
- **`trainner`**: Directory containing training data and models for facial recognition.
- **`trainner1.py`**: Script for training the facial recognition model.
- **`video cap.txt`**: Text file related to video capture settings or logs.
- **`video.py`**: Script for capturing video and processing it for face detection.
- **`project backup.zip`** & **`Project backup2.zip`**: Backup files containing the project data.

## Getting Started

### Prerequisites

Ensure that you have the following installed:

- **Python 2.x**: The project is built using Python.
- **OpenCV**: For facial detection and image processing. You can install it using pip:
  ```bash
  pip install opencv-python
  ```
  
### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Facetrack.git
   cd Facetrack

### Usage

1. **Facial Detection**:
   - To detect faces in an image, run the `detect.py` script:
     ```bash
     python detect.py
     ```
   - For real-time facial detection using your webcam, you can use the `demo.py` script:
     ```bash
     python demo.py
     ```

2. **Training the Facial Recognition Model**:
   - To train the facial recognition model, place your training images in the `trainner` directory and run:
     ```bash
     python trainner1.py
     ```

3. **Video Capture and Face Detection**:
   - To capture video and detect faces, use the `video.py` script:
     ```bash
     python video.py
     ```

4. **Using Two Cameras**:
   - To detect faces using two cameras simultaneously, run the `detect2cams.py` script:
     ```bash
     python detect2cams.py
     ```

### Additional Features

- **Histogram Equalization**: Run `histeq.py` to improve image contrast.
- **Illumination Normalization**: Normalize lighting in images using `illumnorm.py`.
- **Image Extraction**: Extract frames from video using `imgextractr1.py`.

### Notes

- Ensure that the XML files (`haarcascade_frontalface_default.xml`, `lbpcascade_frontalface.xml`) are in the same directory as your scripts, as they are essential for face detection.
- You can modify the scripts to customize the detection and recognition process according to your requirements.
