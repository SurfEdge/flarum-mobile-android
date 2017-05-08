# Make an Android app for your Flarum Forum
A WebView based Android application which will embed your flarum forum inside an application.

## How to setup
1) Clone the repo

2) Open the project in Android Studio - Wait till all the processes complete

3) In the MainActivity.java

`private static final String  url = "https://discuss.flarum.org/";`

Edit the url to yours.

4) Do any changes to the code - Change colors, Package names, Add splash screens

5) It is recommended to enter your own Firebase `google-services.json` file, which you'll be able to get from [Google Firebase](https://firebase.google.com/) itself, once you've logged in create a new project then go through the setup process (Make sure to use Android as your choice of Mobile project for this app example as well as the Package name you're using for the app at this time.)

6) Good to go :)

## How to enable Firebase Notifications

Download and upload **google-services.json** config file to **flarum-mobile-android/app** folder.

This file contains configuration details such as keys and identifiers, for the services you enabled.

### How to download google-services.json file?
1. Login to [Firebase Console](https://console.firebase.google.com).
2. Create a new project or select existing one.
3. Go to Settings >> Project Settings
4. From General Settings section download **google-services.json** file.

## Known Issues
* Facebook login inside app is not working
* ~~File Upload plugin not working~~ - Fixed with Advanced webview


## Screenshots

![Home](https://raw.githubusercontent.com/SurfEdge/flarum-mobile-android/master/screenshots/scr_home.png)
![Inside](https://raw.githubusercontent.com/SurfEdge/flarum-mobile-android/master/screenshots/scr_inside.png)

## Links

[Flarum Home page](http://flarum.org/)

[Flarum Community](https://discuss.flarum.org/)

[Advanced Web View project](https://github.com/delight-im/Android-AdvancedWebView)
