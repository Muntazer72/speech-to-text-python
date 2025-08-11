# 1🎙️ Speech-to-Text Jupyter Notebook

A simple and effective Jupyter-based tool that converts speech in audio files (MP3/WAV) to text using Python. Powered by Google Speech Recognition and `pydub`.

## 🚀 Features
- Converts MP3 to WAV
- Transcribes speech to text
- Runs entirely in a Jupyter Notebook
- Works inside a virtual environment

## 🛠️ Setup Instructions

### 1. Clone the Repository

git clone https://github.com/yourusername/speech-to-text.git
cd speech-to-text
# 2. Create and Activate Virtual Environment
python -m venv env
# Activate:
# Windows
env\Scripts\activate
# macOS/Linux
source env/bin/activate
# 3. Install Requirements
pip install -r requirements.txt
# 4. Launch Jupyter Notebook
jupyter notebook
Then open SpeechToText.ipynb and run the cells.
# 5. File Structure
speech-to-text/
├── audiobook.wav         ← Your audio file
├── SpeechToText.ipynb    ← Jupyter notebook
├── requirements.txt
└── README.md

# 6.💡 Notes

Google’s API needs an internet connection.
Best results come from clean, clear audio.
Supports .mp3 and .wav input files.



