# AI Yoga Guide - Common Yoga Protocol 🧘‍♂️

This project is a high-performance AI Yoga Instructor designed according to the Ministry of AYUSH **Common Yoga Protocol (CYP)**.

## 🚀 Why this version works
1.  **Canvas Drawing:** Unlike standard video tags, this code draws the camera feed onto a `<canvas>`, allowing the AI "skeleton" to be overlaid directly on your body.
2.  **Interaction Gate:** Browsers block camera and audio by default. The "START SESSION" button acts as the manual override to enable these features.
3.  **Real-time Guidance:** It reads instructions and contraindications aloud using the **Web Speech API**.

## 🛠️ Setup
1.  Save the code as `index.html`.
2.  Open in **Chrome** or **Edge** (Safari may block certain scripts).
3.  Allow camera access when prompted.
4.  Stand back until your whole body (head to toe) is visible.

## 📐 AI Parameters
* **Detection Engine:** MediaPipe Pose.
* **Logic:** Calculates relative joint positions to verify balance stability.
