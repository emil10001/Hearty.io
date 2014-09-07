# Hearty.io

<img src="https://raw.githubusercontent.com/emil10001/Hearty.io/master/raw_assets/icon/color_icon.png" height="400px" width="400px" >

### WARNING

This is a workspace for a set of projects that are to become an open source fitness tracking service. Not very far along yet. Don't expect much here.

## Pre-requisites

* Android SDK installed and up to date
* Android 4.4W installed
* Google Glass APIs installed
* Latest Android Build-tools installed
* Android Studio installed and up to date

## Building

1. Check out the entire project from GitHub:

    git clone --recursive https://github.com/emil10001/Hearty.io.git

2. Import into Android Studio as a project.

3. Start hacking!

### Android Studio

Right now, only Android Studio is supported as an environment. This project requires a newer version of
the gradle plugin than IntelliJ, and Eclipse does not do Gradle at all.

### Git Submodules

Here's some documentation on [git submodules](http://git-scm.com/book/en/Git-Tools-Submodules).

To clone everything at once, do the following:

    git clone --recursive https://github.com/emil10001/Hearty.io.git

## Targets

Below are the list of apps that this project can build.

### HeartyGlass

Currently pairs and displays heart rate data from a BLE HRM (Bluetooth 4.0/Low Energy Heart Rate Monitor).

### HeartyAndroid

Currently does basic activity tracking, posting and updating a notification with that current activity.
If the activity is running or bicycling, tapping the notification will launch Strava. Works with HeartyWear.

### HeartyWear

Currently does step counting, and syncs it back to the HeartyAndroid app.