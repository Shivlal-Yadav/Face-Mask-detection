# Face-Mask-detection
<div style="text-align:center">
This is an Android application made to detect if a person is wearing mask or not.
it is made using Microsoft Lobe application, which has been primarly used to train the model using the data.
Data has been taken from Kaggle website.
</div>
<br>
<br>
<br>
<div style="text-align:center"><img src="assets/header.png" /></div>
<br>

[Lobe](http://lobe.ai/) is a free, easy to use app that has everything you need to bring your machine learning ideas to life. The Android starter project takes the machine learning model created in Lobe, and adds it to an Android project. To get started using the starter project, follow the instructions below:

## Get Started

1. Clone, fork or download the project on your computer and install [Android Studio](https://developer.android.com/studio) to get started. Android Studio is the app that's used to run the starter project on your computer or device.

2. Open the `lobe_android` folder in this repository from inside Android Studio. Gradle will automatically start downloading the SDK's as needed.

3. Accept the required licenses by going to `SDK Manager` under the Tools menu. Click on `SDK Tools`. Then toggle `Show Package Details`. Last, install all the Android 30.0 versions under the `Android SDK Build Tools`.

4. To use your own model file, open your Lobe project, go to the Use tab, and click on the `TensorFlow Lite` model file. I recommend using the project setting `Optimize for Speed` for your model to run faster on mobile devices. You can change your project settings by going to File -> Project Settings. When exporting is done, drag both the `saved_model.tflite` and the `signature.json` files to `app/src/main/assets`.

5. Head back to Android Studio and run the app by clicking on the play button. You can also use your own Android device to run the app directly on your phone.

## Additional Information

I recommend Android Studio 4.1 or higher. This version of Android Studio will make sure your models run and load faster and more efficiently.
