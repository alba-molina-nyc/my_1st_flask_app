# Taskly

## My first Flask app

This repository creates a simple CRUD app using Flask

the purpose is to get comfortable using Flask for applications

This repo has been updated to work with Python v3.8 and up.

How To Run
Install virtualenv:
$ pip install virtualenv
 Save
Open a terminal in the project root directory and run:
$ virtualenv env
 Save
Then run the command:
$ .\env\Scripts\activate
 Save
Then install the dependencies:
$ (env) pip install -r requirements.txt
 Save
Finally start the web server:
$ (env) python app.py
 Save
This server will start on port 5000 by default. You can change this in app.py by changing the following line to this:

if __name__ == "__main__":
    app.run(debug=True, port=<desired port>)
 Save

