# Face-Detector-using-OpenCV

---
# 🧠 Real-Time Face Detection using OpenCV

This project is a simple real-time **face detection system** built with **Python** and **OpenCV**. It uses a pre-trained Haar Cascade classifier to detect human faces in live video captured from your webcam.

## 🔍 Features

- 📷 Captures live video from the webcam
- 🧠 Detects faces in real-time using Haar Cascades
- 🟩 Highlights detected faces with bounding boxes
- ⏹️ Press `q` to quit the application gracefully

---

## 📦 Requirements

- Python 3.x
- OpenCV

Install dependencies using pip:

pip install opencv-python
```

---

## 🚀 How to Run

1. Clone the repository:

git clone https://github.com/yourusername/face-detection-opencv.git
cd face-detection-opencv
```

2. Run the script:

python face_detection.py
```

3. A window will open showing your webcam feed with detected faces highlighted in green. Press `q` to exit.

---

## 🧠 How It Works

- Loads OpenCV's pre-trained **Haar Cascade** model for detecting frontal faces.
- Captures real-time video feed using your computer's **default webcam**.
- Converts each frame to **grayscale**, as Haar cascades work best on grayscale images.
- Applies `detectMultiScale()` to identify faces in the frame.
- Draws rectangles around all detected faces for visualization.

---

## 📁 File Structure

```
face-detection-opencv/
│
├── face_detection.py        # Main Python script
├── README.md                # Project README
```

## 🔧 Future Enhancements

- Eye and smile detection
- Save detected face images
- Count and display number of faces
- Use deep learning for better accuracy (e.g., DNN, face_recognition)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Credits

Built with ❤️ using [OpenCV](https://opencv.org/)
```
