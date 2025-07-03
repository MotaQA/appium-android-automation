# My Appium Automation

This project utilizes Appium and WebdriverIO to automate the testing of a login feature 
using both valid and invalid credentials. Appium is an open-source tool for automating 
native, mobile web, and hybrid applications on Android. WebdriverIO provides a powerful 
framework for writing and executing automated tests in JavaScript.

## Instalation
```bash
npm install
```
>**NOTE:**
>
> It is necessary to have **Node.js**, **Appium**, **Android Studio**, and **Java JDK** properly installed and configured in your environment.
Also ensure that an Android emulator or a real device is available and connected.
>
>
> ## Running
>```bash
># Start the Appium server (default port 4723)
>appium
>
># Or start it on a custom port (e.g., 4724)
>appium -p 4724
>
># Then run the automation by command line
>npx wdio run wdio.conf.js
>
> ⚠️ If using a custom port, make sure the port property in your wdio.conf.js matches the one used when starting
>Appium.
>```
