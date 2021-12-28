# react-native

## Create a new app
```shell
npx react-native init ExampleApp
```

## Running
Check https://reactnative.dev/docs/environment-setup for details.

### Execute Metro
```shell
npx react-native start
```

### Execute in iOS
Install Xcode
```shell
npx react-native run-ios
```

### Execute in Android
Install Android Studio

Include in `$HOME/.bash_profile`
```shell
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools
```

```shell
npx react-native run-android
```


## Flow in IntelliJ
https://www.jetbrains.com/help/idea/using-the-flow-type-checker.html#ws_js_install_flow
