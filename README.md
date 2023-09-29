System Requirements

PC
  All Windows 11 devices
  Windows 10 devices with Windows version: 10.0.16299.0 (aka 1709, aka Redstone 3
  ARM64 or x64 processor; Quad-core or better recommended. ARM 32 processors are not supported.
  Minimum of 4 GB of RAM. Many factors impact resources used; we recommend 16 GB RAM for typical professional solutions.
  Hard disk space: Minimum of 850 MB up to 210 GB of available space, depending on features installed; typical installations require 20-50 GB of free space. We recommend installing Windows and Visual Studio on a solid-state drive (SSD) to increase performance.
  Video card that supports a minimum display resolution of WXGA (1366 by 768); Visual Studio will work best at a resolution of 1920 by 1080 or higher.


Installation instructions

  Download Node js Latest LTS Version: 18.18.0 (includes npm 9.8.1) from https://nodejs.org/en/download. 
  Install Node js with the Setup Wizard.
  Read and accept License Agreement
  Select directory where to install Node.js
  Download android studio giraffe and setup an android emulator for testing

Configuration Steps

  Add Android_home to environment variables (path to your android sdk)
  Add platform-tools to PATH
  Make sure node.js is installed on the pc/laptop

Project Creation


  Open Node.js Command Prompt
  Install npm with npm install
  Change directory to correct directory eg: C:\CPRG-303
  Create the application “npx react-native@latest init Incredible Todo List App” (This step might take a while)

Running the project


  Run npm start to start your android app
  In the app folder under /android create a file called local.properties
  In local properties add this line “sdk.dir = “directory to sdk platform tools”
  On the console press a to run on Android
  Test the application on the android emulator.

Troubleshooting
   If running into ENONT: no such file or directory, lstat “Location of npm”
   In node run npm cache verify then try reinstalling npm again
   If problem still persists make sure the location of where you installed node is on your path (System variables)
   If problem still persists make sure when installing npm the directory is in %appdata%/roaming/npm
   If problem still persists try to delete package.json before creating the app
   If problem still persists edit package.json file and change expo version from "^1.0.0" to "~41.0.1"
   If missing sdk
   Go to android/ directory
   Create a file called local.properties
   Add this line “sdk.dir = “directory to sdk platform tools”
   If running into Could not resolve com.facebook.react:react-native-gradle-plugin
   Check if firewall is blocking the hosting of the app
   Check internet connection if not working
Resources
  React Native Docs: https://reactnative.dev/docs/environment-setup?guide=native).
  Expo Go Docs: https://docs.expo.dev/get-started/expo-go/
  Node Js Docs: https://nodejs.org/en/docs


React Native Docs: https://reactnative.dev/docs/environment-setup?guide=native).
Expo Go Docs: https://docs.expo.dev/get-started/expo-go/
Node Js Docs: https://nodejs.org/en/docs
