# AI Yoga Instructor 🧘‍♂️

A real-time, browser-based AI Yoga Assistant that uses Computer Vision to guide users through the **Vrikshasana (Tree Pose)**.

## ✨ Features
* **Real-time Pose Tracking:** Uses MediaPipe Pose to detect 33 body landmarks.
* **AI Bio-feedback:** Provides instant stability scores based on joint alignment.
* **Voice Instruction:** Integrated Web Speech API for hands-free guidance.
* **No Server Required:** Runs entirely in the browser using TensorFlow.js.

## 🛠️ Built With
* [MediaPipe](https://mediapipe.dev/) - For body tracking.
* [TensorFlow.js](https://www.tensorflow.org/js) - Machine Learning in the browser.
* [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) - For AI voice feedback.

## 🚀 How to Run
1. Clone the repository.
2. Open `index.html` in a modern web browser (Chrome or Edge).
3. Grant camera permissions and start your practice!

## 📐 How it Works
The AI calculates the distance between the knee and ankle landmarks ($y$-coordinates) to determine if a leg is lifted. It then measures the variance in movement to generate a **Stability Score**.
