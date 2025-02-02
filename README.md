# Real-Time Emotion Detection

The **Real-Time Emotion Detection** project uses computer vision and machine learning to detect emotions from facial expressions in real-time. The model is built using TensorFlow and OpenCV to classify emotions from live video input captured through a webcam. The emotions detected include categories such as Happy, Sad, Angry, and others.

This project provides a demo notebook where users can run the real-time emotion detection model. The detection process uses a pre-trained model and a Haar Cascade classifier to identify faces in the video stream and predict emotions based on facial expressions.

## How to Use the Demo Notebook

### 1. Install Dependencies:
To run the project, you'll need to install the following libraries:
- OpenCV
- TensorFlow

You can install these dependencies using pip:

```bash
pip install opencv-python
pip install tensorflow
```
### 2. Run the Demo Script:
Clone the repository and open the 'demo.ipynb' file. Ensure you have installed the required libraries. Simply run the code cells in the notebook, and a pop-up window will appear running the real-time emotion detection model using your webcam.

## 3. Real-Time Emotion Detection:
Once you run the script, it will start capturing video from the webcam and process each frame to detect faces and classify emotions:
- Faces are detected and marked with rectangles in the video feed.
- Emotions are predicted for each detected face, and the emotion with the highest confidence score is displayed on the screen.

## 4. Exit the Program:
Press `q` to quit the program and close the webcam window.

## Folder Structure:
- **`models/`**: Contains the trained emotion detection model (`model.keras`).
- **`haarcascades/`**: Contains the Haar Cascade classifier (`haarcascade_frontalface_default.xml`) for face detection.
- **`demo.ipynb`**: Jupyter notebook to demonstrate the emotion detection process.
- **`Data/`**: (Optional folder for storing any datasets or files used in the project).

## Note:
- Ensure you have a webcam connected for real-time emotion detection.
- The demo works best in environments with proper lighting for accurate face detection.

