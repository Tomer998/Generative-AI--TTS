# Your-TTS: Achieving Zero-Shot Multilingual TTS

Your-TTS is an advanced text-to-speech (TTS) model designed for zero-shot generation of speech
for previously unseen speakers. Building upon the VITS architecture, our model incorporates
chaining the YourTTS model with transcription of Hebrew text, translating the text from Hebrew
to English, and then generating English speech while using the original Hebrew speech as reference audio. This project specifically explores the model’s zero-shot capabilities with Hebrew, a
language excluded from the original training dataset, demonstrating the model’s ability to generalize across linguistic boundaries.
