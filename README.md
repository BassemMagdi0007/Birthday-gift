# Birthday-gift
Responsive, Cross-platform application "Works on Windows &amp; Catalina" . Created with HTML &amp; CSS and JavaScript, can be converted into an android &amp; an IPhone applications using Capacitor.js


#Bulid VsCode script To Android 
-------------------------------------
Git Bash

npm init -y                
npm install --save @capacitor/core @capacitor/cli

code  . 
CTRL+~

npx cap init
npx cap add android

npx cap sync //command updates dependencies, and copies any web assets to your project

npx cap copy //To copy web assets only, which is faster if you know you don’t need to update native dependencies


npx cap open android
