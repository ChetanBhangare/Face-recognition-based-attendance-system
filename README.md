# Face-recognition-based-attendance-system

This repository contains a **Face Recognition Based Attendance System** integrated with **Firebase Admin SDK** to store attendance records in real time. The system uses computer vision to recognize faces and manage attendance efficiently and accurately.

---

## Table of Contents  
1. [Features](#features)  
2. [Technology Stack](#technology-stack)  
3. [Installation](#installation)  
   - [Step 1: Clone the Repository](#step-1-clone-the-repository)  
   - [Step 2: Set Up Firebase](#step-2-set-up-firebase)  
   - [Step 3: Install Dependencies](#step-3-install-dependencies)  
   - [Step 4: Save Face Encodings](#step-4-save-face-encodings)  
   - [Step 5: Run the Project](#step-5-run-the-project)  
4. [How It Works](#how-it-works)  
5. [Project Structure](#project-structure)  
6. [Future Improvements](#future-improvements)  
7. [Contributing](#contributing)  
8. [License](#license)  
9. [Contact](#contact)  

---

## Features  
- **Real-Time Face Recognition:** Detects and recognizes faces in real time using a webcam feed.  
- **Firebase Integration:** Automatically updates attendance in Firebase Realtime Database and fetches associated student data.  
- **Custom User Interface:** Displays student details, attendance stats, and recognition status using an interactive graphical interface.  
- **Automated Attendance Management:** Updates total attendance and last attendance time seamlessly.  
- **Performance Optimization:** Designed for efficient processing of multiple faces and fast database interactions.  

---

## Technology Stack  
- **Languages & Libraries:**  
  - Python  
  - OpenCV  
  - face_recognition  
  - Firebase Admin SDK  
  - NumPy  
  - cvzone  

- **Database:**  
  - Firebase Realtime Database  

- **Cloud Storage:**  
  - Firebase Cloud Storage  

---

## Installation  

### Step 1: Clone the Repository  
```bash
git clone https://github.com/yourusername/face-recognition-attendance.git
cd face-recognition-attendance

