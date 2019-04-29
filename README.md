# App Namer

An example [Flutter](https://flutter.dev) project that generates randomised names for iOS and Android. 

## Requirements

Instructions here are with the understanding that the local development environment is Mac based.

* [Flutter](https://flutter.dev/docs/get-started/install) SDK
* [XCode](https://developer.apple.com/xcode/) for iOS development, you need a Mac with Xcode 9.0 or newer
* [Homebrew](https://brew.sh/) for Mac
* [Android Studio](https://developer.android.com/studio) for Android development

[![forthebadge](https://forthebadge.com/images/badges/gluten-free.svg)](https://forthebadge.com)

## Getting Started

MacOS installation details can be found [here](https://flutter.dev/docs/get-started/install/macos).

Key additional tools to download to deploy Flutter apps to iOS devices as mentioned in the Flutter install Docs:

```sh
$ brew install --HEAD usbmuxd
$ brew link usbmuxd
$ brew install --HEAD libimobiledevice
$ brew install ideviceinstaller ios-deploy cocoapods
$ pod setup
```

## Configure

Download the app to your local development folder.

	$ git clone https://github.com/leesheppard/app_namer.git
	$ cd app_namer

### Manually install and trust an enterprise app - iOS

The first time you use an attached physical device for iOS development, you will need to trust both your Mac and the Development Certificate on that device. Select `Trust` in the dialog prompt when first connecting the iOS device to your Mac.

Then, go to the `Settings` app on the iOS device, select **General > Device Management** and trust your **Certificate**.

For more detailed instructions follow these prior to testing/running: [Install custom enterprise apps on iOS](https://support.apple.com/en-au/HT204460).

## Run the App

Start the app by running:

    $ flutter run

## Help

For help with Flutter, view [online documentation](https://flutter.io/docs), which offers tutorials, 
samples, guidance on mobile development, and a full API reference.
