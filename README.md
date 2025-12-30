# AI Yoga Instructor: Ministry of AYUSH (CYP) Edition 🧘‍♂️🇮🇳

A professional, real-time AI Yoga platform that implements the **Common Yoga Protocol (CYP)** as defined by the Ministry of AYUSH, Government of India. This application uses computer vision to provide a humanistic, guided yoga experience.

## ✨ Features
* [cite_start]**CYP Compliance:** Guided sequences including Standing, Sitting, and Lying postures[cite: 6].
* [cite_start]**Humanistic AI Voice:** Emulates a real instructor by providing intros, contraindications, and real-time encouragement [cite: 74-75].
* [cite_start]**Safety First:** Voice alerts for contraindications (e.g., vertigo, cardiac issues) before every practice[cite: 80, 158].
* [cite_start]**Precision Monitoring:** Uses MediaPipe Pose to calculate anatomical angles and stability scores[cite: 51].

## 📋 Practices Included (CYP Sequence)
The platform monitors and scores the following practices based on official guidelines:

1.  [cite_start]**Standing Postures:** Tādāsana (Stability), Vṛkṣāsana (Balance), Pāda-Hastāsana (Flexibility), Ardha Çakrāsana, and Trikoṇāsana[cite: 131, 139, 148, 160, 168].
2.  [cite_start]**Sitting Postures:** Bhadrāsana, Vajrāsana, and Vakrāsana[cite: 180, 194, 201].
3.  [cite_start]**Lying Postures:** Bhujaṅgāsana (Cobra), Śalabhāsana, and Pavanamuktāsana[cite: 212, 222, 245].

## 🛠️ Technical Architecture
* **Vision Engine:** MediaPipe Pose (33 body landmarks).
* **Logic:** Custom JavaScript "State Machine" to handle the Yoga Practice Lifecycle:
    1.  [cite_start]*Instruction & Caution* [cite: 80]
    2.  [cite_start]*Position Setup* [cite: 75]
    3.  [cite_start]*Guided Holding & Counting* [cite: 135, 153]
    4.  [cite_start]*Performance Scoring* [cite: 51]
* **Interface:** HTML5/CSS3 with Web Speech API for the "Gemini-style" voice.

## 🚀 Getting Started
1.  Open `index.html` in a browser.
2.  Click **"START SESSION"** to initialize the voice engine.
3.  Ensure your full body is visible to the camera.
4.  Follow the voice prompts for a 100% hands-free practice.

## ⚠️ Disclaimer
[cite_start]This protocol is intended to create general awareness and is not a substitute for medical advice[cite: 398, 399]. [cite_start]Always consult a physician if you have chronic pain or cardiac conditions before practicing[cite: 72].
