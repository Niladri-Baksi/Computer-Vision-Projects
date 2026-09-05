# Computer Vision Projects

A collection of my **Computer Vision projects**, built while exploring image processing, real-time vision, object/hand tracking, facial recognition, and practical OpenCV applications.

Each project lives in its own repository, with its own code, setup instructions, and implementation details.

---

## Projects

### ✋ Hand Gesture Video Masking & Overlay 🤚

**Repository:** [Hand-Gesture-Video-Masking-Overlay](https://github.com/Niladri-Baksi/Hand-Gesture-Video-Masking-Overlay)

A real-time computer vision project that uses **hand tracking to create a dynamic polygonal mask over a live camera feed**.

**What it does**

* Tracks hand landmarks in real time using **MediaPipe**.
* Uses hand landmark positions to define a dynamic region of interest.
* Creates a polygonal mask based on the detected hand position.
* Applies the mask directly over the camera feed rather than displaying it as a separate frame.
* Uses **OpenCV** for video capture, image processing, masking, drawing, and real-time display.
* Organizes the hand-detection logic into a reusable Python module.

**Main technologies**

* **Python** — core programming language.
* **OpenCV (`cv2`)** — webcam input, image manipulation, masking, drawing, and display.
* **MediaPipe** — real-time hand landmark detection and tracking.
* **NumPy** — polygon masks, arrays, and pixel-level operations.

> A practical exploration of how tracked landmarks can be turned into interactive regions within a live video stream.

---

### 👥 Face Recognition And Attendance System

**Repository:** [Face-Recognition-And-Attendance](https://github.com/Niladri-Baksi/Face-Recognition-And-Attendance)

A face-recognition-based attendance system that automatically identifies known faces from a live camera feed and records their attendance.

**What it does**

* Loads a collection of known faces from a dataset.
* Automatically processes the images and generates facial encodings.
* Captures frames from a webcam using **OpenCV**.
* Detects and encodes faces appearing in the live video.
* Compares live facial encodings against the stored encodings.
* Identifies recognized individuals and displays their names.
* Records attendance for recognized people while avoiding repeated entries.

**Main technologies**

* **Python** — core implementation.
* **OpenCV (`cv2`)** — webcam handling, image processing, and visualization.
* **face_recognition** — face detection, facial encodings, and face matching.
* **NumPy** — numerical operations involved in facial encoding comparisons.
* **OS / filesystem utilities** — automatic loading of images from the dataset.

> From a folder of reference images to an automated attendance system—all through real-time face recognition.

---

## Tech Stack

| Technology           | Used for                                                 |
| -------------------- | -------------------------------------------------------- |
| **Python**           | Core development                                         |
| **OpenCV**           | Image/video processing and real-time camera applications |
| **MediaPipe**        | Hand landmark detection and tracking                     |
| **face_recognition** | Face detection, encoding, and recognition                |
| **NumPy**            | Array and pixel-level operations                         |

---

## About

This repository is a growing collection of experiments and projects focused on **learning Computer Vision by building things**.

The goal is simple: take concepts such as image processing, landmark detection, masking, tracking, and facial recognition, and turn them into working real-time applications.

More projects will be added as the collection grows.
