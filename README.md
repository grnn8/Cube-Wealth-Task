# Cube-Wealth-Task
A simple full-stack web application with authentication and password reset that allows users to manage a list of tasks.
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
# Screenshots
## Main and Login Page
![Alt Text](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/Main%20Page%20and%20Login.PNG)

## Register Page
![Alt Text]([image_url](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/Register%20page.PNG))

## Forgot Password
![Alt Text](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/Forgot%20password%20page.PNG)

## Reset Password Mail
![Alt Text](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/Reset%20Password%20mail.PNG)

## Reset Password 
![Alt Text](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/Reset%20password%20page.PNG)

## Todo Page
![Alt Text](https://github.com/grnn8/Cube-Wealth-Task/blob/main/Screenshots/ToDo%20page.PNG)


