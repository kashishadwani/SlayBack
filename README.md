

````markdown
# 🎭 Emotion-Controlled Video Playback

Control video playback using your facial expressions. This system detects your mood through the webcam and adjusts the playback speed of a video accordingly—speed up, slow down, or pause—all without lifting a finger.

---

## 🚀 How It Works

1. **🎥 Video Playback**  
   - Uses **VLC’s Python bindings (`python-vlc`)** for reliable and responsive video playback.
   - Playback speed can be dynamically adjusted (fast-forward, slow-mo, pause).

2. **🧠 Face Detection**  
   - Utilizes **OpenCV’s Haar Cascade classifier** to detect faces in real-time from webcam input.

3. **😐 Emotion Analysis**  
   - Leverages **DeepFace** to analyze detected faces and classify emotions (e.g., *happy*, *sad*, *angry*, *neutral*, etc.).

4. **⚙️ Action Triggering**  
   - When a consistent emotion is detected over a few frames:
     - 😄 **Happy** → Speed up
     - 😐 **Neutral** → Normal speed
     - 😞 **Sad** → Slow down
     - 😠 **Angry** → Pause the video

5. **📊 UI Feedback**  
   - Real-time on-screen display showing:
     - Your current emotion
     - Current video speed

---

## 📦 Requirements

- Python 3.7 or above
- `opencv-python`
- `python-vlc`
- `deepface`
- `numpy`

Install all dependencies using:

```bash
pip install opencv-python python-vlc deepface numpy
````

---

## ▶️ How to Run

1. Clone the repository.
2. Make sure your webcam is connected.
3. Update the path to the video file in the script if needed.
4. Run:

```bash
python slayback.py --video path/to/your/video.mp4
```

---

## 🧠 Use Cases

* Accessibility for motor-impaired users
* Emotion-aware learning platforms
* Mood-reactive art installations
* Personalized media experiences

---

## 🔮 Future Ideas

* Add voice command fallback
* Support YouTube or streaming platforms
* Add sensitivity settings for emotion detection
* Custom mappings of emotions to actions

---

## 📸 Demo

Coming soon...

---

## 🤖 Built with curiosity, caffeine, and a face full of expressions.

```

