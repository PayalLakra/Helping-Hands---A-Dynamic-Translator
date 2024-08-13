Helping Hand - Dynamic Translator:: It is a dynamic translation application offering a range of functionalities to help with language translation, speech synthesis, and text extraction. 

## Features

- **Text-to-Text Translation**: Translate text from one language to another.
- **Text-to-Speech**: Convert written text to spoken words with various voice options.
- **Speech-to-Text**: Convert spoken language into text.
- **File-to-Speech**: Read aloud text content from files.
- **Speech-to-Speech**: Translate spoken language into another spoken language in real-time.
- **Image-to-Text & Speech**: Extract text from images and read it aloud.

## Libraries Used

- **tkinter**: Standard GUI toolkit for graphical user interfaces.
- **customtkinter**: Enhanced version of tkinter with a modern look and additional features.
- **googletrans**: Interfaces with Google Translate for language translation.
- **pyttsx3**: Text-to-speech conversion library.
- **speech_recognition**: Library for speech recognition.
- **pytesseract**: OCR tool for extracting text from images.

## Screenshots

![Screenshot 1](https://github.com/user-attachments/assets/f4ee2b57-6903-43ab-88b4-b2f685dcc0a7)
![Screenshot 2](https://github.com/user-attachments/assets/7a0e1f8d-a62e-481a-8fcd-243d070f6437)
![Screenshot 3](https://github.com/user-attachments/assets/2d961ae3-1c31-4db2-ac10-760f390baa22)
![Screenshot 4](https://github.com/user-attachments/assets/e14b3cdb-dd1c-4db4-a786-d691d7c92a00)
![Screenshot 5](https://github.com/user-attachments/assets/1d21cab7-bcca-400e-a5da-741853767640)
![Screenshot 6](https://github.com/user-attachments/assets/8292195e-45f9-4b7f-97d0-86d8c7cd5017)
![Screenshot 7](https://github.com/user-attachments/assets/8d9c97dc-6430-49c2-a2b3-d733d545a4d7)
![Screenshot 8](https://github.com/user-attachments/assets/9ac0cd20-922f-43c4-91aa-f389a50cbc73)

## Requirements

- Python 3.x
- Tesseract-OCR (must be installed separately)

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/PayalLakra/Helping-Hands---A-Dynamic-Translator.git
   cd Helping-Hands---A-Dynamic-Translator
   ```

2. **Install the Required Python Packages**

   ```bash
   pip install -r requirements.txt
   ```

3. **Install Tesseract-OCR**

   - Download and install Tesseract-OCR from [here](https://github.com/tesseract-ocr/tesseract).
   - Ensure the path to the Tesseract executable is set correctly in the script. Adjust the path in the script file:

     ```python
     import pytesseract
     pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
     ```

## Usage

Run the application by executing:

```bash
python CodeTranslator.py
```


