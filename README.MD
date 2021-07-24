# RWAD - React Native Web App Dev

![N|Solid](https://i.imgur.com/g2YHoL2.png)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger) ![Build man](https://img.shields.io/node/v/npm) ![Build man](https://img.shields.io/badge/Size-6.86%20MB-informational) ![Build man](https://img.shields.io/amo/stars/dustman) ![Build man](https://img.shields.io/github/last-commit/ThirashaPraween/RWAD-React-Native-Web-App-Dev) ![Build man](https://img.shields.io/badge/Version-1.7%20--%2013605-orange) ![Build man](https://img.shields.io/npm/v/npm) ![Build man](https://img.shields.io/badge/Developer-ThirashaPW-blueviolet)

Generate an Android web app by using RWAD. Written in JavaScript, NodeJS, Java, Python and React Native.
RWAD Version - 1.7 build code - 13605

- Easy build
- No programming knowledge is needed.
- No need to install react native manually
- ✨100% Build speed✨

[Support to this project](https://www.buymeacoffee.com/thirashapraween)

## Features


- No coding knowledge needed for this operation
- Can generate apk or bundle
- Bundle is signed and it can upload to Playstore
- Compiler console script written in python
- React Native backend


RWAD applications/ libraries inbuild versions
| Application | Version |
| ------ | ------ |
| NodeJS | v10 - v15.8.0 |
| React | 16.11.0 |
| React Native | 0.62.2 |
| Java Dev Kit | 8 |
| Web View | 11.0.3 |
| Jest | 24.9.0 |


## Manual

All you need to have on your computer:

- [Node.js](https://nodejs.org/) - Better stable version!
- [ReactNative](https://reactnative.dev/) - React Native CLI (Not compatible with EXPO CLI)
- [JDK8](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html) - Java SE Development Kit 8.

Also check the updates on this repo to build better apps.

<br>
<p align="center">
  <a href="https://www.buymeacoffee.com/thirashapraween">
      <img src="https://camo.githubusercontent.com/2ef5c63105d22716d9d093d2c8b77cd7aa9d540b/68747470733a2f2f63646e2e6275796d6561636f666665652e636f6d2f627574746f6e732f76322f64656661756c742d79656c6c6f772e706e67" height="50px"/>
  </a>
   <a href="https://www.patreon.com/thirasha">
      <img src="https://le-cdn.website-editor.net/05ce6571223a491289ae62de7892c2dd/dms3rep/multi/opt/Patreon-Button-2880w.png" height="50px"/>
  </a>
</p>

## Installation

RWAD requires [Node.js](https://nodejs.org/) v10+ to run.
Clone RWAD repo or download latest release from [Releases](https://github.com/ThirashaPraween/RWAD-React-Native-Web-App-Dev/releases).

You don't need to manually run npm commands. RWAD will automatically run that commands.

```sh
cd RWAD-React-Native-Web-App-Dev
RWADScript.exe
```

For production environments...
open cmd or powershell

```sh
cd RWAD-React-Native-Web-App-Dev
RWADScript
```

## Instructions

Follow this instructions. This will help to use RWAD application.

#### Step 1
Has your computer installed React Native CLI (* Not Expo CLI) ?
 - Enter **y** if you have, press **n** don't have. 

#### Step 2
Application Name:
 - Enter app name. This app name is original app name that shows in the android mobile phones.
 - Example - My App
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

Package Name:
 - This package name looks like com.myapplication.testingapp.
 - You can enter any package name that will identify your app on android phones and google playstore and everywhere.
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

App Logo:
 - Enter app logo path like D:/pictures/logo.png
 - Only work **PNG** files
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

App Splash Image:
 - Enter app splash image path like D:/pictures/splash.png
 - Only work **PNG** files
 - This image will show when app open
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

APP URL:
 - Enter a url that you want to load.
 - Example - https://www.google.com
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

App Color:
 - Enter app color that will apply to spinner in the app.
 - Example - red, green, yellow, blue
 - Also you can use custom colors using color code. Example - #FF06AB
 - Get [color](https://htmlcolorcodes.com/color-picker/) codes
 - If you want to use default given by RWAD, you can skip step by pressing **Enter** key

Allow loading screen:
 - The default value is yes, Which means that the app shows a loading screen with a logo when you browsing the web
 - App starting splash screen shows without an obstacle, It cannot disable
 - If you want to use default (yes) given by RWAD, you can skip step by pressing **Enter** key

Here you can see a simple example of the different state
#### The loading screen shows whenever you load a page
**Actived Loading Screen (yes)** (Don't worry about web view)

![Alt Text](https://i.imgur.com/rzq2uVR.gif)

#### No screen shows whenever you load a page
**No Loading Screen (no)** (Don't worry about web view)

![Alt Text](https://i.imgur.com/3ZerALT.gif)


Fit to mobile screen:
 - The default value is no, Which means that the app use website mobile responsive features.
 - If value is yes then your app will shows full website without mobile resposive features and zooming
 - If you want to use default (no) given by RWAD, you can skip step by pressing **Enter** key

Here you can see a simple example of the different state of fitting
#### Screen fit used

![Alt Text](https://i.imgur.com/qcpdJF6.gif)

#### No screen fit used

![Alt Text](https://i.imgur.com/ZF9NDKZ.gif)

#### Step 3
bundle or apk [b/a]:
- If you want to build apk, enter **a** key. Or you want to build bundle for submit playstore, enter **b** key.

#### Step 4
Start building? [y/n]:
- Enter **y** to start build

**In this step if you want change somthing like app build version number, you can go and edit that inside lib folder. After editing you can press y to continue building.**

*Finally it will generate your app or bundle and put into output folder.*

Thank you for using RWAD!
