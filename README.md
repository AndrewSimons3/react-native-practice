https://dottedsquirrel.com/react/how-to-set-up-react-native/

When setting up React Native, you have two options: the Expo CLI Quickstart or React Native CLI Quickstart.

We’ll be using Expo because it gives you a managed app development workflow that lets you focus on the act of developing an app rather than the supporting things around it. 

Expo is a free third party service and takes away the complexity of React Native app development. However, when you’re using Expo, you are limited to the Expo ecosystem of support. This is because Expo is like a wrapper around your React Native app. 

https://expo.io/learn

Step 1: Download NodeJS

Step 2: npm install expo-cli --global

Step 3: expo init new-project-name-here

It will ask you about which template to use. You can start off with the blank template. If you choose the bare-minimum option, it will set up your React Native app without Expo. 

Hit enter again and it may ask you if you want to use Yarn to install the dependencies. But this will only happen if you have Yarn installed on your machine. If you choose no, it’ll use npm to install the dependencies.

Once that’s completed, cd into the folder generated and use the command expo start to run it.

cd new-project-name-here
expo start

Step 4: It’ll give you a QR code on the screen for you to scan with your mobile phone using the iOS or Android app (downloadable from the app/play store)

This QR code acts as a tunnel that will automatically compile any changes you make in your code, giving you instant and automated feedback. 
