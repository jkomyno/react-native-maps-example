# react-native-maps-example
Since the official react native example provided by React Native [didn't work on Android](https://github.com/airbnb/react-native-maps/issues/998), I fixed it and published it here.

# Installation

First, clone the repository and install its dependencies:

```
git clone https://github.com/jkomyno/react-native-maps-example
cd react-native-maps-example
npm i
```
### Note:
The native dependencies should already be linked, if not then just follow the instructions in the official AirBnB's [readme](https://github.com/airbnb/react-native-maps/edit/master/docs/installation.md).

# Api key

Check out the "meta-data" tag in android/app/src/main/AndroidManifest.xml and add your API key there.

# Run (untested on iOS)

```
react-native run-android
```
