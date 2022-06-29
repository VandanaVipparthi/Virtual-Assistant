# Virtual-Assistant
# Build Your Own ALEXA
It is possible to build your own virtual assistant using python all we need to know is about libraries in python which will make our work quite simple.
# Algorithm
	1. Libraries that we are supposed to import

		* speech_recognition as sr
		* pyttsx3
		* pywhatkit
		* datetime
		* wikipedia
		* pyjokes

	2.Creating a recognizer who will be able to recognize your voice

	3.You can choose which voice you want for eg. i've used engine.setProperty('voice', voices[1].id) where voices[1].id gives female voice

	4.Create a function named Talk() which will speak or repond according to your request

	5.Create another function command() which takes all your commands and gives it to the engine, sometimes we will be facing issues with microphone so its better to keep a try except block

	6.Create another function name it Alexa() here you will take care of all the requests and responses

	7.Now you are good to proceed! Ask your virtual assistant to play a song.
