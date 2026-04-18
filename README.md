# CCTV Face Detection and Verification

A **real-time computer vision system** that detects and recognizes individuals from CCTV footage using deep learning and facial embeddings.

The system processes video input, detects people, extracts faces, generates embeddings, and matches them against a stored face database.

---

## Features

* Real-time CCTV video processing
* Person detection using **YOLOv11**
* Face recognition using **InsightFace embeddings**
* Fast similarity search using **FAISS**
* Automatic logging of detected individuals
* Interactive interface built with **Streamlit**

---

## Tech Stack

* Python
* PyTorch
* YOLOv11 (Ultralytics)
* InsightFace
* FAISS
* OpenCV
* Streamlit
* NumPy & Pandas

---

## System Pipeline

Video Input
⬇
Person Detection (YOLO)
⬇
Face Extraction
⬇
Face Embedding Generation
⬇
Similarity Search (FAISS)
⬇
Identity Matching
⬇
Logging & Visualization

---

## Installation

Clone the repository:

```bash
git clone https://github.com/mait-ai/CCTV-Face-Detection-Verification.git
cd CCTV-Face-Detection-Verification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Application

```bash
streamlit run main_2.py
```

Upload a CCTV video and the system will detect and identify faces.

---

## Example Use Cases

* CCTV surveillance
* Smart security systems
* Attendance monitoring
* Restricted area monitoring

---

## Future Improvements

* Multi-camera support
* Real-time CCTV stream processing
* Improved face recognition accuracy
* Web deployment

---

## License

This project is licensed under the **GPL-3.0 License**.
