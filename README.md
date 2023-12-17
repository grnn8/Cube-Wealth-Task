# Cube-Wealth-Task
A simple full-stack web application with authentication and password recovery that allows users to manage a list of tasks.
# Tech Stack
* JavaScript
* React
* Express
* Tailwind
* MongoDB
* JWT Token

# Installation
Run the following command to clone the repository
```
git clone https://github.com/grnn8/Cube-Wealth-Task.git
```
Go to ```frontend``` and ```backend``` directory to install packages
```
cd frontend
npm install
```
```
cd backend
npm install
```
# Configuration
Create ```.env``` file inside ```backend``` directory and copy the following code

```
MONGO_URI=Your mongodb URI
GMAIL_USERNAME=your gmail address 
GMAIL_PASSWORD=password created inside 'App Password' section under google accounts setting
PORT=8000
JWT_SECRET=a random secret key eg. thisisasecretkey
```

The code can be run without providing a Gmail username and app password as well.
Only an email will not be sent for resetting the password.
# Run the App
Go to ```backend``` and ```frontend``` directory and start the server
```
cd backend
nodemon server
```
```
cd frontend
npm start
```
