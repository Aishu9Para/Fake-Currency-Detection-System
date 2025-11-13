# 🧠 Fake Currency Detection System 
*A Trustworthy Artificial Intelligence Course Project*

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Image%20Processing-green.svg)
![Tkinter](https://img.shields.io/badge/Tkinter-GUI-orange.svg)
![AI Ethics](https://img.shields.io/badge/Trustworthy-AI-blueviolet.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 💡 Overview

The **Fake Currency Detection System** is a Trustworthy AI project designed to authenticate **Indian currency notes (₹500 & ₹2000)** using **image processing** and **computer vision techniques**. 
This system uses advanced algorithms for **feature extraction, pattern analysis, and similarity comparison** to determine whether a note is **real** or **fake**, prioritizing **accuracy**, **transparency**, and **explainability** in its decision-making.

It has been built completely in **Python** using:
- **OpenCV** for image processing 
- **Tkinter** for GUI development 
- **SSIM** and **ORB** algorithms for feature matching 
- **Jupyter Notebook** as the development environment 

---

## 🧩 Key Features

- 🔍 Detects counterfeit Indian currency of ₹500 and ₹2000 denominations 
- ⚙️ Utilizes **ORB (Oriented FAST and Rotated BRIEF)** for key feature detection 
- 📊 Measures similarity using **SSIM (Structural Similarity Index)** for comparison 
- 🖥️ User-friendly **Tkinter GUI** for interaction and visual results 
- 📁 Includes a custom, structured dataset of real and fake notes 
- 🧠 Built with **Trustworthy AI principles** — transparent, reliable, and explainable 

---

## 🛠️ Libraries and Tools

| Library / Tool | Purpose |
|----------------|----------|
| **OpenCV** | Image processing and core feature extraction |
| **Tkinter** | Graphical User Interface (GUI) for input and output |
| **NumPy** | High-performance numerical operations and array handling |
| **Matplotlib** | Visualization and plotting of data and features |
| **Jupyter Notebook** | Modular development, testing, and control flow |

---

## 📂 Project Structure

```yaml
Fake-Currency-Detection-System/
│
├── Dataset/
│ ├── Real_Notes/ # Real ₹500 and ₹2000 notes for templates
│ ├── Fake_Notes/ # Fake currency note images for testing
│ └── Features/ # Stored security feature templates
│
├── Fake Notes/ # Sample fake notes for testing
├── 500_testing.ipynb # Notebook for ₹500 detection logic
├── 2000_testing.ipynb # Notebook for ₹2000 detection logic
├── controller.ipynb # Main notebook controlling the workflow and GUI launch
├── gui_1.ipynb # GUI module for user input (Image selection, denomination)
├── gui_2.ipynb # GUI module for displaying detailed results
├── FAKE_CURRENCY_DETECTOR_REPORT.pdf # Complete project report
└── README.md # You are here!
