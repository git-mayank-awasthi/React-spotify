## Build and run the app

1. Install React Native as described at [https://facebook.github.io/react-native/docs/getting-started.html#content](https://facebook.github.io/react-native/docs/getting-started.html#content)
2. Clone this repository
3. Run `yarn install` , all required components will be installed automatically

    ### iOS
      
    1. Run `pod install` from `react-native-demo/ios` folder
    2. Start XCode and open generated `VoximplantDemo.xcworkspace`
     
    ### Android
    
    no steps required
        
    Note: 
    To enable android push notifications in the demo project:
    1. Follow [the instructions](https://voximplant.com/docs/introduction/integration/adding_sdks/push_notifications/android_sdk) to add the certificates to the Voximplant Cloud 
    2. Add `google-services.json` file to android/app folder
    3. Open `app/build.gradle` file and uncomment the `//apply plugin: 'com.google.gms.google-services'` line

4. It is recommended to run `react-native start` command from root project directory.
5. Run your project from XCode (`Cmd+R`) for iOS, or use `react-native run-android` to run your project on Android.


