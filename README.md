# Face-Recognition-System-
A real-time face recognition system using OpenCV, Face Recognition library, and a webcam. This project detects and recognizes human faces with name labels and displays the confidence (accuracy) below the face box.

🚀 Features
✅ Live face detection via webcam

✅ Face recognition with name labels

✅ Accuracy percentage display below each face

✅ Trained using custom dataset from webcam

✅ Built with modular and clean code

❌ Attendance feature removed for simplicity


📦 face-recognition-project/
├── 1_data_collection.ipynb         # Capture dataset from webcam
├── 2train_model.ipynb             # Train and save face encodings
├── 3_face_recognition.ipynb       # Real-time recognition with accuracy tags
├── dataset/                       # Stored face images (per person)
│   └── prashant/
│       ├── 0.jpg
│       └── ...
├── trained_model/
│   └── encodings.pickle           # Saved face encodings
├── README.md                      # You’re reading it :)



🔧 Technologies Used
Python 3.10+

OpenCV

face_recognition (built on dlib)

NumPy

Jupyter Notebook





 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/face-recognition-project.git
cd face-recognition-project
Install requirements

bash
Copy
Edit
pip install -r requirements.txt
(Or manually install: opencv-python, face_recognition, numpy)

Step 1: Capture dataset

Run 1_data_collection.ipynb

Change person_name in the code and press Space to capture

Step 2: Train the model

Run 2train_model.ipynb to create encodings.pickle

Step 3: Run live recognition

Run 3_face_recognition.ipynb

You’ll see your face detected with your name and accuracy
