[![Build Status](https://travis-ci.org/asfrom30/TravisWithAndroid.svg?branch=master)](https://travis-ci.org/asfrom30/TravisWithAndroid)

# Environment Setting

## Process
* Install Android Studio
* Run Target Setting
    * Run > Run > Edit Configuration
        * Connection with emulator
        * Connection with device
            * 개발자 옵션 켜기
            * LG Android Phone
                * LG폰은 경우에 따라 usb driver 설치해 주어야 함. ADB 등록이 안됨
                * https://aroundck.tistory.com/1937
* Version Control
    * Login Git
    * git init
    * add git repo
* Install Plugins
    * markdown support(vendor intellij)
    
## Keyword
* ADB

# Project Setting
* Check Your SDK Setting
    * platform-tools
    * 
    * https://stackoverflow.com/questions/19911762/what-are-the-android-sdk-build-tools-platform-tools-and-tools-and-which-versio
* Tools > SDK Manager

## Android Version
## Travis
* Dev 환경과 Build 서버를 분리한다.
* ref : https://docs.travis-ci.com/user/languages/android/



## JUnit

# Tricky Part
### Android Build Tools VS SDK
````
Android SDK build tools are used to debug, build, run and test an Android application.

Android Build Tools can be used to develop and work from command line or IDE (i.e Eclipse or Android Studio).

Also used to connect Android devices and root them.(fastboot, adb and more..)

Always use the latest.(Recommended)
````

### Sdk tools vs SDK build tools vs SDK platform vs SDK platform tools
* https://developer.android.com/studio/releases/sdk-tools
* https://stackoverflow.com/questions/19911762/what-are-the-android-sdk-build-tools-platform-tools-and-tools-and-which-versio