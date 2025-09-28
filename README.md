# Salinaka | E-commerce react app
Simple ecommerce react js app with firebase [typescript].
![Firebase Deploy](https://github.com/jgudo/ecommerce-react/workflows/Firebase%20Deploy/badge.svg)

### [Live demo](https://salinaka-ecommerce.web.app/)

![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny1.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny2.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny3.png)
![Salinaka screenshot](https://raw.githubusercontent.com/jgudo/ecommerce-react/master/static/screeny7.png)

### 2. Create a new firebase project
Login to your google account and create a new firebase project [here](https://console.firebase.google.com/u/0/)

Create an `.env` file and add the following variables.

```
// SAMPLE CONFIG .env, you should put the actual config details found on your project settings

VITE_FIREBASE_API_KEY=AIzaKJgkjhSdfSgkjhdkKJdkjowf
VITE_FIREBASE_AUTH_DOMAIN=yourauthdomin.firebaseapp.com
VITE_FIREBASE_DB_URL=https://yourdburl.firebaseio.com
VITE_FIREBASE_PROJECT_ID=yourproject-id
VITE_FIREBASE_STORAGE_BUCKET=yourstoragebucket.appspot.com
VITE_FIREBASE_MSG_SENDER_ID=43597918523958
VITE_FIREBASE_APP_ID=234598789798798fg3-034

``` 

After setting up necessary configuration,
create a **Database** and choose **Cloud Firestore** and start in test mode

## How to add products or perform CRUD operations for Admin
1. Navigate to your site to `/signup`
2. Create an account for yourself
3. Go to your firestore collection `users collection` and edit the account you've just created. Change the role from `USER` to `ADMIN`.
4. Reload or sigin again to see the changes. 

**Firebase Admin to be integrated soon**

## Features

* Admin CRUD operations
* Firebase authentication
* Firebase auth provider authentication
* Account creation and edit

-

////////////////////////////////////////////Set up Edge + ReactJS + NodeJS + VSCode Debugger:////////////////////////////////////////////

Stable: Windows 10 x64 / Windows 11 x64

Setup:
-Install Microsoft Edge
-Install NodeJS: https://nodejs.org/en/download (x64 .msi LTS), check "Automatically install the necessary tools. ...", & next to everything.
-Install VSCode 
-Install these VSCode extensions:
	-Angular Extension Pack
	-Angular Essentials
	-Angular Language Services
	-Angular Snippets
	-Angular Files
	-Microsoft Edge Tools for VS Code
	-Prettier - Code formatter

Now open VSCode, Open Folder: /my-app, click on Terminal -> New Terminal & run the following commands in terminal:
-rm -rf node_modules
-rm -rf package-lock.json
-npm install -g npm
-npm install firebase --force
-npm install express --force
-npm install body-parser --force
-npm cache clean --force 
-npm install --save-dev @babel/preset-react @babel/preset-env --force
-npm i --force
-npm run-script build

Close VSCode terminal.

(Default) Open VSCode, Open Folder: /my-app, click on Terminal -> New Terminal & Run:
-cd my-app
-npm run-script dev

(Optional, Unit test) Open VSCode, Open Folder: /my-app, click on Terminal -> New Terminal & Run:
-cd my-app
-npm test

Now press F5 in VSCode. React will be debugged through the VSCode IDE.

