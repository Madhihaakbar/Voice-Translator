In this application, the main objective is to develop a real-time voice translator that can translate user ’s voice input and generates output voice translation in the required language with text representation

CODE EXPLANATION:

 At first four modules playsound, googletrans, speech_recognition, gtts are imported by pip installation and os is also imported.

 A tuple is created for the available languages with its language code

 Def keyword function is created by declaring microphone as source for voice input and a command is printed to speak.  By using try and except, input command is declared using speech_recognition module.

 If the voice is recognized it asks for a language to translate. If the voice is not recognized a command is given for user to say it again until the voice is recognized.  The language we say is converted to lowercase and checked in the tuple using gtts and googletrans module. If the language is not recognized using loop statement again try except commands are printed.

 Now the user ’s voice input is saved as mp3 file to playsound and removed by os module to store the output voice and get output.

 This is represented also by text of the particular language translate
