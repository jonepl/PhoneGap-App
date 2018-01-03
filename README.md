# PhoneGap Application Template

Tutorial by:  
URL: https://www.youtube.com/watch?v=je-VIKhUIgI

## Ubuntu 16.04 Installation:

Helpful Installation Links:
* https://www.youtube.com/watch?v=UhQH4hZ9GHw
* http://www.levibotelho.com/development/the-complete-guide-to-running-phonegap-on-ubuntu/
* https://cordova.apache.org/docs/en/4.0.0/guide/platforms/android/index.html

#### Update Advance Package Tool
```sh
$ sudo apt-get update
```

#### Install git
```sh
$ sudo apt-get install git
```

#### Install node
```sh
$ sudo apt-get install node
```

#### Installs PhoneGap
```sh
$ sudo npm install -g phonegap
```

#### Installs ant
```sh
$ sudo apt-get install ant
```

### Installation steps for Android emulate

## Usage:

Create a folder for your Phonegap project and build the phonegap project with

```sh
$ cordova create my_app_name com.example.hello my_app_name
$ cd my_app_name
$ cordova platform add android
$ cordova build
```

You may need to install gradle for cordova build to work. If so apply the following code

```sh
$ sudo add-apt-repository ppa:cwchien/gradle # Add Gradle repository
$ sudo apt-get update # Update if needed
$ sudo apt-get install gradle # Install gradle
```

Make sure to accept the license agreement with Android Studio SDK Manager
```sh
$ /home/Android/sdk/tools && ./skdmanager update
```
