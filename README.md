# Face Recognition GUI with TensorFlow and Tkinter

This is a complete desktop-based **Face Recognition System** that uses a trained MobileNetV2 model to perform real-time or image-based face recognition via webcam or file upload. The application features a clean GUI built with **Tkinter**, integrates **OpenCV** for image processing, and supports dynamic confidence threshold adjustment.

---

## ✨ Features

- 🎥 Real-time face recognition from webcam
- 📁 Upload static image for recognition
- 🧠 Deep learning with MobileNetV2 (transfer learning)
- 🧪 Adjustable confidence threshold via slider
- 🖼️ Displays recognition results directly on video/image
- ✅ Easy-to-use graphical user interface (Tkinter)

---

## 📦 Project Structure

face-recognition-gui/
├── model/
│ ├── face_recognition_model.h5 # Trained model
│ └── classes.npy # Encoded class labels
├── assets/
│ └── example.jpg # (Optional) Sample image
├── main.py # GUI logic and inference code
├── train_model.py # Script for training the model
├── requirements.txt # Project dependencies
├── README.md # You're reading it!
└── .gitignore # Files/folders to ignore in version control

---

## ⚙️ Requirements

- Python 3.7+
- TensorFlow 2.x
- OpenCV
- NumPy
- Pillow
- scikit-learn
- imutils

Install them using:

```bash
pip install -r requirements.txt
##🚀 How to Run
🔧 1. Train Your Model (Optional)
If you want to train your own model on your dataset:
python train_model.py
Ensure your dataset is organized as:
Datasset/
├── Person1/
│   ├── image1.jpg
│   ├── image2.jpg
├── Person2/
│   ├── image1.jpg
│   └── ...
▶️ 2. Run the GUI App
python main.py
🖼️ GUI Features
Button	Function
Start Camera	Starts webcam feed
Stop Camera	Stops webcam
Live Recognition	Enables/disables real-time detection
Capture & Recognize	Captures current frame and predicts
Upload Image	Load and recognize a saved image
Confidence Threshold	Set prediction certainty (slider)
📷 Demo Screenshot
![tkinter_face_recognition_GUI](https://github.com/TeferiMulatu/Face-Detection/blob/bbcadcb48cf74f20028f62cb6291dce299face92/screenshot.png)

🙌 Acknowledgements
TensorFlow Keras

OpenCV

Pillow (PIL)

[Tkinter (built-in Python GUI)]

🤝 Contributing
Pull requests are welcome! Please open an issue first to discuss your changes.




