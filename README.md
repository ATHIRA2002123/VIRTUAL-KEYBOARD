# 🤖 Hand Gesture Controlled Virtual Keyboard Using Python

## 📌 Project Overview

The **Hand Gesture Controlled Virtual Keyboard** is a Python-based application that allows users to type without using a physical keyboard. It uses a webcam to detect hand movements and recognize finger gestures to interact with an on-screen keyboard.

The application is developed using **OpenCV, CVZone, and NumPy**. It uses computer vision and hand tracking technology to identify finger positions and detect gestures.

Users can select virtual keys by bringing their index finger and middle finger together.

## 🎯 Objectives

- To develop a virtual keyboard using Python.
- To implement hand tracking using computer vision.
- To enable typing through hand gestures.
- To provide an alternative method of text input.
- To understand real-time image processing and gesture recognition.

## ✨ Features

- Real-time hand detection using a webcam.
- Interactive on-screen keyboard.
- Hand gesture-based key selection.
- Pinch gesture recognition using index and middle fingers.
- Text display area to show typed characters.
- Backspace functionality to delete characters.
- Simple and user-friendly interface.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Computer Vision:** OpenCV
- **Hand Tracking:** CVZone
- **Numerical Processing:** NumPy
- **IDE:** Visual Studio Code
- **Version Control:** Git and GitHub

## 💻 Requirements

- Python 3.x
- Webcam
- Visual Studio Code or another Python IDE
- Required Python libraries: OpenCV, CVZone, NumPy, and MediaPipe.

## 🚀 How to Use

1. Connect a webcam to your computer.
2. Run the Python application.
3. Allow the application to access the webcam.
4. Show your hand in front of the camera.
5. Move your index finger over the desired virtual key.
6. Bring your index finger and middle finger together to select the key.
7. The selected character will appear in the text display area.
8. Use the `<--` key to delete the last character.
9. Press **Q** on the physical keyboard to close the application.

## 🖐️ Working Principle

The application works using the following steps:

1. **Webcam Capture:** OpenCV captures real-time video through the webcam.
2. **Hand Detection:** CVZone's HandDetector identifies the hand and tracks its landmarks.
3. **Finger Position Detection:** The application tracks the index finger tip (landmark 8).
4. **Key Selection:** It checks whether the index finger is positioned over a virtual keyboard button.
5. **Gesture Recognition:** The distance between the index finger tip (landmark 8) and middle finger tip (landmark 12) is calculated.
6. **Character Input:** When the distance is less than 30 pixels, the selected key is activated.
7. **Text Display:** The selected character is displayed in the text bar.

## 📚 Learning Outcomes

- Understanding Python programming.
- Learning computer vision concepts.
- Implementing real-time hand tracking.
- Understanding hand landmarks and finger detection.
- Learning gesture recognition.
- Working with OpenCV and CVZone libraries.
- Developing interactive applications using Python.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

Feel free to fork this repository and submit a pull request.

## 👨‍💻 Author

Athira Mohan
GitHub: https://github.com/athira20122002-ui

## 📄 License

This project is developed for educational purposes. You can add an open-source license such as the MIT License if you wish to distribute it under those terms.

---

⭐ If you find this project interesting, consider giving the repository a star!
