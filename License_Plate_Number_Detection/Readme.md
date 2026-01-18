# License Plate Number Detection using Contours

A computer vision project that detects vehicle license plates from images using
traditional image processing techniques such as edge detection and contour analysis.

This project focuses on understanding how classical OpenCV methods can be used
to localize license plates without deep learning models.

---

## 📌 Project Overview

The objective of this project is to detect the region of a license plate from
vehicle images using contour-based image processing techniques.

The approach involves preprocessing the image, detecting edges, extracting
contours, and identifying the contour that most likely corresponds to a license plate
based on shape and aspect ratio.

---

## 🎯 Objectives

- To understand classical computer vision techniques
- To implement license plate detection using contours
- To work with real-world vehicle image datasets
- To visualize intermediate image processing steps

---

## 🛠 Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## ⚙️ Methodology (Contours-Based Detection)

1. Convert input image to grayscale
2. Apply noise reduction (Gaussian blur)
3. Perform edge detection (Canny)
4. Detect contours in the image
5. Filter contours based on:
   - Area
   - Shape
   - Aspect ratio
6. Identify and crop the license plate region

This approach avoids machine learning models and relies purely on image processing.

---

## 🗂 Project Structure

License_Plate_Number_Detection/
├── README.md
├── 1. License Plate Detection (using Contours).ipynb
├── data/
│ └── vehicle_images/
├── requirements.txt

---

## ▶️ How to Run the Project

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
3. Open Jupyter Notebook
4.Run the notebook: 
  License Plate Detection (using Contours).ipynb

---

## 📦 Dataset

The dataset consists of images of vehicles containing visible license plates.
These images are used as input for testing contour-based detection methods.

---

## 📊 Results

License plate regions are successfully detected in clear, well-lit images

Performance depends on image quality and plate visibility

Works best for images with strong edges and minimal background noise

---

## 🧠 What I Learned

Practical use of OpenCV for real-world problems

Edge detection and contour filtering techniques

Limitations of classical vision methods compared to deep learning

Importance of preprocessing in image-based tasks

---

## ⚠️ Limitations

Sensitive to lighting conditions

Performance drops with tilted or blurred plates

Not suitable for real-time or large-scale deployment without improvements

---

## 🔮 Future Improvements

Add character segmentation and OCR

Improve robustness using adaptive thresholding

Compare contour-based detection with deep learning approaches

Extend to video-based detection

---

## 👤 Author

Suyash

---

## Why this README is now **correct and strong**

- ❌ No YOLO confusion
- ❌ No unused config files
- ✅ Matches the actual notebook
- ✅ Honest about limitations
- ✅ Interview-safe (you won’t be caught bluffing)

---

## VERY IMPORTANT NEXT STEP (Don’t Skip This)

You should **delete or ignore** these from your repo:
- `yolo_utils/`
- `darknet-yolov3.cfg`
- Any YOLO references in README

Leaving unused ML artifacts is worse than not knowing ML.

---

## What I can do next (high value)

1️⃣ Review your **notebook content** and suggest improvements  
2️⃣ Help you add **OCR** as a next version  
3️⃣ Write a **top-level README** linking all your projects  
4️⃣ Help you explain this project confidently in interviews  

Tell me what you want to do next.

