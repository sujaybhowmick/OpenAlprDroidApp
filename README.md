# Reference Android App demonstrating the use of [Automated License Plate Recognition library](http://www.openalpr.com/)

## How to build Android APK

### Steps to build your APK

First, change the path `sdk.dir` in `OpenAlprDroidApp/local.properties` file to your Android SDK location (e.g. `sdk.dir=/Applications/Android/sdk`)
Then,
```bash
git clone git@github.com:sujaybhowmick/OpenAlprDroidApp.git
cd OpenAlprDroidApp/
./gradlew clean
./gradlew assembleRelease
 ```

You will find app-release-unsigned.apk file in directory `OpenAlprDroidApp/app/build/outputs/apk` folder or

## Native JNI implementation of OpenAlpr API is another project called [openalpr-droidapp-native](https://github.com/sujaybhowmick/openalpr-droidapp-native)
