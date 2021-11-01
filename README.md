# An-AI-Chatbot-in-Python-and-Flask
An AI Chatbot using Python and Flask REST API 

<h1>DISCLAIMER<h1>
  <p>
    If you want to test our code, please create a pull request from "ver1.1" branch as that is the last updated branch.
  </p>
<h3>Introduction</h3>
<p>
  This is Stella, an AI chatbot that runs on a web browser and capable of maintaining conversations with humans and also handle to-do lists.
  This project is for the HackMakers hackathon.
</p>

<h3>Technologies used</h3>
<p>
  numpy
  pickle
  json
  flask
  flask_ngrok
  nltk
  keras
</p>
<h3>Execution</h3>
<p>To run this Bot, First run the train.py file to train the model. This will generate a file named chatbot_model.h5. <br>
This is the model which will be used by the Flask REST API to easily give feedback.<br>
After running train.py, next run the app.py to initialize and start the bot.<br>
To add more terms and voccabulary to the bot, modify the intents.json file and add your personalized words and retrain the model again.</p>
<h3>Inspiration</h3>
<p>
  The code in this project is based on the code from Dennis Maina "https://github.com/Maina-Dennis" and edited by our team.
</p>
