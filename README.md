### Flutter E-Commerce App using Firebase and Stripe

![Shoppers](https://i.imgur.com/LIHHX0j.png)


### Introduction

Shoppers is an eCommerce app inspired by Flutter framerwork, made by Google. With the mission of reducing 100+ hours of business spent on designing, developing and testing a mobile app, Shoppers comes as a complete solution for optimizing to deliver your app to the market with high productivity and cost-efficiency. It could be able to satisfy all of the business requirements including e-commerce functionalities, impressive UX design and smooth performance on both iOS and Android devices.
The download package is included the full source code and many related resources (designs, documents, videos…) that help you install in the smoothest way.

Either you are business people with raising sale ambition or developers with faster mobile application creation need, Shoppers provides you solutions. Faster- Smoother- Closer.

## Features

- Easy to use. 
- Sign In and Sign Up with Email
- Sign In with Facebook
- Sign In with Google
- Flutter firebase phone authentication (Test: +919852954321, CODE: 333333)
- Push notification 
- Clean Code And Well Documented. 
- Bloc pattern 
- Custom Carousel Slider 
- Easy setup 
- Form Validation
- Admin dashboard
- Stripe payment gateway
- Full e-commerce features – Dynamic Product variants, checkout process, order tracking, order notes, wishlist, manage address.
- Great UX design multi-level categories, quick product filter, super smooth checkout flow, searching keyword history…

- Flexible Design System – easy to config the logo and style.

- Powerful User Setting – the ability to enable the push notification, view wishlist, order history.

- Push notification 
- Offline Images Caching – speed up the loading performance with caching image offline method.
- Realtime 
- 60 frames per second (fps) app – working really well on both iOS and Android with support with

### What will you get?
- Full Dart source code
- Free version upgrade
- Free Video tourtial, please [subscribe](https://www.youtube.com/channel/UC-_pVFNRfGQBGC5P63V_ABQ)


## Thank You

Thank you for purchasing Shoppers – **Flutter E-Commerce App using Firebase and Stripe**. If you have any questions that are beyond the scope of this help file, please feel free to create an issue here. Thanks so much!


## Installation

We believe you have installed flutter in your system if not then install [flutter](https://flutter.dev/docs/get-started/install)

### Quickstart

```bash
flutter run
```

## Customization

### 1. App name/icon, Bundle ID

#### 1.1 Change the app name:

**IOS app:**

- Open ios/Runnder/Info.plist and replace the FluxStore by your App Name
```
<key>CFBundleDisplayName</key>
	<string>Fluxstore</string>
```

- Make sure to clean up the cache by running following scipt to clean the previous cache
```
flutter clean
flutter build ios
```

>> It's possible to change via XCode - https://tppr.me/Mfu5F.The facebook app name and App ID could be change from this file as well

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


