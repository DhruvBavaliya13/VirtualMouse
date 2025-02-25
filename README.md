# 🖱️ Virtual Mouse using Hand Gestures  

Welcome to the **Virtual Mouse** project! This Python-based application allows users to control their computer mouse **using hand gestures** via a webcam, leveraging **computer vision and AI**. 🚀  

## 📌 Project Overview  

This project aims to:  

- 📷 Use **OpenCV and MediaPipe** for real-time hand tracking.  
- 🖐️ Detect hand landmarks to move the cursor.  
- 🖱️ Implement **clicking functionality** using thumb and index finger distance.  
- 🔄 Enable **gesture-based interaction** without physical devices.  

## 🛠️ Tech Stack  

- **Programming Language**: Python 🐍  
- **Libraries Used**:  
  - `OpenCV` - for real-time video processing  
  - `MediaPipe` - for hand tracking  
  - `PyAutoGUI` - for controlling the mouse cursor  

## 📜 Code Explanation  

1. 📥 **Capture video feed** from the webcam.  
2. ✋ **Detect hand landmarks** using MediaPipe Hands.  
3. 🎯 **Track index finger** to control mouse movement.  
4. 🖱️ **Detect thumb-index proximity** to trigger mouse clicks.  

## 🚀 How to Run  

1. Clone this repository:  
   ```sh
   git clone https://github.com/DhruvBavaliya13/VirtualMouse.git
   cd VirtualMouse
   ```  
2. Install dependencies:  
   ```sh
   pip install opencv-python mediapipe pyautogui  
   ```  
3. Run the script:  
   ```sh
   python virualMouse.py  
   ```  

## 📸 Demo  

🔹 Move the index finger to control the cursor.  
🔹 Tap the thumb and index finger together to **click**.  
![Screenshot (98)](https://github.com/user-attachments/assets/f49af1ed-47b4-471c-9cdb-653d62458b8c)


## 🤝 Contributing  

Feel free to **fork** this repository and submit a pull request if you have additional improvements!  

## 📬 Contact  

For any queries or collaboration opportunities, reach out via:  
📧 Email: [drbavaliya13@gmail.com](mailto:drbavaliya13@gmail.com)  

---

⭐ If you find this project useful, don't forget to **star** this repository! ⭐  

---

Let me know if you need any modifications! 🚀🔥
