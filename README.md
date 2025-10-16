🖐️ HandTalk: Real-Time ASL Interpreter using MediaPipe

HandTalk is a real-time American Sign Language (ASL) and gesture recognition system that uses MediaPipe, OpenCV, and deep learning to interpret hand gestures into spoken and written language. The project bridges the communication gap between sign language users and non-signers by translating gestures into text and speech — with multi-language support (English, Kannada, Hindi, Telugu).

⸻

🚀 Features
	•	🎥 Real-time Hand Tracking using Google’s MediaPipe Hands
	•	🧠 Gesture Classification powered by a custom-trained neural network
	•	🔤 Automatic Translation of recognized gestures into multiple languages
	•	🔊 Speech Output via text-to-speech (TTS) in the selected language
	•	🖋️ Unicode Support for Indian languages (Kannada, Hindi, Telugu)
	•	💾 Data Logging Mode — capture new gesture samples for model training
	•	🧩 Menu Interface for switching languages during live recognition

⸻

🧰 Tech Stack
	•	Python 3
	•	OpenCV – for camera input and visual overlays
	•	MediaPipe – for hand landmark detection
	•	TensorFlow / Keras – for gesture classification models
	•	PIL (Pillow) – for rendering Unicode text
	•	pyttsx3 / playsound – for speech synthesis
	•	NumPy, CSV, Argparse – for utilities and dataset handling

⸻

📦 Project Structure:
hand-gesture-recognition-mediapipe-main/
│
├── app.py                             # Main application
├── model/                             # Pre-trained gesture classification models
├── utils.py                           # FPS calculation and helper functions
├── fonts/                             # Unicode fonts for language rendering
├── voices/                            # Pre-recorded or TTS-generated audio clips
└── requirements.txt                   # Dependencies
🧑‍💻 How It Works
	1.	The webcam captures a live video feed.
	2.	MediaPipe detects and tracks the user’s hand landmarks in real time.
	3.	A trained classifier predicts the performed gesture.
	4.	The recognized gesture is translated into the selected language using a predefined dictionary.
	5.	The system displays the text on screen and converts it to speech.

⸻

🌐 Supported Languages
	•	English 🇺🇸
	•	Kannada 🇮🇳
	•	Hindi 🇮🇳
	•	Telugu 🇮🇳

⸻

🗣️ Demo

(Add a GIF or short video clip showing the real-time translation in action)

⸻

🧩 Future Improvements
	•	Add support for continuous sign sentences
	•	Improve dataset and model accuracy
	•	Integrate camera calibration for better hand detection
	•	Build a lightweight mobile version

⸻

❤️ Authors

Harshavardhana & Team
B.E. Final Year Project — 2025
