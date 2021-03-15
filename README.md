# Build and run the app


Install React Native as described at https://facebook.github.io/react-native/docs/getting-started.html#content

Clone this repository

Run yarn install , all required components will be installed automatically

iOS
Run pod install from react-native-demo/ios folder
Start XCode and open generated VoximplantDemo.xcworkspace
Android
no steps required

Note: To enable android push notifications in the demo project:

Follow the instructions to add the certificates to the Voximplant Cloud
Add google-services.json file to android/app folder
Open app/build.gradle file and uncomment the //apply plugin: 'com.google.gms.google-services' line
It is recommended to run react-native start command from root project directory.

Run your project from XCode (Cmd+R) for iOS, or use react-native run-android to run your project on Android.
