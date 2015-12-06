# Potato Library

Easy to use Utility library for Android.

[![JitPack Status](https://img.shields.io/github/release/chipset95/Potato-Library.svg?label=JitPack)](https://jitpack.io/#chipset95/Potato-Library)
[![Travis-CI Build Status](https://travis-ci.org/chipset95/Potato-Library.svg?branch=master)](https://travis-ci.org/chipset95/Potato-Library)
[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-Potato%20Library-blue.svg?style=flat)](http://android-arsenal.com/details/1/2205)

## Usage

### Gradle
Add the following to your module's `build.gradle`

```groovy
repositories {
    maven {
	    url "https://jitpack.io"
	}
}

dependencies {
    compile 'com.github.chipset95:Potato-Library:0.1.4'
}
```

### Maven

```xml
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>

<dependency>
    <groupId>com.github.chipset95</groupId>
    <artifactId>Potato-Library</artifactId>
    <version>0.1.4</version>
</dependency>
```

Call the library using `Potato.potate()` and you will get following methods to use:

* Utils() - Utility methods to check Internet connection, methods on Bluetooth connection, methods for WiFi, get Battery level, Mobile Data tools etc.
* Notifications() - Create a notification with or without sound
* Preferences() - Store and Retrieve data to/from `SharedPreferences` easily
* Intents() - Create Intents for email, call, sms, browser, calendar, music player, camera with ease


### Permissions

The following permissions need to be added to AndroidManifest.xml file of your project

#### For checking internet connection

```xml
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
<uses-permission android:name="android.permission.INTERNET" />
```

#### For bluetooth tools

```xml
<uses-permission android:name="android.permission.BLUETOOTH" />
```

#### For WiFi tools
```xml
<uses-permission android:name="android.permission.ACCESS_WIFI_STATE" />
<uses-permission android:name="android.permission.CHANGE_WIFI_STATE" />
```

## Further Development

Plan to add Android Wear support.

## Contribution

Feel free to fork the repo, add new methods, send in pull requests and add new issues. There's no license right now.

Thanks to
- [Saketh Kaparthi](https://github.com/sakethkaparthi) for adding Wifi tools, GPS tool and Bluetooth disable method.
- [Anuraag Baishya](https://github.com/anuraag-baishya) for adding Mobile Data tools.
