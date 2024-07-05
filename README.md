# Real-Time-Violence-Detection-model-with-Alert-System

#Overview
This project aims to develop a real-time violence detection system using computer vision techniques. The system analyzes video frames to detect instances of violence and, if detected, captures the face of the person involved. The project leverages the MobileNet V2 model for efficient and accurate detection.

#Features
Real-Time Detection: Processes video frames in real-time to identify violent activities.
Face Capture: Captures and saves the face of the person involved in the detected violent activity.
Efficient Model: Utilizes MobileNet V2 for a balance between speed and accuracy.
#Model
We used the MobileNet V2 model for this project due to its lightweight architecture and high performance. The model has been trained on a dataset containing various instances of violent and non-violent actions to achieve high accuracy in detection.

#Colab Notebook
To test and experiment with the trained model, we have provided a Google Colab notebook. You can use this notebook to run the model on your own video inputs and see the results.

Colab Notebook for Model Testing - https://colab.research.google.com/drive/1FR8vkhhI1iNsxRWfgA_1eqINUr-kKbUq?usp=sharing

#Installation
Prerequisites
Python 3.6+
TensorFlow
OpenCV
Other dependencies as listed in requirements.txt
Setup
Clone the repository:


#Copy code
git clone https://github.com/Adityaastronomy/Real-Time-Violence-Detection-model-with-Alert-System.git
cd Real-Time-Violence-Detection-model-with-Alert-System
Install the required dependencies:


#Copy code
pip install -r requirements.txt
Usage
Prepare Video Input: Place your video file in the designated input directory.

Run the Detection Script:


#Copy code
python detect_violence.py --input /path/to/video/file
Output: The system will process the video and output frames where violence is detected, along with the captured faces.


#Contribution
Feel free to open issues or submit pull requests for any improvements or bug fixes.

#License
This project is licensed under the MIT License. See the LICENSE file for more details.

#Future Scope
We will extend this project and add another part of creating a violence alert message with the face of person who is detected.
