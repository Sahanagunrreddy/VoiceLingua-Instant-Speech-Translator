# VoiceLingua-Instant-Speech-Translator

LinguaSync: Real-Time Voice Translator
LinguaSync is a cutting-edge Real-Time Voice Translator designed to provide seamless and natural cross-lingual communication. This machine learning-powered desktop application uses advanced deep neural networks to translate voice in real-time, while maintaining the speaker's tone and emotions. It supports multiple platforms including Windows, Linux, and MacOS.

The app allows users to speak in one language and instantly get translations in another. It's designed for both individual and multi-user conversations, offering a smooth translation experience in real-time.

Features
Real-Time Voice Translation: Instant translation with minimal delay.

Emotion and Tone Preservation: Translations retain the speaker's emotions and tone.

Cross-Platform: Works on Windows, Linux, and MacOS.

User-Friendly Interface: Simple to use for users of all experience levels.

Multi-Language Support: Translate between a wide variety of languages.

Conversation Mode: Easily translate multi-person conversations.

Dependencies
Python <= 3.11

gTTS (Google Text-to-Speech)

PyAudio

playsound==1.2.2

deep-translator

SpeechRecognition

google-transliteration-api

cx-Freeze

Getting Started
Follow these steps to set up the project on your local machine.

Clone the repository and create a virtual environment (recommended):

bash
Copy
Edit
# Clone the repository
git clone https://github.com/SamirPaulb/real-time-voice-translator.git
cd real-time-voice-translator

# Create virtualenv
python -m venv env

# Activate virtualenv
# Linux/MacOS
source env/bin/activate

# Windows
env\Scripts\activate
Install the required dependencies:

bash
Copy
Edit
pip install --upgrade wheel
pip install -r requirements.txt
Run the application:

bash
Copy
Edit
python main.py
This will start the voice translator and you can begin speaking to translate instantly.

Program Flow


Installation for Windows/Linux/Mac
Download the latest installer for your platform from the release page:
Download Latest Release

If you wish to build the installer yourself, the project uses cx_Freeze to package the app. You can modify build settings through the setup.py file.

To build the installer:

Windows:

bash
Copy
Edit
python setup.py bdist_msi
Linux:

bash
Copy
Edit
python setup.py bdist_rpm
Mac:

bash
Copy
Edit
python setup.py bdist_mac
GUI Preview
Here's a preview of the user interface of LinguaSync:

Contributing
Feel free to fork the repository and submit pull requests. Contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Thanks to cx_Freeze for helping package the app as an executable.

Special thanks to the SpeechRecognition and deep-translator libraries for their seamless integration into the translation process.
