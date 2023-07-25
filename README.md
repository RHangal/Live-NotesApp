# Live-NotesApp
A note taking app where user generated notes are stored and fetched from a Django RESTful API

Follow the steps below to start the application:

--> Clone the repository

--> Move into the directory where we have the project files :

cd Live-NotesApp

--> Create a virtual environment :

# If you are on Windows
virtualenv env
# If you are on Linux or Mac
python -m venv env
--> Activate the virtual environment :

# If you are on Windows
.\env\Scripts\activate
# If you are on Linux or Mac
source env/bin/activate

# Running the App

--> Move into the backend directory

cd Live-NotesApp/backend

--> Execute the following command:

python manage.py runserver:
⚠ Then, the backend server will be started at http://127.0.0.1:8000/

--> Open a new terminal and move into the frontend directory

cd Live-NotesApp/frontend

--> Execute the following commands:

npm install

npm run dev: 
⚠ Then, the development server will be started at http://localhost:3000

# Enjoy the App!


