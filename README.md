# Birthday Gift

## Introduction
This project is a responsive, cross-platform application designed to seamlessly operate on both Windows and macOS Catalina systems. Developed using a combination of HTML, CSS, and JavaScript, it offers a user-friendly experience across various devices and screen sizes.

## Technologies Used
- **HTML & CSS:** The application's structure and styling are crafted with HTML and CSS, ensuring a visually appealing and consistent design.

- **JavaScript:** The dynamic behavior and interactivity of the application are powered by JavaScript, enhancing user engagement and overall functionality.

- **Capacitor.js:** To extend the cross-platform capabilities, this project leverages Capacitor.js. Capacitor is a powerful framework that enables the conversion of web applications into native Android and iOS applications, providing a seamless user experience on mobile devices.

## Cross-Platform Compatibility
The application is designed to work flawlessly on both 'Windows' and 'macOS Catalina', catering to a diverse user base. Whether users are on a desktop computer, laptop, or tablet, the responsive design ensures optimal performance.

## Mobile Application Conversion
With the integration of `Capacitor.js`, this project can be effortlessly converted into native Android and iOS applications. This allows users to enjoy the application on their Android devices and iPhones, providing a consistent experience across different platforms.
  ```python
# Important Note
The cmd should be opend on the directory that has 'www' file in it
  ```
## Android Developers: Requirments & How to run

- **Node.js:** needs to be installed
- **VsCode:** preferred to be installed
- **Android Studio:** needs to be installed, would be cool if you added SDK. Well, it's necessry actually.
  
  
  ```python
  # Open cmd
  - pip install npm 
  - npm init -y  # This command initializes a new Node.js project by creating a package.json file with default values.
  - npm install @capacitor/android  # This installs the necessary Capacitor packages as project dependencies. 
  ```
  ```python
  # Open VsCode terminal
  - npx cap init  # This initializes Capacitor in the project. Capacitor needs to know some configuration details, and this command helps set up the necessary files.
  - npx cap add android  # This adds the Android platform to your Capacitor project. It prepares the project to be built and run as a native Android application.
  ```
  ```python
  # On the cmd...
  - npx cap sync  # This command updates dependencies and copies any web assets to your native project.
  - npx cap copy  # This command is optional. It copies web assets only, which can be faster if you know that you don't need to update native dependencies. 
  - npx cap open android  # This opens the Android Studio project associated with your Capacitor Android app. It allows you to build, run, and debug your native Android application.
  ```
### Android
![Screenshot (135)](https://user-images.githubusercontent.com/60258792/119457530-143a8900-bd3c-11eb-910d-66eb731d0f5e.png)
### To build the APK 
Andoid studio: go to Build -> Build Bundle -> Build Apk 

## IOS Developers: Requirments & How to run

- **Node.js:** needs to be installed
- **VsCode:** still preferred to be installed
- **Xcode:** needs to be installed
  
  ```python
  # Open terminal
  - pip install npm
  - npm init -y  # This command initializes a new Node.js project by creating a package.json file with default values.
  - npm install @capacitor/ios  # This installs the necessary Capacitor packages as project dependencies. 
  ```
  ```python
  # Open VsCode terminal
  - npx cap init  # This initializes Capacitor in the project. Capacitor needs to know some configuration details, and this command helps set up the necessary files.
  - npx cap add ios  # This adds the IOS platform to your Capacitor project. It prepares the project to be built and run as a native IOS application.
  ```
  ```python
  # On the terminal...
  - npx cap sync  # This command updates dependencies and copies any web assets to your native project.
  - npx cap copy  # This command is optional. It copies web assets only, which can be faster if you know that you don't need to update native dependencies. 
  - npx cap open ios  # This opens the Xcode project associated with your Capacitor IOS app. It allows you to build, run, and debug your native IOS application.
  ```
### IPhone
![144895094_798999107363401_250159604435072287_n](https://user-images.githubusercontent.com/60258792/119457712-46e48180-bd3c-11eb-8cd7-80fa8b078bf3.jpg)

## License 

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
