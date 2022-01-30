# ragini-python-notesapp

# Notes app

Note taking app developed in python Django with basic CRUD function for notes

## How to run it?

* Download the source code
  git clone ''
* Change the diectory to source code folder
  cd notesapp
* Create virtual environment(optional) and activate it
  virtualenv -p python djangoenv(for example) 
  djangoenv\Scripts\activate
* Apply migration
  python manage.py migrate
* Run the app
  python manage.py runserver
  Now, go to browser and open http://127.0.0.1:8000 
  This will display the the application where we can login, add notes, fetch all the notes, edit and delete the notes as well as search notes based on title and body message.

## To-Do

* Notes needs to contain Tags along with Title and Body
* Users can filter notes via Tags



