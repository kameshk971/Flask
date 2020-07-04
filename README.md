Steps to create new environment:

1. Open anaconda prompt
2. type : conda create -n myenv python=3.7

Steps to create db :

1. open anaconda cmd 
2. type python and press enter
3. type: from app import db and press enter
app is flash app name and db is db name in the code
4. db.create_all() ---> this will create the database
5. exit()

To create requirements.txt file :

1. Activate your environment in anaconda cmd prompt by using : activate envname
2. create Procfile.txt with --> web: gunicorn app:app where first app is flask file name and second app is flask app name
3. pip freeze > requirements.txt

To Check Logs while deploying:
1. download heroku cli
2. open command prompt and type heroku login
3. press any key and then webpage will open there you have to login 
4. then cmd will recognize ur account
5. Type : heroku logs --app your_app_name