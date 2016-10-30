# React Native Cheatsheet
Android Cheatsheets

## Create and run react native
```html
react-native init AwesomeProject
cd AwesomeProject
react-native run-android
```
## Detach existing adb connections
```html
adb kill-server
```
## Pull up the menu in emulator
```html
adb shell input keyevent 82
```
## Sending input to emulator
```html
adb shell input text ‘hello’
```
## Location of Filewatcher in case you need to edit it
```text
\AwesomeProject\node_modules\react-native\packager\react-packager\src\node-haste\FileWatcher
```
## Using CodePush
```text
code-push release-react MyApp android --description "Modified the header color"
```
## Mandatory option with -m
```text
code-push release-react MyApp android -m --description "Modified the header color"
```



