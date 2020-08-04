# Awesomeproject

React Native hello world project from [official documentation](https://reactnative.dev/docs/getting-started.html)

In case of error :

```
ERROR:root:code for hash md5 was not found" when using ...
```

Executing:

```
npx react-native init AwesomeProject
```

Create a virtual environment with Python 3.8 or try [this](https://stackoverflow.com/questions/59269208/errorrootcode-for-hash-md5-was-not-found-when-using-any-hg-mercurial-command)

## Expo CLI

Expo CLI allows you to run your React Native app on a physical device without setting up a development environment

## React Native CLI

If you want to run your app on the iOS Simulator or an Android Virtual Device, please refer to the instructions for "React Native CLI Quickstart" to learn how to install Xcode or set up your Android development environment.

## Throubleshoting

Sometimes firewall can block connections to the Metro server. Try running it on different port (default is 8081):

`npx react-native run-android --port=8082`

> To test the Metro server just open http://localhost:8081

## Links

- [Setting up the development environment (Expo CLI and React Native CLI)](https://reactnative.dev/docs/environment-setup)
- [Getting started](https://reactnative.dev/docs/getting-started.html)
- [Running on device](https://reactnative.dev/docs/running-on-device)
