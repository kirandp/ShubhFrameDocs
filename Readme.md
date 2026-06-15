# Shubh Frame

**Shubh Frame** is a mobile photo frame, poster, advertisement, and short video creation app built with **React Native** and **Expo**.

The app allows users to select ready-made templates, upload their own photos, add text, stickers, emojis, colorful effects, animated effects, and export the final design as an image or video.

---

## Features

### Photo Frame Creation

* Choose from ready-made frame templates
* Upload photos from the device gallery
* Adjust photo fit inside the selected frame
* Create personalized designs for different occasions

### Personal Templates

Create beautiful personal designs for:

* Birthdays
* Weddings
* Anniversaries
* Festivals
* Travel memories
* Family memories
* Graduation
* Newborn celebrations
* Social media posts

### Business Advertisement Templates

Create promotional designs for:

* Shops
* Local businesses
* Product promotions
* Offers and sales
* Events
* Service advertisements
* Social media marketing

### Text Editing

* Add custom text
* Move and resize text
* Add names, wishes, captions, offers, addresses, and contact details
* Customize design content easily

### Stickers and Emojis

* Add emojis and stickers to designs
* Use creative decorative elements
* Create attractive social media-ready visuals

### Colorful Effects

The app includes multiple visual effects such as:

* Balloons
* Hearts
* Stars
* Butterflies
* Fish
* Cars
* Aeroplanes
* Boats
* Helicopters

### Image Export

* Save final designs as images
* Share designs with friends, family, customers, or social media platforms

### Video Generation

* Generate short videos from designs
* Add animated effects
* Export designs as MP4 videos
* Useful for greetings, festival videos, personal videos, and promotional videos

---

## Tech Stack

* React Native
* Expo
* TypeScript
* React Native SVG
* React Native Reanimated
* React Native View Shot
* Expo Image Picker
* Expo Media Library
* Expo File System
* Expo Video
* AsyncStorage

---

## Project Structure

```txt
ShubhFrame/
├── assets/
│   ├── icon.png
│   ├── adaptive-icon.png
│   └── video/
├── src/
│   ├── components/
│   ├── config/
│   ├── screens/
│   ├── types/
│   └── utils/
├── android/
├── app.json
├── package.json
├── tsconfig.json
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/shubh-frame.git
cd shubh-frame
```

Install dependencies:

```bash
npm install
```

Install required Expo dependencies:

```bash
npx expo install
```

---

## Running the App

Start Expo:

```bash
npx expo start -c
```

Run on Android:

```bash
npx expo run:android
```

Run on iOS:

```bash
npx expo run:ios
```

---

## Android Build

Generate Android native files:

```bash
npx expo prebuild --clean --platform android
```

Build Android APK:

```bash
cd android
./gradlew assembleRelease -x test -x testDebugUnitTest -x testReleaseUnitTest
```

Build Android AAB for app store release:

```bash
cd android
./gradlew bundleRelease -x test -x testDebugUnitTest -x testReleaseUnitTest
```

The generated AAB file will be available at:

```txt
android/app/build/outputs/bundle/release/app-release.aab
```

The generated APK file will be available at:

```txt
android/app/build/outputs/apk/release/app-release.apk
```

---

## Android Configuration

The app uses the following Android package name:

```txt
com.kirandp.advertisementeditor
```

Recommended Android build configuration:

```json
[
  "expo-build-properties",
  {
    "android": {
      "minSdkVersion": 24,
      "compileSdkVersion": 36,
      "targetSdkVersion": 34
    }
  }
]
```

---

## Permissions

The app may request the following permissions:

* Photo library access
* Media access
* Save to gallery permission
* Storage permission on older Android versions

These permissions are used for:

* Selecting user photos
* Adding photos to frames
* Saving generated images
* Saving generated videos
* Sharing completed designs

---

## Privacy

Shubh Frame processes user-created designs on the user’s device.

Unless specifically stated otherwise, selected photos, edited images, and generated videos are not uploaded to any server by the app. Final images or videos are saved locally only when the user chooses to save them.

Users are responsible for the photos, logos, text, business details, and other content they use in the app.

---

## Disclaimer

Shubh Frame allows users to create personalized images, frames, posters, advertisements, and videos using their own uploaded photos, text, templates, stickers, and design elements.

Users are solely responsible for ensuring that generated content does not violate copyright, trademark, privacy, publicity, or third-party rights.

Users must not upload or generate content that is illegal, harmful, offensive, misleading, defamatory, abusive, discriminatory, obscene, or rights-infringing.

---

## App Store Description

Create photo frames, posters, ads, greetings, and short videos using your photos. Add text, stickers, emojis, effects, save, and share easily.

---

## Release Checklist

Before publishing the app, verify:

* App icon is added
* Splash screen is working
* Package name is final
* Version code is updated
* Privacy policy is ready
* Disclaimer is included
* Photo upload works
* Image export works
* Video export works
* Save and share functionality works
* App does not crash on launch
* Release APK/AAB is tested on a real device

---

## License

This project is proprietary software.

All rights reserved. Do not copy, distribute, modify, or use this project without permission from the owner.

---

Please refer below video on how to use the application:

https://drive.google.com/file/d/1q44rqK-MUGJcrxSy0p2a6tj4W-t6IX0i/view?usp=share_link



## Author

**Developer:** Ashwini P.
**Contact:** indian.insect.killer@gmail.com
