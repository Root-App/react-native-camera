# React Native Camera [![Backers on Open Collective](https://opencollective.com/react-native-camera/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/react-native-camera/sponsors/badge.svg)](#sponsors) [![npm version](https://badge.fury.io/js/react-native-camera.svg)](http://badge.fury.io/js/react-native-camera) [![npm downloads](https://img.shields.io/npm/dm/react-native-camera.svg)](https://www.npmjs.com/package/react-native-camera)

### 🚧🚧 Looking for maintainers and backers 🚧🚧

See this [issue](https://github.com/react-native-community/react-native-camera/issues/3000)

We are looking for maintainers for this package, or to depreciate this in favor of [react-native-vision-camera](https://github.com/mrousavy/react-native-vision-camera) or [expo-camera](https://docs.expo.io/versions/latest/sdk/camera/), if nobody want to maintain this package.

## Docs
Follow our docs here [https://react-native-camera.github.io/react-native-camera/](https://react-native-camera.github.io/react-native-camera/)

The comprehensive camera module for React Native.

Supports:

- photographs.
- videos
- face detection (Android & iOS only)
- barcode scanning
- text recognition (optional installation for iOS using CocoaPods)

### Example import

```jsx
import { RNCamera, FaceDetector } from 'react-native-camera';
```

#### How to use master branch?

We recommend using the releases from npm, however if you need some features that are not published on npm yet you can install react-native-camera from git.

**yarn**: `yarn add react-native-camera@git+https://git@github.com/react-native-community/react-native-camera.git`

**npm**: `npm install --save react-native-camera@git+https://git@github.com/react-native-community/react-native-camera.git`

### Contributing

- Pull Requests are welcome, if you open a pull request we will do our best to get to it in a timely manner
- Pull Request Reviews are even more welcome! we need help testing, reviewing, and updating open PRs
- If you are interested in contributing more actively, please contact me (same username on Twitter, Facebook, etc.) Thanks!
- We are now on [Open Collective](https://opencollective.com/react-native-camera#sponsor)! Contributions are appreciated and will be used to fund core contributors. [more details](#open-collective)
- If you want to help us coding, join Expo slack https://slack.expo.io/, so we can chat over there. (#react-native-camera)

##### Permissions

To use the camera,

1) On Android you must ask for camera permission:

```java
  <uses-permission android:name="android.permission.CAMERA" />
```

To enable `video recording` feature you have to add the following code to the `AndroidManifest.xml`:

```java
  <uses-permission android:name="android.permission.RECORD_AUDIO"/>
  <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
  <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
```

![5j2jduk](https://cloud.githubusercontent.com/assets/2302315/22190752/6bc6ccd0-e0da-11e6-8e2f-6f22a3567a57.gif)

2) On iOS, you must update Info.plist with a usage description for camera

```xml
...
<key>NSCameraUsageDescription</key>
<string>Your own description of the purpose</string>
...
	
```
For more information on installation, please refer to [installation requirements](./docs/installation.md#requirements).

For general introduction, please take a look into this [RNCamera](./docs/RNCamera.md).

## Security contact information

To report a security vulnerability, please use the

[Tidelift security contact](https://tidelift.com/security).

Tidelift will coordinate the fix and disclosure.
