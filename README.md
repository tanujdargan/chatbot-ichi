# chatbot-ichi
Ichi Chatbot ### Creating the virtual environment
```
virtualenv --python C:\Users\tanuj\AppData\Local\Programs\Python\Python310\python.exe venv
```
### activate the virtual env
```
.\venv\Scripts\activate
```
### Installing packages
``` 
pip install Flask torch torchvision nltk
```
### Installing required package for NLTK
```
python
import nltk
nltk.download('punkt')
```
### To change the questions and their responses edit the intents.json file
### To train the model run
```
python train.py
```
### If you get torch module not found error then in your terminal execute
```
pip install torchvision 
```
### To chat with the bot in terminal run
```
python chat.py
```
### Finally to use the bot with it's interface
```
Command 1: cd C:/Users/tanuj/Desktop/Internship stuff/chatbot
Command 2: .\venv\Scripts\activate
Command 3: "c:/Users/tanuj/Desktop/Internship stuff/chatbot/venv/Scripts/python.exe" "c:/Users/tanuj/Desktop/Internship stuff/chatbot/app.py"
```

<h3 align="center"><img src="https://raw.githubusercontent.com/tanujdargan/chatbot-ichi/main/assets/terminal-training.png?token=GHSAT0AAAAAABSBHTQNLIASVXQZF72JGE6OYWIA5QQ" width="800px"></h3>
