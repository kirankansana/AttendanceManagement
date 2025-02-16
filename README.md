# Face Recognition Attendance System
This project is a Python-based attendance system that utilizes OpenCV and face recognition techniques to recognize faces and mark attendance in an Excel spreadsheet. The system captures images through a webcam, compares them with a pre-trained set of known faces, and records attendance for recognized individuals.

# Features
1. Real-time face recognition using OpenCV and deep learning models
2. Attendance marking in an Excel spreadsheet

# Installation
Clone the repository to your local machine:
Copy code
git clone https://github.com/your-username/face-recognition-attendance.git

Change into the project directory:
Copy code-:

cd face-recognition-attendance

Install python and all other necessary packages before running the project
Download all the requirements from requirements.txt

# Usage
Make sure you have Python installed on your system.

Update the attendance.py script and modify the file paths or configurations according to your needs.

Run the attendance.py script to start the attendance system:
Copy code-:

python attendance.py

The system will open the webcam feed and start recognizing faces. If a recognized face matches a student's record, their attendance will be marked in the Excel spreadsheet.

Press q to exit the system.

# Demo Video
https://youtu.be/M2FQsdwjgkg

# Customization
You can modify the code in attendance.py to change the attendance marking logic or add additional features to the system.

Update the excel.py file to customize the Excel spreadsheet's format or add more functionality for handling attendance records.

Feel free to extend the project by training your own face recognition model or implementing additional features.

# Acknowledgements
OpenCV - Open Source Computer Vision Library

face_recognition - Simple face recognition library

Openpyxl - Python library for Excel file manipulation

numpy - Library for array operations

cv2 - OpenCV library for computer vision task

