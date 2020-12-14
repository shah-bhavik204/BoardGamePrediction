# BoardGamePrediction

<h2>You can see the actual hosting implementation by clicking on <a href = "http://bsshah4216.pythonanywhere.com/">this</a></h2>
## To deploy this project on your own local server or on another hosting site, you need to perform the following steps:
Creating Flask App-
1. Create a Folder in your Local Directory using mkdir in command prompt
2. After creating your work directory, enter the directory through command prompt using cd <directory_name>
3. Once we are in the work directory, we first need to install python if you do not have it already.
4. After downloading python, we need to create a virtual environment in our work directory. We first install it by using "pip3 install  --user virtualenv"
5. We can do that using "virtualenv venv" command in command prompt
6. After running that command , we can activate the virtual environment using "venv\scripts\activate"
7. Once we are in our virtual environment, we must install flask. On windows you can do that by typing "pip3 install flask"
8. After flask is downloaded, we can open our python code. After entering all the code for our HTML and our Python backend, we now move on to deployment.
Deploying Flask App on pythonanywhere-
1.	Create a Git repo and upload the files.
2.	Open bash in “pythonanywhere” and clone the repo using command “git clone <repo>”.
3.	Set the virtual env by entering the path of the env in Web tab.
4.	Reload the site and you are good to go.
  
### Contents
1. saved model- "model.pickle"
2. saved vectorizer- "vectorizer.pickle"
3. template- "/templates/index.html"
4. flask app- "app.py"
5. css- "static/css/style.css"


