
# react-native-contact-csv

## Getting started

`$ npm install react-native-contact-csv --save`

### Mostly automatic installation

`$ react-native link react-native-contact-csv`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-contact-csv` and add `RNContactCsv.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNContactCsv.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNContactCsvPackage;` to the imports at the top of the file
  - Add `new RNContactCsvPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-contact-csv'
  	project(':react-native-contact-csv').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-contact-csv/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-contact-csv')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNContactCsv.sln` in `node_modules/react-native-contact-csv/windows/RNContactCsv.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Contact.Csv.RNContactCsv;` to the usings at the top of the file
  - Add `new RNContactCsvPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNContactCsv from 'react-native-contact-csv';

// TODO: What to do with the module?
RNContactCsv;
```
  