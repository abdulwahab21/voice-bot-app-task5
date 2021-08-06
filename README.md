# voice-bot-app-task5
This task for voice bot application in Flutter. 
<br>
<b>Packages:</b> 
<br>
I have used four packages which are Speech To Text (STT), Text To Speech (TTS), IBM Watson Assistant Chatbot and Rive. 
<br>
1- STT: This package convert speech to text.
<br>
2- TTS: This package convert text to speech.
<br>
3- IBM Watson Assistant Chatbot: This package gets the text from STT. Then, sending it to IBM Watson Assistant Chatbot. After that, getting the result from chatbot as text. 
<br>
4- Rive: This package for animation of robot. 
<br>
<b>Files:</b> 
<br>
There are three files as dart extension in the lib folder which are animation, Chatbot and main. 
<br>
1- animation: This file to determine the duration of animation by adding a list of answers from chatbot and a list of duration for every answer. Then, it is return the duration as integer.
<br>
2- Chatbot: This file is containing the function to get the answer from chatbot as text. 
<br>
3- main: This file it is containing the run application. 
<br>
Also, there is file in asset folder that contains face_robot_v1.riv as Rive extension to do the animation. 
<br>
<b>Chatbot dialog:</b> 
<br>
The dialog of chatbot has 8 intents as follow: 
<br>
1- Welcome: it shows welcome when someone open it.
<br>
2- Greeting: when a person send greeting like hello, good morning, etc.
<br>
3- Services: it provides services of chatbot when a person writes “what are services?” or similar question. Also, it has 3 entities. 
<br>
4- Building website: it provides how I have built the website when person writes “can you tell me how you build the website?”.
<br>
5- Time of tournament: it provides the time of tournament when a person writes “When will the tournament begin?”.
<br>
6- Cost of tournament: it provides the cost of tournament when a person writes “Is there any fee for the tournament?”. 
<br>
7- Thanks, it provides the pleasure when a person writes “Thanks”, “Thank you”, etc. 
<br>
8- Anything else: if the chatbot cannot recognize what a person writes.
<br>
9- feedback: it gets the feedback from person when he writes “good” or “bad”.
<br>
10- evaluation: It provide the evaluation for place when the person writes “I would like to evaluate this place.” or “evaluation” .
<br>
11- The robot: When the person writes “are you a bot” or “Are you human”. 
<br>
12- jokes: when the person writes “tell me a joke.”. 
<br>
13- technique: it provides a basic technique to win against an opponent in the fighting balloon robots when the person write “Give me a technique”.   
<br>
<b>Application:</b>
<br>
The application is about a voice bot that run the function “_listen()” by a duration of 5 seconds without a button.
<br>
Note: I have built the application in android studio, so I recommend running in android studio. 
<br>
Note: to run the application, you should open folder chatbot and run the application.
