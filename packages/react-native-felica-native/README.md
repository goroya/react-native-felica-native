# react-native-felica-native

## Getting started

`$ npm install react-native-felica-native --save`

### Mostly automatic installation

`$ react-native link react-native-felica-native`

### Manual installation


#### Android

1. Open up `android/app/src/main/java/[...]/MainApplication.java`
  - Add `import com.goroya.felica_native.RNFelicaNativePackage;` to the imports at the top of the file
  - Add `new RNFelicaNativePackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-felica-native'
  	project(':react-native-felica-native').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-felica-native/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-felica-native')
  	```


## Usage
```javascript
import RNFelicaNative from 'react-native-felica-native';

// TODO: What to do with the module?
RNFelicaNative;
```
  