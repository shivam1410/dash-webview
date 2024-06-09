## Install Ionic and cordova globally
```
npm install -g @ionic/cli
npm install -g cordova
```

## Create app
```
ionic start myApp blank
cd myApp
```

## Install Dependency
```
npm i cordova-plugin-ionic-webview
npm i @ionic-native/ionic-webview
npm install @capacitor/android
```

## Other Prerequisites
```
// https://developer.android.com/studio?gad_source=1&gclid=Cj0KCQjwpZWzBhC0ARIsACvjWROyIly_6GpeZNWnrihCESXM0mdqRKrokGtQC0bULQ-6XDila2D-UJgaAiVMEALw_wcB&gclsrc=aw.ds
// Install android sdk

// https://www.oracle.com/java/technologies/downloads/#jdk22-mac
// Install Java runtime
```

## Run the code
### Run in web
```
npm start
```
### Run in Android
```
ng build && npx cap copy android
npx cap run android
```
