project:
  itle: 🛑 Driver Drowsiness Detection
  tagline: "Because a blink too long can cost a life."
  description: >
    A real-time system that monitors signs of drowsiness in drivers using facial landmark detection. 
    By tracking eye blinks and yawns through your webcam, it raises alerts when fatigue is detected — helping prevent accidents before they happen.

tech_stack:
  languages:
    - 🐍 Python 3.x
  libraries:
    - 📷 OpenCV (for real-time video processing)
    - 🔍 Dlib (for facial landmark detection)
    - 🧮 NumPy
    - 📐 Math module
  concepts:
    - 👁️ Eye Aspect Ratio (EAR)
    - 👄 Mouth Aspect Ratio (MAR)
    - 🧠 68-point facial landmark detection
    - 🖥️ Real-time visual alert system

features:
  - ✅ Detects prolonged eye closure and yawning in live video
  - 🎯 Displays green or red face boxes based on alertness
  - 📈 Continuously monitors and shows EAR and MAR values
  - 🧩 Modular code structure for easy feature additions

impact:
  - 🚗 Promotes road safety by monitoring driver alertness
  - 💻 Improved understanding of computer vision techniques
  - 🧠 Enhanced hands-on experience with real-time detection

usage_guide:
  setup:
    prerequisites:
      - Python 3.x
      - Webcam enabled device
      - shape_predictor_68_face_landmarks.dat model file
    install_commands:
      - pip install opencv-python dlib numpy
    download_model:
      - http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
  run_steps:
    - Place the `.dat` file in the same directory as the script
    - Run the script:
      ```bash
      python drowsiness_detection.py
      ```

file_structure:
  - drowsiness_detection.py: Main detection script
  - shape_predictor_68_face_landmarks.dat: Required facial landmark model
  - README.yml: Structured project documentation

project_status: ✅ Completed and functional  
future_scope:
  - 🔊 Add buzzer or sound alert system
  - 📦 Package as a standalone desktop app
  - 📱 Extend for use in mobile applications

note: |
  ⚠️ This project is for educational and demo purposes only. Not intended for deployment in real-world vehicles without further testing.

license: MIT
