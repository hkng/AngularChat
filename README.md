# AngularChat

## firebase setup
     Open firebase account https://console.firebase.google.com/
     1. Authentication - enable Email/Password Sign-in method
     2. Realtime Database - create realtime database

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
