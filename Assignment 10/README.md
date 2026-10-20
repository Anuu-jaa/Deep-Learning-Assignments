# Assignment 10

Deep Learning Lab Assignment 10.

# Audio Classification Using Deep Learning: Speech-to-Text and Text-to-Speech

## Aim
To design and implement a deep learning application for audio processing that incorporates Speech-to-Text (STT) and Text-to-Speech (TTS), and evaluate its performance using suitable metrics.

## Problem Statement
Design and implement a deep learning application for audio classification that incorporates Speech-to-Text and Text-to-Speech using appropriate deep learning architecture and evaluate its performance using suitable metrics.

## Technologies Used
- **Python** – Programming language
- **Google Colab** – Execution environment
- **OpenAI Whisper** – Deep learning-based speech recognition
- **gTTS (Google Text-to-Speech)** – Speech generation
- **JiWER** – Word Error Rate evaluation
- **FFmpeg** – Audio processing
- **IPython Audio** – Audio playback in the notebook

## Features
1. Upload audio files in WAV, MP3, or M4A format.
2. Convert spoken audio into text using the Whisper model.
3. Detect the language of the input audio.
4. Display the recognized text and play the original audio.
5. Evaluate transcription performance using Word Error Rate (WER).
6. Convert recognized text into speech using gTTS.
7. Play and download the generated MP3 audio.
8. Display processing time and performance evaluation results.

## Algorithm
1. Install the required libraries.
2. Import the necessary modules.
3. Load the pre-trained Whisper model.
4. Upload an audio file.
5. Preprocess the audio and perform speech recognition.
6. Display the recognized text and detected language.
7. Enter the reference transcript and calculate WER.
8. Convert the recognized text into speech using gTTS.
9. Play and download the generated speech.
10. Display the final performance metrics.

## Performance Evaluation
The application evaluates speech recognition using the following metrics:

- **Word Error Rate (WER):** Measures transcription errors compared with the reference transcript. Lower values indicate better transcription performance.
- **Approximate Word Accuracy:** Calculated as (1 − WER) × 100 when WER is between 0 and 1.
- **STT Processing Time:** Measures the time required to transcribe the input audio.
- **TTS Generation Time:** Measures the time required to generate the output speech.

## Requirements
- Python 3
- Google Colab account
- Internet connection
- An audio file containing speech
- Required Python libraries: `openai-whisper`, `gTTS`, and `jiwer`
- FFmpeg audio processing utility

## How to Run
1. Open Google Colab and create a new notebook.
2. Copy the Python code into the notebook cells.
3. Run the cells in sequence.
4. Upload an audio file when prompted.
5. Enter the correct reference transcript.
6. Observe the recognized text and evaluation metrics.
7. Listen to and download the generated speech audio.

## Expected Output
- Recognized speech text
- Detected language
- Original audio playback
- Word Error Rate and approximate word accuracy
- Speech-to-Text processing time
- Generated speech playback
- Downloadable MP3 output
- Final performance evaluation report

## Applications
- Voice-controlled applications
- Speech transcription systems
- Accessibility tools
- Language learning applications
- Voice assistants
- Audio-based information processing

## Conclusion
This practical demonstrates the integration of deep learning-based speech recognition and text-to-speech synthesis. Whisper converts spoken audio into text, while gTTS generates speech from the recognized text. Word Error Rate and processing time are used to evaluate the system's performance.
