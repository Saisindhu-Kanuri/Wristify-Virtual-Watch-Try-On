# 🕒 Wristify – Virtual Watch Try-On

**Virtual Wrist Watch Try-On** is a browser-based Augmented Reality (AR) application that enables users to virtually try on wristwatches in real time using their webcam. Built using modern web technologies and TensorFlow.js, this project blends computer vision and an intuitive UI to deliver a seamless and interactive virtual fitting experience — no app installation required!

---

## 🚀 Features

### 🔍 Real-Time Hand & Wrist Detection
- Utilizes **TensorFlow.js Handpose** model to accurately detect and track the user's wrist and hand landmarks through their webcam.
- Dynamically adjusts watch position to align with wrist movement in real time.

### ⌚ Smart Watch Overlay
- Allows users to virtually try on different watch images.
- Supports **rotation**, **scaling**, and **mirroring** to match the natural position and orientation of the wrist.
- Overlays are applied precisely using landmark-based mapping and Canvas API rendering.

### 🧼 Background Removal for Watch Images
- Upload any watch image and automatically remove the background.
- Ensures clean overlays that blend naturally with the video feed.

### 🖼️ Gesture-Based Zoom & Resize
- Users can zoom in/out on the watch or adjust its size to achieve a natural fit using intuitive hand gestures or manual controls.

### 💾 Export Functionality
- Capture a snapshot of your virtual try-on session with a single click and download the image.

### 📱 Fully Responsive UI
- Clean, modern, and mobile-friendly design using **Tailwind CSS**.
- Works across all major desktop and mobile browsers.

---

## 🛠️ Built With

- **HTML5** – Semantic structure and layout  
- **Tailwind CSS** – Utility-first responsive styling  
- **JavaScript (ES6+)** – Core logic, gesture handling, UI interactivity  
- **TensorFlow.js** – Real-time hand and wrist tracking using Handpose  
- **Canvas API** – Image overlay, rendering, and export  
- **MediaDevices API** – Webcam access for live video stream  

---

## 📸 How It Works

1. **Launch the App** – Grant webcam permissions to activate the live video stream.
2. **Hand Detection** – The system continuously detects your wrist and hand position.
3. **Watch Overlay** – A watch image is dynamically placed on your wrist in real time.
4. **Customization** – Adjust watch orientation, zoom, and size. Upload your own watch designs.
5. **Snapshot & Export** – Capture your try-on session and download the result as an image.

---

## 📂 Use Cases

- Virtual try-on experience for **e-commerce watch retailers**
- Interactive demo for **computer vision** and **AR/VR** coursework
- Prototype for **wearable tech UX/UI design** testing
- Fun and engaging **personal AR project**

---

## 🧠 Future Enhancements

- Add gesture-based interactions like **swipe to change watches**
- Support for **bracelet and smartwatch bands**
- Integration with **3D watch models** using WebGL
- Improved wrist-fit accuracy using multi-angle detection
- Dark mode and UI themes


