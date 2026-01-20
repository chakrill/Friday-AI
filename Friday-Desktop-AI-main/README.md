Friday Desktop AI
A Python-based desktop voice assistant capable of performing various tasks like playing music, taking screenshots, telling the time, and searching the web.

Features
Voice Interaction: Speaks and listens to commands.
Web Automation: Opens YouTube, Google, and searches Wikipedia.
System Utilities:
Takes screenshots.
Reports CPU and battery usage.
Opens system applications (Notepad, Calculator, etc.).
Media Playback: Plays music from your local library or YouTube.
Information: Tells time, date, weather, and news headlines.
Fun: Tells jokes and can change its voice.
Installation
Clone the repository:

git clone https://github.com/yourusername/Friday-Desktop-AI.git
cd Friday-Desktop-AI
Install dependencies:

pip install -r requirements.txt
(Note: You may need to create a requirements.txt file listing libraries like pyttsx3, speechRecognition, wikipedia, pywhatkit, selenium, etc.)

Prerequisites:

Python 3.x
Active Internet connection for speech recognition and web features.
Microphone.
Usage
Run the main script:

python Friday.py
Click the "WISH ME" button to start, or "PLAY" to begin listening for commands.

Code Structure
Friday.py
: Main application logic and GUI.
Libraries.py
: Import statements for all required libraries.
News.py
, 
weather.py
, 
diction.py
: Helper modules for specific features.
Assistant.gif
: Animation for the GUI.
Contributing
Feel free to open issues or submit pull requests to improve Friday!
