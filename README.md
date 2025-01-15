# face_recognisation
face
This is a simple face recognition project using google teachable machine model. Project Overview The facial recognition project aims to implement a system that can identify and verify individuals based on their facial features. This system leverages machine learning algorithms, computer vision techniques, and a database to manage and track attendance or access control efficiently. It finds applications in areas such as security systems, attendance monitoring, and user authentication.

Key Components Image Acquisition: Camera Integration: Captures real-time images or video streams using a webcam or IP camera.

Image Preprocessing: Enhances captured images by resizing, normalizing, and adjusting for optimal input to the facial recognition model.

Face Detection and Recognition: Face Detection: Identifies the presence of a face in the captured images using pre-trained models such as Haar Cascades, DLIB, or MTCNN.

Face Recognition: Matches the detected face against a database of known faces using a deep learning model, such as those based on Convolutional Neural Networks (CNNs).

Model Training and Deployment: Model Training: Uses a labeled dataset of faces to train a recognition model. Models like OpenCV’s FaceRecognizer, or deep learning frameworks like TensorFlow or Keras, can be used.

Model Deployment: Deploys the trained model for real-time recognition. The model classifies faces in the video feed into known or unknown categories.

Database Integration: Database Connection: Integrates with a relational database (e.g., MySQL) to store and retrieve user information and attendance records.

Attendance Management: Automatically logs attendance by inserting records into the database upon successful recognition.

User Interface: Graphical User Interface (GUI): Provides a visual interface for users to interact with the system, view attendance logs, and manage user data. Real-Time Feedback: Displays recognition results and status messages to users during operation.

Technical Workflow Initialization: Load the pre-trained facial recognition model and associated label data. Establish a connection to the MySQL database for storing attendance records.

Real-Time Face Recognition: Continuously capture frames from the camera. Preprocess each frame and pass it through the face detection and recognition pipeline. Compare detected faces with stored profiles and determine the identity.

Attendance Logging: For recognized individuals, check if attendance has already been marked for the current day. If not, insert a new record into the database with the person’s name, date, and time.

Error Handling and Feedback: Provide real-time feedback in case of errors, such as database connection failures or low confidence in recognition results. Allow for manual intervention if required, such as overriding attendance entries or managing user profiles.

Challenges and Considerations: Accuracy: Ensuring high accuracy in various lighting conditions and angles. Security: Securing the system to prevent unauthorized access and data breaches.

Performance: Optimizing the system for real-time processing without significant delays. Ethical Concerns: Addressing privacy issues and obtaining user consent for data collection and usage.

Applications: Access Control: Automated door entry systems for secure access to buildings or rooms. Attendance Systems: Non-intrusive attendance tracking in schools, workplaces, and events.

Surveillance: Monitoring and identifying individuals in public spaces for security purposes. This facial recognition project demonstrates a practical application of AI and computer vision, highlighting the integration of various technologies to solve real-world problems.

Step 1: Search in web browser google teachable machine

![Screenshot (24)](https://github.com/user-attachments/assets/7d5a707f-4d91-4545-ba05-555b7f7a4fda)
step 2: click on teachable Machine
![Screenshot (24)](https://github.com/user-attachments/assets/903efb5c-ade2-4350-b67c-bfbccd79097a)

step 3: Next click on Get Start
![Screenshot (25)](https://github.com/user-attachments/assets/a6c07a25-ed8a-4e56-bb15-ff1c5d6abc81)

step 4:Click on image model
![Screenshot (32)](https://github.com/user-attachments/assets/041047ce-e5c4-4c4b-adf9-31ff351e1f0f)
step 5:Click on Standard image option
![Screenshot (26)](https://github.com/user-attachments/assets/42d5ed2a-a857-4946-bce1-d602f39f884d)
step 6:Create your model in class1 as "your name" and calss2 "unknown"
![Screenshot (28)](https://github.com/user-attachments/assets/f1c6be40-3659-45d5-a705-65525744089b)
step 7: Train your model
![Screenshot (27)](https://github.com/user-attachments/assets/7db92bf6-c1f1-4b25-99a7-b920e042f920)
step 8: Export your model step9:Download your "opencv keras model in"tensorflow"
![Screenshot (31)](https://github.com/user-attachments/assets/394ccc36-c922-4c6b-9cac-0f042b60c2c9)
step 10: Place the converyed keras file in projecttbdirectory as "keras.h5" and "lable.txt"in pycharm.
<img width="266" alt="py" src="https://github.com/user-attachments/assets/ffd40620-dda9-4139-86f3-3d24859741bb" />
step 11:Now create a file pycharm as "main.py" and enter code
<img width="568" alt="py1" src="https://github.com/user-attachments/assets/32428358-00fb-4d1a-95cd-528eb3989ab9" />
step 12: Run code
step 13: expected output may display by opening the web camera of your system and show the"confidence score1" of yur model








