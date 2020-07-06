# Facets UI React Native initial package
### It allows assemble and run created Mobile Screens designed in the [FacetsUI Editor](https://www.facetsui.com/editor)

## What is FacetsUI?
It's a drag & drop editor to build Mobile UI and convert the design into the React Native source code. It makes it easy and quick to create Mobile UI screens and components.
![Product Presentation Image](https://muiditor-plugin.s3.amazonaws.com/laptop-basics-3.png)

## How to use it?

* download or clone the facetsui-react-native npm project
* open the terminal and perform

```
cd <absolute-path-to>/facetsui-react-native
```
* init react-native inside the current project with the preferred project name 
```
npx react-native init YourProjectName
mv YourProjectName/ios ios
mv YourProjectName/android Android
mv YourProjectName/app.json app.json
rm -rf YourProjectName
```
* go to the [FacetsUI Editor Project sample](https://www.facetsui.com/editor/1)
* press "Generate React Native Package" button

<p align="center">
<img src="https://muiditor-plugin.s3.amazonaws.com/generate-rn-package.png" width="50%">
</p>

* unzip generated package (it's might be in the downloads folder)
* drag and drop unzipped package named "src" inside the downloaded facetsuiRN project
* press "replace" if prompted
* in the terminal perform commands

###### YARN

```
yarn install
```

###### NPM

```
npm install
```

###### IOS

```
cd ios && pod install && cd ..
```

```
yarn ios
```
###### or
```
npm run ios
```

###### ANDROID
* open the emulator in Android Studio before run the terminal command
* run in the terminal
```
yarn android
```
###### or
```
npm run android
```

#### After few minutes you can play with the project inside the emulator, and the project ready for publishing in mobile stores.
