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

# Android
![Screenshot (135)](https://user-images.githubusercontent.com/60258792/119457530-143a8900-bd3c-11eb-910d-66eb731d0f5e.png)

# IPhone
![144895094_798999107363401_250159604435072287_n](https://user-images.githubusercontent.com/60258792/119457712-46e48180-bd3c-11eb-8cd7-80fa8b078bf3.jpg)
