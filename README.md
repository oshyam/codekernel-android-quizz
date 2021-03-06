# codekernel-android-quizz

## Manually add Firebase

To add Firebase to your app you'll need a Firebase project and a Firebase configuration file for your app.

* Create a Firebase project in the Firebase console, if you don't already have one. If you already have an existing Google project associated with your mobile app, click Import Google Project. Otherwise, click Create New Project.
* Click Add Firebase to your Android app and follow the setup steps. If you're importing an existing Google project, this may happen automatically and you can just download the config file.
* When prompted, enter your app's package name. It's important to enter the package name your app is using; this can only be set when you add an app to your Firebase project.
* At the end, you'll download a google-services.json file. You can download this file again at any time.
* If you haven't done so already, copy this into your project's module folder, typically app/.

## Getting Debugging SHA1 easy way

- Open Android Studio
- Open your Project
- Click on Gradle (From Right Side Panel, you will see Gradle Bar)
- Click on Refresh (Click on Refresh from Gradle Bar, you will see List Gradle scripts of your Project)
- Click on Your Project (Your Project Name form List (root))
- Click on Tasks
- Click on Android
- Double Click on signingReport (You will get SHA1 and MD5 in Run Bar)
- Select app module from module selection dropdown to run or debug your application
