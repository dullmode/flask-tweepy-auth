# flask-tweepy-auth 
 
### Features
get personal access token and access token secret(consumer keys) using tweepy and flask
 
### Requirement

* tweepy==3.9.0
* Flask==1.1.2
* .env file

### Installation
install modules
```bash
pip install tweepy
pip install Flask
```
clone file
```bash
git clone https://github.com/dullmode/flask-tweepy-auth.git
```
set consumer keys to .env file
```bash
echo -e API_KEY=xxxxxxxx\\n\
    API_KEY_SECRET=xxxxxxxx > flask-tweepy-auth/service/.env
```

 
### Usage
```bash
cd flask-tweepy-auth
python service/main.py
```
 
### Note
you need to set `http://127.0.0.1:5000/callback` to callback url, which is in twitter developer portal 
