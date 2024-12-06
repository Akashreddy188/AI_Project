# AI Translator with OCR & Voice Input

An AI-powered Streamlit application that provides language translation, text-to-speech functionality, optical character recognition (OCR), and voice input transcription, making it a versatile and accessible tool for multilingual communication.

## Demo Link

https://github.com/user-attachments/assets/58a29397-e72e-4088-8d19-718939750d70


## Business Understanding
The AI Translator with OCR & Voice Input aims to break language barriers by combining text-based, image-based, and voice-based translation into a single platform.

**Purpose**: Provide a seamless and efficient way to translate text, images, and spoken language into the desired target language.  
**Challenges Addressed**: Multilingual communication, accessibility for people with visual impairments, and creating a user-friendly interface.

## Data Understanding
The application uses the Google Translate API for language translation and Tesseract OCR for extracting text from images. Audio input is processed using the SpeechRecognition library, making it possible to detect and transcribe spoken words.

### Data Sources:
- User-provided text, images, and audio files.
- Google Translate API for translation.
- Tesseract for OCR.

## Technologies
- **Frontend**: Streamlit  
- **APIs**: Google Translate API  
- **OCR**: Tesseract OCR  
- **Speech Recognition**: SpeechRecognition library, Google Text-to-Speech (gTTS)  
- **Programming Language**: Python  
- **Additional Libraries**: `pyttsx3`, `threading`, `tempfile`, `PIL (Python Imaging Library)`

## Approach

### Language Translation:
- Detect the source language and translate the text to the target language using the Google Translate API.

### OCR:
- Extract text from uploaded images using Tesseract OCR.
- Translate the extracted text to the target language.

### Voice Input:
- Record and transcribe audio using the `SpeechRecognition` library.
- Translate the transcribed text to the target language.
- Use Google Text-to-Speech (gTTS) to synthesize translated speech.

## Status
- **Current Version**: 1.0  
- **Status**: Complete  

### Future Enhancements:
- Add support for offline OCR functionality.
- Enable multilingual voice output for enhanced user experience.

## Libraries and Tools:
- **Streamlit**: For creating the web-based interface.
- **Google Translate API**: For language translation.
- **Tesseract OCR**: For text extraction from images.
- **SpeechRecognition**: For voice input transcription.
- **gTTS (Google Text-to-Speech)**: For synthesizing speech.
- **pyttsx3**: For additional text-to-speech options.
- **Pillow (PIL)**: For image processing.

## Contributing
Contributions are welcome! If you would like to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.



## Contact
For any queries or feedback, feel free to reach out:
- **Email**: vamshikrishnamatsa@gmail.com
- **GitHub**: [vamshikrishnamatsa](https://github.com/vamshikrishnamatsa)
