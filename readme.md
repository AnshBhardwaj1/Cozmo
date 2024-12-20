# Cozmo - Your AI Digital Pet

This is my submission for SDSLabs Makers'. Cozmo is a fun and interactive AI-powered digital pet that can listen, talk, respond dynamically, and express emotions through facial animations. This project integrates multiple technologies to simulate the behaviors of Cozmo, making it a delightful and engaging experience.

## Features

- **Conversational Skills:** Powered by OpenAI's ChatGPT API for dynamic and context-aware interactions.
- **Emotion Recognition:** Uses IBM Watson NLP to analyze and classify emotions in user input.
- **Facial Animations:** Displays Cozmo's emotions (happy, sad, surprised, etc.) using Python's Tkinter library.
- **Voice Interaction:**
  - **Speech-to-Text (STT):** Allows users to interact with Cozmo via voice commands.
  - **Text-to-Speech (TTS):** Gives Cozmo a robotic voice, with pitch modulation for emotion-based expressions.

## Tech Stack

- **Programming Language:** Python
- **APIs and Libraries:**
  - OpenAI API (ChatGPT for conversation generation)
  - IBM Watson NLP (Emotion classification)
  - Tkinter (Facial animations)
  - pyttsx3 (Text-to-Speech)
  - SpeechRecognition (Speech-to-Text)

## How It Works

1. **Voice Input:** Users speak to Cozmo, and Speech-to-Text (STT) converts the voice input into text.
2. **Emotion Detection:** The text is analyzed using IBM Watson NLP to detect emotions.
3. **Response Generation:** Cozmo generates a conversational response using OpenAI's ChatGPT API.
4. **Voice Output:** The response is vocalized using Text-to-Speech (TTS) with robotic tone modulation.
5. **Facial Animation:** Cozmo displays an emotion-matched facial expression using Tkinter.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AnshBhardwaj1/cozmo.git
   cd cozmo-ai-pet
   ```

2. Install dependencies:
   ```bash
   pip install openai ibm-watson python-tk pyttsx3 SpeechRecognition pygame
   ```

3. Set up API Keys:
   - OpenAI API key for ChatGPT.
   - IBM Watson API key for emotion classification.

4. Run the application:
   ```bash
   python cozmo.py
   ```

## Usage

1. Start the program and interact with Cozmo via voice.
2. Observe Cozmo's responses, voice output, and animated facial expressions.
3. Have fun exploring its dynamic responses and emotions!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
