# SAM Object Detection and Tracking (YOLOv8 + Deep SORT) 

This project is a real-time object detection and tracking system built using the Ultralytics YOLOv8 models and Deep SORT tracking. It includes a clean and interactive Streamlit interface with webcam, video, and image input support.

---

## Features

- ✅ YOLOv8 Model Variant Selection (`n`, `s`, `m`, `l`, `x`)
- ✅ Webcam, video file, and image input support
- ✅ Deep SORT tracking (toggleable)
- ✅ Real-time FPS counter
- ✅ Class-wise object count summary
- ✅ Filter detection by object classes
- ✅ Confidence threshold control
- ✅ Detection log console
- ✅ Download processed video and CSV summary
- ✅ Fully interactive and professional Streamlit GUI

---

##  Sample Classes Supported

- person
- car
- dog
- cat
- truck
- bicycle
- motorcycle
- bus
- bottle

*(based on COCO dataset classes)*

---

## Technologies Used

- Python
- OpenCV
- Ultralytics YOLOv8
- Deep SORT tracking
- Streamlit




## ▶️ How to Run

1. **Clone this repository**  
```bash
git clone https://github.com/SAMYAK9833/SAM_OBJECT_DETECTION_TRACKING
cd Object-Detection-Tracking
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Download YOLOv8 model weights** (e.g. `yolov8n.pt`)  
From: [https://github.com/ultralytics/ultralytics](https://github.com/ultralytics/ultralytics)


4. **If using virtual environment, activate it**
```bash

venv\Scripts\activate
```
---

5. **Install necessary libraries**
```bash

pip install ultralytics opencv-python deep_sort_realtime streamlit
```
---

6. **Run the app**
```bash

streamlit run main.py
```

---

## Screenshots
 
 ### Snap 1 :- 
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/c5518c9d-e55a-4bf4-95c6-917d30a51b3b" />

 ### Snap 2 :-
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/75652fb0-592e-4a6c-97ff-6a27e4884300" />

 ### Snap 3 :-
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/b20f0635-f38e-492f-878e-39ee339ddba2" />

 ### Snap 4 :-
 <img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/29893cbf-2739-4e19-ba4c-de570b94a475" />

## Author

**SAMYAK VAIDYA**  
Artificial Intelligence & Data Science Enthusiast  
Connect on [LinkedIn](https://www.linkedin.com/in/samyak-vaidya-4bb9b4282)



