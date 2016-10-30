# cheatsheet
Android Cheatsheets

Create and run react native
```html
react-native init AwesomeProject
cd AwesomeProject
react-native run-android
```
Detach existing adb connections
```html
adb kill-server
```
Pull up the menu in emulator
```html
adb shell input keyevent 82
```
Sending input to emulator
```html
adb shell input text ‘hello’
```
