Iris-Based Biometric Attendance System

A real-time attendance system using iris recognition. The system captures the user’s eye image, applies feature extraction, and verifies identity through pattern recognition — marking attendance automatically.


---

✨ Features

📸 Real-time image capture through webcam

👁️ Iris region detection using OpenCV

🧠 Feature extraction via grayscale + edge filters

✅ Attendance marking on successful match

🗂️ CSV-based attendance logging

📊 Performance evaluation (FAR/FRR)



---

🛠️ Technologies Used

Component	Tech

Language	Python
Image Processing	OpenCV
Math & Matrix Ops	NumPy
Preprocessing	Histogram equalization, Gaussian blur
Recognition Technique	Feature matching + distance metric
Storage	CSV / SQLite



---

📂 Folder Structure

iris-attendance-system/
│── main.py
│── haarcascade_eye.xml
│── attendance.csv
│── /images (optional for testing)
│── README.md


---

⚙️ Installation & Setup

1️⃣ Install dependencies

pip install opencv-python numpy

2️⃣ Run script

python main.py


---

🎯 System Workflow

Capture Eye → Preprocess Image → Segment Iris → Extract Features → Match with Template → Mark Attendance


---

📁 Output

Attendance stored in:

attendance.csv

Example:

Name	Timestamp	Status

User001	2025-10-31 09:42:15	Present



---

🛡️ Performance Metrics

FAR — False Acceptance Rate

FRR — False Rejection Rate



---

🚀 Future Enhancements

Deep learning-based iris recognition

GUI system for attendance portal

Cloud-synced student database

Recognition for multiple users simultaneously



---

👤 Credits

Developed as a Computer Vision + Biometrics project using OpenCV.
