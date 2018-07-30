# Prompt keyboard when focus on android device
This helps to emulate click in android app when focus on any input field programtically on device.This is very handy when we develop apps using Ionic 2/3.

# Installation

```cordova plugin add https://github.com/bhanu7755/cordova-android-focus```

# Usage

```declare var cordova;
   let element: HTMLElement = document.getElementById('searchTxt');
   cordova.plugins.Focus.focus(element);
   ```


