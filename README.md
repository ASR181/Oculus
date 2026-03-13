# Oculus Gesture Mouse 👁️🖱️

Oculus Gesture Mouse is a production-ready, open-source desktop application that allows users to control their system mouse using webcam-based hand tracking. 

Built with **Python**, **PyQt6**, **OpenCV**, and **MediaPipe**, it prioritizes system safety, threading stability, and performance.

## 🚀 Features
- **Clean UI**: Modern dark-mode interface matching professional system tools.
- **Fail-Safe Processing**: Threaded OpenCV tracking prevents UI freezing.
- **Gesture Controls**: 
  - 👆 **Move**: Index finger up, others down.
  - 🤏 **Left Click**: Pinch index and middle finger quickly.
  - ⏱️ **Right Click**: Hold pinch for 2 seconds.
  - ↕️ **Scroll**: Move cursor to screen edges while moving.
- **Safety First**: Zero system files modified, edge-clamped mouse manipulation, and auto-camera release on exit.
- **Customization**: Full control over cursor smoothness, frame borders, and scrolling speeds via JSON config.

## ⚙️ Installation

**1. Clone the repository**
```bash
git clone https://github.com/yourusername/oculus-gesture-mouse.git
cd oculus-gesture-mouse
