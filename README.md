# [ARCHIVED] Dynamic Video Chat Rooms

**⚠️ This project is no longer maintained and has been archived.**  
Please note that this repository is now in a read-only state and will not receive any further updates or support.

We recommend using to the latest version of the **Agora React Native SDK**: [Learn more](https://www.agora.io/en/products/video-call/) 

For documentation and support, please visit the [Agora Documentation](https://docs.agora.io/en/).

---
React Native using **Agora RTC** and **RTM** SDKs to create dynamic rooms. The RTC SDK is used to share live audio/video, RTM is used to signal the room status to all connected users.

## Prerequisites
* '>= react native 0.60.x'
* iOS SDK 9.0+ (and a recent version of XCode and cocoapods)
* Android 5.0+ x86 arm64 armv7a
* A valid Agora account ([Sign up](https://console.agora.io/) for free)

<div class="alert note">Open the specified ports in <a href="https://docs.agora.io/cn/Agora%20Platform/firewall?platform=All%20Platforms">Firewall Requirements</a> if your network has a firewall.</div>

## Running this project

### Generate an App ID

In the next step, you need to use the App ID of your project. Follow these steps to [create an Agora project](https://docs.agora.io/en/Agora%20Platform/manage_projects?platform=All%20Platforms) in Console and get an [App ID](https://docs.agora.io/en/Agora%20Platform/terms?platform=All%20Platforms#a-nameappidaapp-id ).

1. Go to [Console](https://dashboard.agora.io/) and click the **[Project Management](https://dashboard.agora.io/projects)** icon on the left navigation panel. 
2. Click **Create** and follow the on-screen instructions to set the project name, choose an authentication mechanism (for this project select App ID without a certificate), and Click **Submit**. 
3. On the **Project Management** page, find the **App ID** of your project. 

### Steps to run the example

* Download and extract the zip file from the master branch.
* Run `npm install` to install the app dependencies in the unzipped directory.
  * If you're using iOS - Run `cd ios && pod install`. Please use a physical device as iOS simulator doesn't support cameras.
* Navigate to `./src/App.tsx` and edit line 56 to enter your App ID that you generated.
* Connect your device and run `npm run android` / `npm run ios` to start the app.


## Sources
* Agora [API doc](https://docs.agora.io/en/)
