# Face_recognition_based_attendance_system
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, we have made an attendance system which takes attendance by using face recognition technique. We have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.

TECHNOLOGY USED:
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for details of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.

### Running the project:
1) Create python env
    python3 -m venv myenv
2) Install the required packages
    pip3 install -r requirements.txt
3) Run main.py
    python3 main.py