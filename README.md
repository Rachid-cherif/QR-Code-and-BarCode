# QR-Code-and-BarCode
implement QR and BarCode scanner in android studio

I'm using Android Studio 4.1.1
With BuildGradle 4.1.1

# Intentlntegrator class:

It's a class wish helps ease integration with Barcode scanner via Intents
This is a simple way to invoke BarCode scanning and receive results
Without any need to integrate, modifiy or learn the project source code.

# implementation 
implementation 'com.journeyapps:zxing-android-embedded:3.4.0'

# AndroidManifest 

<uses-permission android:name="android.permission.CAMERA"/>

 <activity android:name=".Capture"
            android:screenOrientation="portrait"
            android:theme="@style/zxing_CaptureTheme"/>

