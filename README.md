# Transcriber

Audio Preprocessing & Transcription Pipeline
This project automates the process of cleaning and transcribing audio recordings using Python, PyDub, and OpenAI's Whisper model.

Features
Silence Removal: Automatically detects and removes long silences from recordings using PyDub, making the audio more concise and easier to analyze.

Audio Preprocessing: Combines non-silent segments and exports a cleaned .wav file.

Speech-to-Text Transcription: Utilizes the openai/whisper-large-v3-turbo model for accurate transcription with word-level timestamps.

Google Colab Compatible: Easily run and manage everything in a Colab notebook with Google Drive integration.

How It Works
Mount Google Drive to access audio files.

Detect and trim silence based on custom dB and duration thresholds.

Export the cleaned audio as a new .wav file.

Transcribe the audio using the Whisper ASR pipeline from Hugging Face Transformers.
