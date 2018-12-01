[![](https://img.shields.io/badge/IBM%20Cloud-powered-blue.svg)](https://bluemix.net)
[![](https://img.shields.io/badge/platform-android-lightgrey.svg?style=flat)](https://developer.android.com/index.html)

# Create an Android application in Java which uses image recognition

> We have a similar pattern available for [iOS](https://github.com/IBM/visual-recognition-ios), as well!

In this code pattern, you will create an Android app that showcases computer vision by labeling what the device's camera sees. You will provision a Visual Recognition service where you can either leverage a demo model or train your own custom model.

When you have completed this code pattern, you will understand how to:

* Customize Watson Visual Recognition for your unique use case
* View the labels related to a picture and the estimated accuracy of that label

![](README_Images/architecture.png)

## Requirements

* An [IBM Cloud](http://bluemix.net) account
* [Android Studio](https://developer.android.com/studio/index.html)
* [Gradle](https://gradle.org/gradle-download/)

## Configuration

* Open the project in Android Studio and perform a Gradle Sync.
* Your unique Visual Recognition Api Key has been injected into your application so no further config is needed.

## Run

* You can now build and run the application from Android Studio!

![VisualRecognitionAndroid](README_Images/VisualRecognitionAndroid.png) ![VisualRecognitionAndroidClicked](README_Images/VisualRecognitionAndroidClicked.png)

The application allows you to perform Visual Recognition on user-selected images. You can take a photo from the application or select a photo from your gallery to start the Visual Recognition process. Tap the Tags to see the certainty score for the image.

> **Note:** If you have problems getting the camera to work properly, make sure you have accepted appropriate permissions and are using the most up to date version of Google Play Services. You will need to re-create an emulator to pick up updates after downloading.

## License

[Apache 2.0](LICENSE)
