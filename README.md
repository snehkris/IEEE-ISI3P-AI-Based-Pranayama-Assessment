# IEEE-ISI3P-AI-Based-Pranayama-Assessment
A research project for real-time Pranayama assessment using breathing audio analysis, pose estimation, and machine learning.


> AI-powered assessment of Anulom Vilom and Kapalbhati using audio signal processing and computer vision.

## 📌 Project Overview

This project focuses on the automated assessment of Pranayama techniques by combining:

- 🎧 Quantitative analysis from breathing audio
- 📷 Qualitative analysis from body posture
- 🤖 AI and Computer Vision for real-time feedback

The goal is to develop an intelligent system capable of evaluating breathing quality and posture during Pranayama practice.

---

## 🚀 Current Progress

### ✅ Quantitative Analysis (Completed)

- Audio extraction from video
- Waveform visualization
- Mel Spectrogram generation
- RMS Energy computation
- Signal smoothing
- Peak detection
- Breathing cycle estimation
- Breathing frequency calculation
- Rhythm consistency analysis
- Quantitative report generation

### 🚧 Qualitative Analysis
This notebook performs qualitative posture analysis for Anulom Vilom using YOLOv8 Pose.

-  Pose Estimation
- Spine alignment analysis
- Neck posture evaluation
- Shoulder alignment
- Hand position tracking
- Sitting posture assessment
- Overall posture scoring

---

## 📊 Current Quantitative Results

| Parameter | Value |
|-----------|--------:|
| Audio Duration | 28.98 s |
| Breathing Cycles | 6 |
| Average Cycle Duration | 5.54 s |
| Breathing Frequency | 10.84 breaths/min |
| Rhythm Consistency (STD) | 0.795 s |
| Average RMS Energy | 0.0347 |
| Maximum RMS Energy | 0.0540 |
| Minimum RMS Energy | 0.0000 |



## Qualitative Analysis Report

| Parameter | Score |
|-----------|------:|
| Neck Score | 85.0 / 100 |
| Spine Score | 40.0 / 100 |
| Shoulder Score | 85.0 / 100 |
| Hand Position | 94.1 / 100 |
| Sitting Posture | 100.0 / 100 |

### Overall Performance

- *Overall Score:* *80.8 / 100*
- *Overall Result:* *Good*

---

## 🛠️ Technologies Used

- Python
- Librosa
- NumPy
- SciPy
- Matplotlib
- OpenCV
- YOLOv8 Pose 

---

## 📂 Repository Structure

```text
.
├── notebooks/
│   ├── Quantitative_Analysis.ipynb
│   └── Qualitative_Analysis.ipynb (Coming Soon)
│
├── results/
│   ├── Quantitative_Report.csv
│   ├── waveform.png
│   ├── mel_spectrogram.png
│   ├── rms_energy.png
│   ├── peak_detection.png
│   └── quantitative_results.png
│
├── README.md
└── LICENSE
```

---

## 🎯 Future Work

- Real-time breathing analysis
- Pose correction feedback
- Mobile application integration
- AI-based posture classification
- Deep learning for Pranayama assessment
- Multimodal fusion of audio and video

---

## 📜 License

This repository is intended for research and educational purposes.

---

⭐ **Project Status:** Active Development
