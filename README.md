# 🖱️ Virtual Mouse Using Hand Gesture Recognition

This project is a computer vision-based virtual mouse that allows users to control cursor movement and click actions using hand gestures via a webcam. It uses Python and OpenCV to detect hand landmarks and translates gestures into real-time mouse events—creating a touchless, intuitive interface.

---

## 🚀 Features

- Real-time hand tracking using webcam input
- Move the mouse pointer using index finger
- Perform click actions with finger gestures
- No external hardware required
- Lightweight and easy to use

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV** – for image processing and webcam input
- **MediaPipe** – for accurate hand landmark detection
- **PyAutoGUI** – for controlling mouse events
- **NumPy**
- **Tkinter** (optional GUI interface)

---

## 📷 How It Works

1. The webcam captures the live video stream.
2. MediaPipe detects hand landmarks in real-time.
3. Specific finger gestures are mapped to mouse actions:
   - Move pointer: index finger movement
   - Left click: index + middle finger pinch
4. PyAutoGUI simulates the corresponding system mouse actions.

---

## 💻 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/Addi071/Virtual-mouse-.git
cd Virtual-mouse-
