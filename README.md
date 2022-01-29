# AngularChat

## firebase setup
     Open firebase account https://console.firebase.google.com/
     1. creat project
     2. add Web app
     3. update your firebaseconfig into src/environments/environment.ts
         const firebaseConfig = {
            apiKey: "you key",
            authDomain: "angularchat-e2ffa.firebaseapp.com",
            databaseURL: "https://angularchat-e2ffa-default-rtdb.asia-southeast1.firebasedatabase.app",
            projectId: "angularchat-e2ffa",
            storageBucket: "angularchat-e2ffa.appspot.com",
            messagingSenderId: "161504863541",
            appId: "your id"
          };
     4. Authentication - enable Email/Password Sign-in method
     5. Realtime Database - create realtime database

     refer: https://www.securecoding.com/blog/angular-firebase-authentication-integration/

## download this source code and compile
    npm install

## angular build
     ng build --prod --aot

## firebase hosting
      $ npm install -g firebase-tools
      $ firebase logout
      $ firebase login
      $ firebase init
          Select Realtime database & Hosting
          what do you want as your public directory? dist/AngularChat
          configure as a single-page app? y

      $ firebase deploy

## Firebase deploy detail

    Project Console: https://console.firebase.google.com/project/angularchat-e2ffa/overview
    Hosting URL: https://angularchat-e2ffa.web.app

## Reference
    How to setup firebase realtime database
    https://www.positronx.io/deploy-angular-app-to-production-with-firebase-hosting/
    https://github.com/errejotaaa/chat-app
