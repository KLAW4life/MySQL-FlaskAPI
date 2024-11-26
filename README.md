# MySQL-FlaskAPI
This is a Flask API that reads a .csv file and inserts the data into a database.

How to run this program:

First we need to create the databse and insert the data before creating our api

In the command line, start the script_create_db.py program

NB: '$' represents the start of the command and not to be entered.

```bash
python script_create_db.py
```

OR

"If you have python 3 installed on you machine"

```bash
python3 script_create_db.py
```

Once the databse can been sucessfully created, it is now time to run our app.py program to run our flask api.
This is done by first creating a virtual environment, installing the required dependencies and then running the program.

In the command line, run the following commands:

```bash
python -m venv venv (you may need to use python3 instead if you are using python3)
```
If you have a Mac/Linus System you run this command to create your virtual environment
```bash
source venv/bin/activate 
```

If you have a Windows System you run this command to create your virtual environment
```bash
.\venv\Scripts\activate
```
Install all the requirements for the project to run
```bash
pip install -r requirements.txt
```
To run the flask Application
```bash
flask --app app --debug run
```