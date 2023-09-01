# ML1
first_ml_project

# Requirement
```
1. Github Account: https://github.com
2. Heroku Account: https://dashboard.heroku.com/login
3. VS Code IDE: https://code.visualstudio.com/download
4. GIT cli: https://git-scm.com/downloads
5. conda installed
```

Create a conda virtual environment
```conda create -p venv python==3.11 -y```
```conda activate venv/ or conda activate venv```


Make a new file requirements.txt and write Flask in it

Install requirements
```pip install -r requirements.txt```

Make a new file app.py and write a simple flask app and run it using python3 app.py, check it and come back to terminal and stop it by ctrl+c
```from flask import Flask
app=Flask(__name__)
@app.route("/",methods=['GET','POST'])
def index():
    return "1st ML project"
if __name__=="__main__":
    app.run(debug=True)```

