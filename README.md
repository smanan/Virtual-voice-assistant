# Virtual-voice-assistant
Jarvis is a voice commanding assistant service in Python 3.5+
It is a virtual assistant that uses voice recognition, language processing algorithms, and voice synthesis to listen to specific voice commands and return relevant information or perform specific functions as requested by the user.

Assistant Skills:

Opens a web page (e.g 'Jarvis open youtube')
Play music in Youtube (e.g 'Jarvis play mozart')
Tells the current time and/or date (e.g 'Jarvis tell me time or date')
Creates a reminder (e.g 'Jarvis create a 10 minutes reminder')
Opens linux applications (e.g 'Jarvis open bash/firefox')

Assistant Features:

Asynchronous command execution & speech recognition and interpretation
Supports two different user input modes (text or speech), user can write or speek in the mic.
Easy voice-command customization
Configurable assistant name (e.g 'Jarvis', 'Sofia', 'John' etc.) (change on run time supported)
Vocal or/and text response.

Installation required:

Python Speech Recognition module: pip install speechrecognition.
PyAudio: Use the following command for linux users sudo apt-get install python3-pyaudio. Windows users can install pyaudio by executing the following command in a terminal pip install pyaudio.
Python pyttsx3 module: pip install pyttsx3.
