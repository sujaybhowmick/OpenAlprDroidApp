# Reference Android App demonstrating the use of [Automated License Plate Recognition library](http://www.openalpr.com/)

## How to build App APK

###Steps to build

1. Change the path sdk.dir in OpenAlprDroidApp/local.properties file to your Android SDK location (e.g. sdk.dir=/Applications/Android/sdk)
2. Sujays-MacBook-Pro:tmp sujay$ git clone git@github.com:sujaybhowmick/OpenAlprDroidApp.git
3. Sujays-MacBook-Pro:tmp sujay$ cd OpenAlprDroidApp/
4. Sujays-MacBook-Pro:OpenAlprDroidApp sujay$ ./gradlew clean
5. Sujays-MacBook-Pro:OpenAlprDroidApp sujay$ ./gradlew assembleRelease

You will find app-release-unsigned.apk file in OpenAlprDroidApp/app/build/outputs/apk folder

## Native JNI implementation of OpenAlpr API is another project called [openalpr-droidapp-native](https://github.com/sujaybhowmick/openalpr-droidapp-native)

License
--------
[Affero GPLv3](http://www.gnu.org/licenses/agpl-3.0.html)

If you need any help contact me @ sujaybhowmick at gmail dot com