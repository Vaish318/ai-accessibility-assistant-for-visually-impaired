# AI Accessibility Assistant for Visually Impaired

This project is an AI-powered accessibility system designed to assist visually impaired users through voice commands, text-to-speech, speech-to-text, OCR text reading, object detection, and navigation assistance. The system integrates multiple AI components to provide an interactive and helpful digital assistant.

---

## Features

### 1. Voice Interaction
- Converts speech into text using SpeechRecognition
- Provides audible responses using pyttsx3
- Enables hands-free interaction

### 2. Optical Character Recognition (OCR)
- Reads text from images using Tesseract OCR or EasyOCR
- Helps users read documents, labels, signs, menus, and more

### 3. Object Detection
- Detects everyday objects using MobileNet-SSD (OpenCV DNN)
- Assists users in understanding their environment

### 4. Navigation Assistance
- Converts place names into coordinates using Geopy
- Generates routes using OSRM API
- Provides turn-by-turn direction instructions

### 5. Gradio Interface
- A simple GUI to test:
  - OCR  
  - Object detection  
  - Navigation  
  - Voice recognition  
  - Text-to-speech  

---

## Technology Stack

| Component | Technology |
|----------|------------|
| Language | Python |
| OCR | Tesseract OCR, EasyOCR |
| Object Detection | MobileNet-SSD (OpenCV DNN) |
| Speech-to-Text | SpeechRecognition |
| Text-to-Speech | pyttsx3 |
| Navigation | Geopy + OSRM |
| User Interface | Gradio |
| Development | Jupyter Notebook, macOS |

---

## Project Structure

## Project Structure

```
ai-accessibility-assistant-for-visually-impaired/
    ai_accessibility_assistant.ipynb        - Main Jupyter notebook
    ai_assist_helpers.py                    - OCR, object detection, navigation, voice functions
    gradio_app.py                           - Gradio demo application
    ai_project_requirements.txt             - Python dependencies
    README.md                               - Project documentation
    .gitignore                              - Git ignored files
```


## Installation
### 1. Clone the Repository
git clone https://github.com/Vaish318/ai-accessibility-assistant-for-visually-impaired.git
cd ai-accessibility-assistant-for-visually-impaired

### 2. Install Dependencies
pip install -r ai_project_requirements.txt

### 3. Install Tesseract OCR
macOS:
brew install tesseract
Ubuntu:
sudo apt install tesseract-ocr
Windows:  
Download from https://github.com/tesseract-ocr/tesseract

## Running the Notebook
Start Jupyter Notebook:
jupyter notebook
Open:
ai_accessibility_assistant.ipynb
Features available inside:
- OCR  
- Object Detection  
- Navigation  
- Speech Recognition  
- Text-to-Speech  

## Running the Gradio Demo
python gradio_app.py
This launches a local web interface where you can test all system features.

## Use Cases
- Reading documents, books, signs, and labels
- Object awareness in daily surroundings
- Navigation assistance for pedestrians
- Voice-controlled accessibility companion
- Assistive technology for visually impaired users

## Future Enhancements
- Real-time camera-based obstacle detection
- Integration with smart cane or wearable devices
- Offline speech recognition models
- Multi-language support
- Face recognition
- Mobile application version

## Contributing
Contributions are welcome. Submit issues or pull requests to enhance the project.

## Author
**Vaishnavi Harish**  
GitHub: https://github.com/Vaish318
