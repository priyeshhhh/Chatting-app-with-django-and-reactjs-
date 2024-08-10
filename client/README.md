
## Installation Process
To install this app please follow ths steps:

## Run Backend
1. Create a virtual environment virtualenv venv
2. And activate it source venv/bin/activate(for ubuntu) venv\Scripts\activate(for windows)
3. Then change the directory to server/ and install dependencies pip install -r requirements.txt
4. Migrate to database python manage.py migrate
5. Now run the server python manage.py runserver

## Run Frontend
1. Change the directory to clients/
2. Install dependencies npm install
3. Now start the server npm start


Now you'll be redirected to localhost:3000 Then open two browser window and do the signup with name, email, profile image and start chatting from two different window.



## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!



