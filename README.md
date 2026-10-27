
# Multimodal AI Assistant

A Python-based desktop AI assistant that combines conversational AI, computer vision, and voice interaction in a single application.

## Features

- **Conversational AI:** Integrates Google Gemini Live API for AI-powered responses.
- **Desktop GUI:** Built using PySide6 for an interactive chat interface.
- **Computer Vision:** Uses OpenCV to capture and process camera frames.
- **Voice Responses:** Integrates ElevenLabs API for text-to-speech generation.
- **Audio Processing:** Captures microphone input and plays generated speech.
- **Asynchronous Processing:** Uses asyncio and threading to handle concurrent tasks.
- **File Operations:** Supports AI-assisted file and folder creation through function calls.

## Technologies Used

- Python
- PySide6
- Google Gemini API
- OpenCV
- ElevenLabs API
- PyAudio
- Pillow
- asyncio
- WebSockets

## Project Structure

```text
multimodal-AI/
├── main.py
├── requirements.txt
├── .gitignore
├── README.md
└── LICENSE
```

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/PREETHI-1804/multimodal-AI.git
   ```

2. Navigate to the project folder:

   ```bash
   cd multimodal-AI
   ```

3. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   ```

   Windows:

   ```bash
   .venv\Scripts\activate
   ```

   macOS/Linux:

   ```bash
   source .venv/bin/activate
   ```

4. Install dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

## API Configuration

Create a `.env` file in the project folder and add your own API keys:

```text
GEMINI_API_KEY=your_gemini_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
```

Replace the placeholders with your actual API keys. Never upload the `.env` file or expose your API keys publicly.

## Run the Application

```bash
python main.py
```

The application requires valid API credentials, a working microphone, audio output, and camera access when camera mode is enabled.

## Important Notes
This project is under development. Actual functionality depends on API availability, installed dependencies, and local hardware configuration. Test the application before claiming that every feature works successfully.

## Author
preethi kumari

GitHub: [PREETHI-1804](https://github.com/PREETHI-1804)
