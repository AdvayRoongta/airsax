# Airsax

A computer vision project that lets you play tenor saxophone fingerings in the air using just your hands and a webcam. The notes are real, I recorded them myself on my tenor sax and mapped them to hand positions detected by Mediapipe.

Demo: [YouTube](https://www.youtube.com/watch?v=hacINoEem5s)

---

## Features

- Covers 16 notes from low D to high C, including F# and Gb
- Left-hand thumb acts as the octave key, same as on a real saxophone
- Fingering patterns match actual tenor sax fingerings, so it's learnable if you already play
- Built entirely in Python using OpenCV and Mediapipe — no hardware needed

---

## How It Works

Mediapipe tracks your hands in real time through a webcam feed. Each frame, your finger positions are compared against a lookup of standard tenor saxophone fingerings. When a match is found, the corresponding audio sample plays back. The left thumb is tracked separately as an octave key — raise it and the same fingering jumps up an octave, just like on the physical instrument.

---

## Installation

```bash
git clone https://github.com/AdvayRoongta/airsax
cd Visioneer
pip install -r requirements.txt
python main.py
```

Python 3.8+ recommended. A working webcam and audio output are required.

---

## Notes

The audio samples are dry recordings with no processing, which keeps latency low. If you already play saxophone, the fingerings will feel familiar. If you don't, there are plenty of fingering charts online for tenor sax that apply directly here.
