# 🎷 Visioneer: The Invisible Saxophone

**Play the saxophone — without the saxophone!**  
Visioneer (also known as **AirSax**) lets you perform realistic saxophone fingerings in the air, and it plays back real tenor sax notes that you recorded yourself. Built entirely in Python, this computer vision project turns your hands into an instrument.

🎥 **Demo:** [Watch on YouTube](https://www.youtube.com/watch?v=hacINoEem5s)

---

## 🌟 Features

- 🎵 **Realistic Saxophone Fingerings** – Hold down the same keys you'd use on a real tenor saxophone.  
- 🖐️ **Octave Key Support** – Use your left-hand thumb as an octave key to jump up an octave.  
- 🎶 **16 Unique Notes** – From low D to high C, with some sharps and flats (like F# and Gb).  
- 🧠 **Fully Hand-Tracked** – Powered by OpenCV and Mediapipe for accurate hand detection.  
- 🐍 **Built 100% in Python** – No external hardware required.  
- 🎷 **Authentic Sound** – All tenor saxophone notes were recorded by the creator.

---

## 🧩 How It Works

1. **Hand Tracking:** Mediapipe detects your hands in real time.  
2. **Finger Mapping:** Your fingers’ positions are matched to saxophone key patterns.  
3. **Note Playback:** The corresponding recorded saxophone note plays instantly.  
4. **Octave Control:** Your left thumb toggles the octave — just like the real thing.

In short, Visioneer makes it possible to play a virtual saxophone using only your hands and a webcam.

---

## ⚙️ Installation

Follow these steps to run the project locally:

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/Visioneer.git
cd Visioneer

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the project
python main.py
