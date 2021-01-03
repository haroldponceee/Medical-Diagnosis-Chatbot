# Project Medica
A web app chatbot based on Python Flask, Chatterbot, SQLAlchemy, and Hexo design for initial medical diagnosis of common diseases.

Make sure you have installed git, nodejs, hexo, and python 3.x

### Local setup:
```sh
pip3 install chatterbot
pip3 install sqlalchemy
sudo apt install nodejs
sudo apt install npm
npm install -g hexo-cli
git clone https://github.com/notnoobdude/Project_Medica.git
cd Project_Medica
pip3 install -r requirements.txt
npm install hexo-renderer-pug --save
```

### To run:
There are two separate runs that should happen here on the command line.
First:
```sh
hexo clean
hexo server
```
Second:
```sh
python3 train.py
python3 run.py
```
