# FinanceReactNative

iOS's Stocks App clone written in [React Native](https://github.com/facebook/react-native) for demo purpose. Data is pulled from Yahoo Finance.

![Preview](https://raw.github.com/7kfpun/FinanceReactNative/master/preview.gif)

## Plugins used

* [react-native-navbar](https://github.com/Kureev/react-native-navbar): Simple customizable navbar component for react-native.
* [react-native-refreshable-listview](https://github.com/jsdf/react-native-refreshable-listview): A pull-to-refresh ListView which shows a loading spinner while your data reloads.
* [react-native-simple-store](https://github.com/jasonmerino/react-native-simple-store): A minimalistic wrapper around React Native's AsyncStorage.
* [react-native-viewpager](https://github.com/race604/react-native-viewpager) - ViewPager component for React Native.
* [reflux](https://github.com/reflux/refluxjs): A simple library for uni-directional dataflow application architecture with React extensions inspired by Flux.

## Components used

* **Image** - A React component for displaying different types of images, including network images, static resources, temporary local images, and images from local disk, such as the camera roll.
* **ListView** - A core component designed for efficient display of vertically scrolling lists of changing data.
* **Navigator** - Use Navigator to transition between different scenes in your app.
* **Platform**
* **StatusBarIOS**
* **StyleSheet** - A StyleSheet is an abstraction similar to CSS StyleSheets.
* **Text** - A React component for displaying text which supports nesting, styling, and touch handling.
* **TextInput** - A foundational component for inputting text into the app via a keyboard.
* **TouchableHighlight** - A wrapper for making views respond properly to touches.
* **TouchableOpacity** - A wrapper for making views respond properly to touches.
* **View** - A container that supports layout with flexbox, style, some touch handling, and accessibility controls, and is designed to be nested inside other views and to have 0 to many children of any type.
* **WebView**

## Known Issues

* WebView is not working for Android App

## Running

#### Clone & install

* Clone this repo `git clone git@github.com:7kfpun/FinanceReactNative.git`
* `cd FinanceReactNative`
* run `npm install`

#### iOS

* Open `Finance.xcodeproj` in `XCode`
* Press `cmd+r` to build it

#### Android

* Run `react-native run-android`

## License

Released under the [MIT License](http://opensource.org/licenses/MIT).
