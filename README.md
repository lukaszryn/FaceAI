# Recognition-Text-Translator

Recognition-Text-Translator is a Python application that recognizes speech in real-time, converts it to text, and then translates the text into the selected language. The application uses the Tkinter library for the graphical interface, Google Speech Recognition for speech-to-text conversion, and the `translate` module for translations.

# Notes

- **Microphone Setup:** Ensure that your microphone is correctly configured and working. Alternatively, you can enable the Stereo Mix option on Windows, allowing the application to capture sound from the computer.

- **Translation Limitations:** The application uses an online translation API, so an internet connection is required.

## Project Structure

### Folders and Files:

1. **`Program - demo/`**
   - **`Demo-Translator.exe`** – This is a ready-to-use executable file of the application, created for Windows users. You can run it without needing to install Python or any additional dependencies.
     - **Location**: `Program - demo/Demo-Translator.exe`
     - **How to use**: Just double-click the `Demo-Translator.exe` file to launch the application. It is ready to use without further configuration.
  
2. **`Project/`** 
   - Contains all the necessary files such as scripts and images required to run the Python application from the source code.
   
   Files in this folder:
   - **`recognition.py`** – The main script of the application. It handles speech recognition, text translation, and the graphical user interface.
     - **Location**: `Project/recognition.py`
     - **Description**: This file starts the Python application. You can run it through a Python environment.
     - **How to use**: Run this file in the terminal using the command `python recognition.py` after installing the required libraries.
     
   - **Image files (flags and icons)**:
     - **`arrow.png`** – The arrow image used in the interface to indicate the translation direction.
     - **`de.png`, `en.png`, `es.png`, `flags.ico`, `flags.png`** – Image files of flags used to represent countries in the application. Each file corresponds to a specific language (e.g., `de.png` for German, `en.png` for English, `es.png` for Spanish).
     - **Location**: `Project/arrow.png`, `Project/de.png`, `Project/en.png`, `Project/es.png`, `Project/flags.ico`, `Project/flags.png`
     - **Description**: These are the images used in the graphical interface of the application. The application loads these images to display flags and icons.
   
## Requirements

Before running the application from the source code, ensure you have the following installed:

- **Python 3.7+** – Required to run the application.
- **Python Libraries**:
  - `pyaudio` – Required for microphone access.
  - `speech_recognition` – For speech-to-text recognition.
  - `translate` – For translating text.
  - `Pillow` – For image handling.