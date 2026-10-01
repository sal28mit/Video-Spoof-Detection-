# 🎭 Video Spoof Detection System

A real-time video spoof detection system using **YOLO** to identify spoofing attempts in video feeds and enhance security in biometric facial recognition systems.

## 📌 Overview

The Video Spoof Detection System leverages YOLO-based object detection to identify potential spoofing attempts in real-time video streams. The project focuses on improving the reliability of facial recognition systems by distinguishing genuine facial presentations from spoofing attempts.

Through model training, experimentation, and evaluation, this project explores the practical application of YOLO for real-time spoof detection.

## 🎯 Objectives

- Detect potential spoofing attempts in real-time video feeds.
- Enhance the security of facial recognition systems.
- Implement YOLO for efficient and reliable spoof detection.
- Explore real-time video processing and computer vision techniques.
- Evaluate the practicality of deep learning-based spoof detection.

## ✨ Key Features

- **Real-Time Detection:** Processes live video feeds for spoof detection.
- **YOLO-Based Model:** Uses a trained YOLO model for detecting spoofing attempts.
- **Computer Vision:** Leverages video processing techniques for visual analysis.
- **Local Processing:** Supports running the detection system locally.
- **Security Enhancement:** Aims to strengthen biometric facial recognition security.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| YOLO | Object detection and spoof detection |
| OpenCV | Video capture and image processing |
| PyTorch | Deep learning model support |
| NumPy | Numerical operations |
| Computer Vision | Visual data analysis |

## 📂 Project Structure

```text
Video-Spoof-Detection/
│
├── models/
│   └── l_version_1_300.pt
│
├── main.py
├── requirements.txt
├── README.md
└── ...
```

*The structure above is illustrative. Adjust the filenames to match your actual repository.*

## 📥 Trained Model

The trained YOLO model is available as a downloadable asset in the GitHub Releases section.

**Model:** `l_version_1_300.pt`

**File size:** Approximately 83.57 MB

**Download:** [GitHub Releases](https://github.com/sal28mit/Video-Spoof-Detection/releases)

Download the model and place it inside the `models/` directory.

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/sal28mit/Video-Spoof-Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd Video-Spoof-Detection
```

### 3. Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Download the Trained Model

Download `l_version_1_300.pt` from the Releases section and place it inside the `models` folder.

## ▶️ Running the Project

Once the dependencies are installed and the trained model is available, run the project's main detection script.

```bash
python main.py
```

*Make sure the script name and model path match your actual implementation.*

## 🔬 Methodology

1. **Video Input:** Capture video frames from a live video feed.
2. **Preprocessing:** Process the captured frames using OpenCV.
3. **Model Inference:** Pass the frames to the trained YOLO model.
4. **Spoof Detection:** Analyze the model's predictions to identify potential spoofing attempts.
5. **Output:** Display detection results in real time.

## 🔮 Future Scope

- Improve detection accuracy across different lighting conditions.
- Explore additional spoofing techniques and attack scenarios.
- Optimize inference speed for real-time applications.
- Expand evaluation using diverse datasets.
- Investigate integration with existing biometric authentication systems.

## 📊 Conclusion

This project demonstrates the application of YOLO in real-time video spoof detection, contributing to research in biometric security and computer vision. Experimental analysis highlights the model's practical implementation and potential for enhancing digital security. Further development can focus on improving robustness, detection performance, and adaptability to evolving spoofing techniques.

## 👩‍💻 Author

**Saloumi Mitre**

GitHub: [@sal28mit](https://github.com/sal28mit)

---

⭐ If you find this project useful, consider giving the repository a star!
