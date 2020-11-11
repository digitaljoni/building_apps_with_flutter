

# Building Cross-Platform Mobile Apps with Flutter
An introduction to Dart and Flutter to start building your own mobile app.

## Pre-Workshop Setup

### 1. Setup

Click on the respective links below and follow the instructions listed under **Get the Flutter SDK**, **Update your path** and **Run flutter doctor** only.

Flutter set up instructions per OS:
* [Windows](https://flutter.dev/docs/get-started/install/windows#get-sdk)
* [macOS](https://flutter.dev/docs/get-started/install/macos#get-sdk)
* [Linux](https://flutter.dev/docs/get-started/install/linux#get-sdk)


You should be able to run ```flutter doctor``` on your machine after following the instructions. This will give you an overview if each tool needed to develop in Flutter. Use  ```flutter doctor -v``` for more detailed info.


### 2. Set up Visual Studio Code

For this workshop, we are going to use [Visual Studio Code](https://code.visualstudio.com/). Download it and install it for your respective OS.

Install the Flutter and Dart extensions:
* Start VS Code.
* Invoke View > Command Palette….
* Type “install”, and select Extensions: Install Extensions.
* Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required Dart plugin.

### 3. Android/iOS Development Dependencies

For this workshop, you would need to at least have an iOS device/simulator or android device/AVD. So make sure to follow either **Android Setup** or **iOS Setup** on the installation links above. Please note that iOS is only available on macOS.

Running ```flutter doctor``` should show the following output:

![Flutter doctor](flutter_doctor.png)

If you have set up everything correctly you should see a [✓] for Android Studio or Xcode. 

### 4. Git clone Starter Repo

We are going to build a simple app and this is going to be the starter repo.

```
https://github.com/digitaljoni/number_trivia
```
