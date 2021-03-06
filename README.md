EmoCall - iOS Sample - Emotion Aware Video Communications using Twilio and Affectiva
==============================================================

This project is a sample application using [Twilio Video for iOS](https://www.twilio.com/docs/api/video). It aims to demonstrate more advanced video capturing and rendering techniques than the [Quickstart application](https://www.twilio.com/docs/api/video/guide/quickstart-ios).

### Requirements
This application was most recently updated to run against [version 0.24.1](https://www.twilio.com/docs/api/video/changelogs/ios) of the Twilio Video iOS SDK. 

### How to Run

* **Step 1:** Clone the repository to your local machine

* **Step 2 (option 1 - CocoaPods):** Run `pod install` at your terminal, from inside the cloned repository's working directory. Then open the Xcode Workspace created by CocoaPods (`VideoSampleCaptureRender.xcworkspace`).

* **Step 2 (option 2 - manual):** Open the Xcode project (`VideoSampleCaptureRender.xcodeproj`) from the cloned repository's working directory. [Download](https://www.twilio.com/docs/api/video/sdks#ios-sdk) the iOS Conversations framework and iOS Twilio Common framework. Drag and drop the framework files into your Xcode project, making sure that "Copy items if needed" is checked.

* **Step 3:** Insert a valid Twilio Access Token to `ViewController.swift` in place of the placeholder string `TWILIO_ACCESS_TOKEN`. You can generate a demo access token [here](https://www.twilio.com/user/account/video/dev-tools/testing-tools). Once you have this working, you may wish to connect your app with a server that [generates Access Tokens on-demand](https://www.twilio.com/docs/api/video/guide/identity).

* **Step 4:** Insert a valid Affectiva license string to `AffectivaRenderer.swift` in place of he placeholder string `AFFECTIVA_LICENSE`. You can obtain a license string [here](http://www.affectiva.com/sdk).

* **Step 5:** (optional) If you're interested in using the [Keen analytics service](http://www.keen.io), then you will need to obtain a valid project ID, as well as read/write keys in `AppDelegate.swift`.

* **Step 6:** Run the app. Running on a physical device will deliver a better experience, as the simulator cannot provide camera access.

### Learn more
- Check out the full Twilio documentation at https://twilio.com/docs/api/video, and Affectiva documentation at http://developer.affectiva.com
- Contact the Twilio support team at help@twilio.com and the Affectiva SDK support team at sdk@affectiva.com
