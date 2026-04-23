# Face Auto Capture using OpenCV

A real-time face detection project that uses OpenCV Haar Cascades to detect faces from webcam and automatically capture and save images when a face is detected.

---

## Features

- Real-time face detection using webcam
- Automatic image capture when a face is detected
- Configurable capture delay to avoid duplicates
- Simple and lightweight implementation
- Uses OpenCV Haar Cascade classifier

---

##  Requirements

- Python 3.x
- OpenCV
- urllib (built-in)
- os (built-in)
- time (built-in)

Install OpenCV:


##How It Works?
 -Downloads Haar Cascade file if not available
 -Opens webcam feed
 -Detects faces in real-time
 -Draws bounding boxes around detected faces
 -Saves captured images after a delay to avoid duplicates
 -Run Project
 -python main.py

---

Output

 -Captured images will be saved automatically in the directory you define:

  save_path = "Put Your Path In Order To Save"

---

Configuration

You can adjust:

capture_delay → time between saved images
scaleFactor and minNeighbors → detection sensitivity

---

Notes

 -Press ESC to exit the program
 
 -Make sure webcam is enabled and accessible
 -First run will download Haar Cascade file automatically
