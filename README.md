
# Project Teeket

# HerTechTrail Team 6 Capstone Project cd

# Getting Started with Create React App

# Project- Teeket APP

# HerTechTrail Team 6 Capstone Project 
Team members: Oreoluwa Ruth Ajayi and Eghe Cynthia Igbinoba

# Teeket App
This is a simple web app that allows users to create, book and manage tickets for various events. It uses React.js for the frontend, Tailwind CSS for the styling, and Firebase for the backend and authentication.

# Features
Users can sign up and log in with their email and password or Google account.
Users can create, edit, delete, and view tickets for different events.
Users can filter tickets by status, category, date, or keyword.

# Installation
To run this app locally, you need to have Node.js and npm installed on your machine. Also run installation for tailwind css You also need to create a Firebase project and enable Firestore, Storage, and Authentication services.

Clone this repository: git clone https://github.com/<your-username>/ticket-app.git
Install the dependencies: npm install
Create a .env file in the root directory and add your Firebase configuration variables. You can find them in the Firebase console under Project settings > General > Your apps > Firebase SDK snippet > Config. For example:
REACT_APP_FIREBASE_API_KEY=AIzaSyA...
REACT_APP_FIREBASE_AUTH_DOMAIN=ticket-app.firebaseapp.com
REACT_APP_FIREBASE_PROJECT_ID=ticket-app
REACT_APP_FIREBASE_STORAGE_BUCKET=ticket-app.appspot.com
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=123456789
REACT_APP_FIREBASE_APP_ID=1:123456789:web:abcdefg

Start the development server: npm start
Open http://localhost:3000 in your browser.

# Deployment
To deploy this app to Firebase Hosting, you need to have the Firebase CLI installed and logged in.
Build the production bundle: npm run build
Initialize Firebase Hosting: firebase init hosting
Choose your Firebase project and select build as the public directory.
Deploy the app: firebase deploy

# Hosting
Hosting was done using netlify.
netlify commands : npm install netlify-cli -g
netlify deploy

# Resources
https://techvblogs.com/blog/how-to-use-tailwind-css-with-a-react-app
https://v2.tailwindcss.com/docs
https://console.firebase.google.com/u/0/project/sample-f9c58/overview
https://firebase.google.com/docs/web/setup
https://www.figma.com/file/yCssXNupv9qyds1bOEFqkL/Cohort-6---Capstone-Project-(Design)?type=design&node-id=832-5807&t=8orGkOIa9x71zI1W-0
