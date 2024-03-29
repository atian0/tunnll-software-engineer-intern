
# My Position - Show Device Position
This is an android app used to show the current position of a device using both GPS and network to get the location written in Kotlin language.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
* Android SDK. Can install the SDK via Android Studio or stand-alone tools. 
* IDE: Android Studio recommended which is the official IDE for Android, this project requires [Android Studio 3.0](https://developer.android.com/studio/preview/index.html) for minimum.

### Building the App
* First, install Kotlin plugin: navigate to `Android Studio -> Preferences -> Plugins -> Browse Repositories` and search for "Kotlin" then, click on "install". When the install is complete, you will need to restart Android Studio to apply the new plugin.

* Next, install Google Play services: navigate to `Android Studio -> Preferences -> Appearance & Behavior -> System Settings -> Android SDK`, select `SDK Tools` on the top right interface, find `Googe Play services` and choose it, click OK.

* Clone the repo:<br>
`git clone git@github.com:LucyTian/tunnll-software-engineer-intern.git`

* Open project with Android Studio:<br>
Open Android Studio and select `File -> Open...` or from the Android Launcher select Import project and navigate to the root directory of the project. Select MyMap directory and click "OK" to open the project.

* A Gradle sync should start, but you can force a sync and build the 'app' module as needed.

## Running the App
Connect an Android device to your development machine that allows USB debugging, the device should have Google Play services installed. 
* Select Run -> Run 'app' (or Debug 'app') from the menu bar
* Select the device you wish to run the app on and click 'OK'

## Using the App
Open the App on an Android device which is connected to worknet, allow the App to access the location data and it will show you with Google Map the location of your device with a red marker. Click the marker it will show "You are here" text. 
Click the small button on the top right would exit the program, but it stills runs in the background.

You can also down the package of the App [app-release.apk](https://github.com/LucyTian/tunnll-software-engineer-intern/tree/master/MyMap/app/release) to your device directly, install and open it to use.

## Reference
* [Google Map API tutorial](https://developers.google.com/maps/documentation/android-api/current-place-tutorial) 
* Square launch icon from [icons8](https://icons8.com/icon/342/map)
