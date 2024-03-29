# first_flutter_app

A new Flutter project.

- **Project Owner : Prabhu Sundarraj**
- **Author : [Prabhu Sundarraj](https://www.linkedin.com/in/prabhu-sundarraj/)**

## Getting Started

### What is Flutter?
**Flutter** is Google's UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.

This project is a starting point for our Flutter application, we will create a simple mobile Flutter app. If you're familiar with object-oriented code and basic programming concepts such as variables, loops, and conditionals then you can work on this project to enhance the mobile application in a way that you want to develop. 

You don't need previous experience with Dart, mobile, or web programming


### Scope or Feature of this Android Application:
A simple app that generates proposed names for a startup company. The user can select and unselect names, saving the best ones. The code lazily generates 10 names at a time. As the user scrolls, more names are generated. There is no limit to how far a user can scroll.


### Scope of the Learning:
- build the Flutter mobile app
- deploy the Flutter mobile app


### Steps to run this Project in your Machine:

#### 1.Set up your Flutter environment:
You need two pieces of software to complete this project [Flutter SDK](https://flutter.io/get-started/install/) and an [editor](https://flutter.io/get-started/editor/). 
You can use Android Studio, or any your preferred editor.

You can run the project by using any of the following devices:
•	A physical Android or iOS device connected to computer and set to developer mode
•	The Android Emulator (requires setup in Android Studio)
•	A browser (Chrome is required for debugging)


#### 2.Set up your Android device:
To prepare to run and test your Flutter app on an Android device, you need an Android device running Android 4.1 (API level 16) or higher.

•	Enable Developer options and USB debugging on your device. Detailed instructions are available in the [Android documentation](https://developer.android.com/studio/debug/dev-options).
•	Windows-only: Install the Google USB Driver.
•	Using a USB cable, plug your phone into your computer. If prompted on your device, authorize your computer to access your device.
•	In the terminal, run the flutter devices command to verify that Flutter recognizes your connected Android device. By default, Flutter uses the version of the Android SDK where your adb tool is based. If you want Flutter to use a different installation of the Android SDK, you must set the ANDROID_SDK_ROOT environment variable to that installation directory.


#### 3.Check the device connected using the following command: 
  Connect you android mobile to PC/laptop where you are doing this developement and run the below command
   **flutter devices**
  
  It will show all connected devices including your browsers and your connected mobile device should be shown under the android API in the list
  
  
#### 4.Now Run the following command to run our basic flutter app from the command line"
   **flutter run**
  You should see either Android, iOS, or web output, depending on your device. If you connected you android mobile device successfully then this command will automatically build an apk file, install and run your flutter app in your mobile device. 
  Here you go!
  You should see a list of word pairings no matter how far you scroll.  


#### References - https://flutter.dev/

#### A few other resources to get you started if this is your first Flutter project:

- [Default Project: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

#### For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
