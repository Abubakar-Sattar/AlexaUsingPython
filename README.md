# AlexaUsingPython
# AlexaUsingPython

Alexa Has Only 2 Tasks to perform:
1. Listen
  Alexa will pay attention to your order, as: "Hello Alexa, play music," "Hello Alexa, what's the time?"
  Alexa will pay attention to your order, get it, and afterward do some activity as indicated by your order.
2. Speaking
  At the point when Alexa will comprehend your order after paying attention to it, it will play out some activity on it.
Now let’s Implement Those Two Features:
  To implement these two features, we will require two Python modules:
    1.	SpeechRecognition
    2.	Python Text-To-Speech (pyttsx3)

1. SpeechRecognition
  This Python module performs speech recognition. It helps Alexa to listen what we are saying, catch that, and act accordingly.
  Use the command below to install SpeechRecognition module, from your terminal:
  Once installed and imported, we can use it in our task.

2. Python Text-To-Speech (pyttsx3)
  Text-to-Speech (TTS) module for Python works without internet or any delay.
  First you’ll have to install it:
 
  Our Alexa can finally speak with the help of this module.
  Starting the Fun Part
  We’ll create three different functions and each will be responsible for a single task.
  
  Step #1. Importing modules
    Let’s first import the modules:

 
  Step #2. Initializing of modules
    To use them lets initialize them and make their objects:
 
  Step #3. Create a method to convert text to speech - talk() method.
 
  Step #4. Create a method for Speech Recognition
 
  Step #5. Creating a method for response 
 
  Here, we need to understand a few things:
  
    i. Fetching required part:
      Suppose you want to hear a specific song or music. You’ll speak to Alexa this way:
      Play music_name. Using this command, we will just remove the word ‘play’ and get only
      the ‘music_name’ part:
 
      And, then we will store that music name (without ‘Play’) in variable song.
    ii) pywhatkit.playonyt():
      To use this module we have to install this module first and then import it. PyWhatKit
      has features to help us in automation. This module has a playonyt() method which we 
      will use to play the required songs directly on YouTube.
      First we’ll have to install it:
 
      And then import it.
    iii. datetime.datetime.now():
      To use datetime Module first we have to install it and then import it. This module 
      helps us to manipulate dates and times. The method now() returns the current time, datetime 
      module is built-in Python module.
      Import it this way:
 
    iv. wikipedia.summary():
      First we will need to install and import the Wikipedia module. This Python library makes it 
      easy to access data from Wikipedia. The summary() method gets the data from the summary 
      section of the Wikipedia.
      As we know it’s a third party module, then, we’ll have to install it first:
 
      And then import it in our code.
    v. pyjokes.get_joke():
      First of all we have to install and import pyjokes module in order to use it in our program. This 
      module will generate some funny jokes randomly which our Alexa will crack.
      This is also a third-party module so first, we will have to install pyjokes.
 
      And then import it.
 
  Step #6. Let’s run our Alexa
 
    Finally, we make the call to the run_alexa() method.
    Now we have created our own Alexa. Yay!
    Using some Python skills and with the help of some other modules you can add more features to Alexa.

The Whole Code
Now you can Enjoy your Alexa.
