# Semester Project

This is the project files for our mid semester hackathon. Our project was to build a fake news detection system. 
In the football commmunity, during transfer season there are numerous reports of players transfer status. From a player joining a new club to a player's contract being terminated. Unfortunately, majority of the news are wide off the mark but there's no way to tell. So the A team decided to build a model that helps users authenticate fake transfer news.

Our project consists of:
1. Model and Dataset which is located in the Final_Semester_Project_Mining
2. Website. A UI for the user to authenticate news. 


# To run this project. 

```bash
# install packages
$ pip install -r requirements.txt
# start the server
$ uvicorn app.main:app --reload --port 8080
```

Visit [http://127.0.0.1:8080/](http://127.0.0.1:8080/).


### Requirements

```sh
requests==2.27.1
fastapi==0.72.0
uvicorn==0.17.0
python-dotenv==0.19.2
aiofiles==0.8.0
python-multipart==0.0.5
jinja2==3.0.3
Markdown==3.3.6
pytest==6.2.5
nltk (punkt, wordnet, omw-1.4, stopwords)
sklearn
pandas
tweepy
matplotlib
```

=======
