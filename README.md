# react-native-pusher-beams

## Getting started

`$ npm install react-native-pusher-beams --save`

### Mostly automatic installation

`$ react-native link react-native-pusher-beams`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-pusher-beams` and add `PusherBeams.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libPusherBeams.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.reactlibrary.PusherBeamsPackage;` to the imports at the top of the file
  - Add `new PusherBeamsPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-pusher-beams'
  	project(':react-native-pusher-beams').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-pusher-beams/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-pusher-beams')
  	```


## Usage
```javascript
import PusherBeams from 'react-native-pusher-beams';

// TODO: What to do with the module?
PusherBeams;
```
