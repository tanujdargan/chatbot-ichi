# chatbot-ichi
Ichi Chatbot 
### Creating the virtual environment
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
### to change the questions and their responses edit the intents.json file
### to train the model run
```
python train.py
```
### if you get torch module not found error then in your terminal execute
```
pip install torchvision 
```
### to chat with the bot in terminal run
```
pip install torchvision 
```
<h3 align="center"><img src="https://raw.githubusercontent.com/tanujdargan/chatbot-ichi/main/assets/terminal-training.png?token=GHSAT0AAAAAABSBHTQMOZYM2K44TSN6RS2KYWHONVQ" width="800px"></h3>
