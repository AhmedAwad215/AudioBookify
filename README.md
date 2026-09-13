PDF-to-Speech-Converter 🔊📄
Convert any PDF file into a spoken audio file (MP3) using Python.
The script extracts text from a PDF and converts it into natural-sounding speech.

Features=>
          *Extracts text from any PDF file page by page
          *Converts extracted text into speech using Google Text-to-Speech (gTTS)
          *Saves the output as an audio file
          *Simple, lightweight, and beginner-friendly

*Make sure the PDF contains selectable text (not scanned images), otherwise extract_text() will return nothing.
The output should be saved with a .mp3 extension since gTTS generates audio, not video.
