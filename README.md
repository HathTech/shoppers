




## Thank You

Thank you for purchasing FlutterFire. If you have any questions that are beyond the scope of this help file, please feel free to create an issue here. Thanks so much!


## Installation

We believe you have [flutter](https://flutter.dev/docs/get-started/install) is installed in your system.

### Quickstart

```bash
flutter run
```

## Configuration

#### Change the bundle identifier
- Search for flutterfire and replace it with your own name.

### Firebase configuration 
- Create a firebase project

- iOS
 
     - Create an iOS app in the firebase console.
     - Download the Googleservice-info.plist file
     - Replace the file in "ios/Runner" 
- Android 
     - Create an Android app in the firebase console.
     - Download the google-services.json file
     - Replace the file in "android/app" 



##### When you run your app you might get an error containing "google secure content" replace the out error in info.plist file in "ios/Runner/info.plist"

Run the project. 
- Don't forget to enable email and Gmail authentication and enable firestore database.

#### Facebook configuration

- Create a [facebook app](https://developer.facebook.com)
- Enable facebook authentication in firebase
- Don't forget to enable email and Gmail authentication.
- Follow the facebook installation process on their website.
- Change the facebook app id in Android-manifest.xml and info.plist


### Push notification
- User will be asked to allow push notification in iOS, in android it is allowed by default.
- Token will be saved in user/user-id/tokens collection.
- To test push notification open tab cloud messaging in firebase console.
- Select the token from the above collection
- Add the title and message and send it.





Once again, thank you so much for purchasing this theme. As I said at the beginning, I'd be glad to help you if you have any questions relating to this. No guarantees, but I'll do my best to assist. If you have a more general question relating to the items on codecanyon, you might consider visiting the forums and asking your question in the "Item Discussion" section.


