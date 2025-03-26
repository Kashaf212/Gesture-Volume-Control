# Gesture Volume Control 🎚️✋

A Python-based computer vision project to control your system's volume using hand gestures detected via your webcam. This project leverages **OpenCV**, **MediaPipe**, and **pycaw** to provide a real-time gesture interface for volume control.

## 🚀 Features

- Real-time hand detection using **MediaPipe**
- Volume control by measuring the distance between thumb and index finger
- Smooth volume bar and percentage display
- FPS counter for performance tracking

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe (for hand landmark detection)
- pycaw (for Windows volume control)
- NumPy
- comtypes

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kashaf212/Gesture-Volume-Control.git
   cd Gesture-Volume-Control
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the project:
   ```bash
   python VolumeControl.py
   ```

## How It Works?

- The webcam captures live video.  
- MediaPipe detects hand landmarks.  
- The system calculates the distance between the thumb tip and index finger tip.  
- This distance is mapped to a volume range (0% to 100%) using pycaw.  
- Visual feedback (volume bar and percentage) is displayed on screen.

## Note

This script is designed for **Windows** using the **pycaw** library.  
For Mac/Linux users, a different audio control library would be needed.  

## To-Do

- Add gesture-based mute/unmute  
- Add support for multiple platforms (Mac, Linux)    
- Deploy the application  

## License

This project is open-source under the **MIT License**.


