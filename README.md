# Real-Time Web-Based Yoga Pose Detection and Correction

## Project Overview

This project develops a **real-time web-based Yoga Pose Detection and Correction system** using **HTML, CSS, and JavaScript**. It leverages powerful machine learning libraries such as **PoseNet**, **ml5.js**, and **p5.js** to detect human body keypoints accurately through live webcam input.

The system allows users to perform various yoga poses in front of their webcam. Using PoseNet, it extracts keypoints like shoulders, elbows, hips, and knees in real-time. A **K-Nearest Neighbors (KNN)** classifier implemented with ml5.js classifies these poses by comparing the live keypoints to previously collected training data.

For pose correction, the application calculates joint angles and compares them to ideal reference angles for each yoga pose. Deviations are detected and visually highlighted, helping users adjust their posture. Additionally, voice feedback is provided using the **Web Speech API** to make the user experience interactive and easy to follow.

---

## Features

- **Real-time pose estimation** with PoseNet via webcam.
- **Pose classification** using ml5.js KNN classifier.
- **Pose correction** based on joint angle calculations.
- **Visual and voice feedback** to guide users for correct posture.
- User-friendly web interface built with HTML, CSS, and JavaScript.

---

## Technologies Used

- **PoseNet** (via ml5.js) — for pose keypoint detection.
- **ml5.js** — for KNN pose classification.
- **p5.js** — for creative visualizations and webcam handling.
- **Web Speech API** — for voice feedback.
- **HTML/CSS/JavaScript** — frontend web technologies.

---

## How It Works

1. The webcam captures live video input.
2. PoseNet detects 17 key body points in real-time.
3. The KNN classifier compares the detected keypoints against stored training data to classify the current pose.
4. Joint angles are computed and compared to ideal reference angles.
5. Visual cues highlight any deviations in posture.
6. Voice feedback guides the user to correct their pose.

---

## Setup and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/thanishka220/Yoga-Pose-Correction-main.git
   cd Yoga-Pose-Correction-main

