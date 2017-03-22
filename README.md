# react-nativebase-demo
Demo of nativebase tutorial
## Getting Started

### iOS

  - `brew install node`
  - `brew install watchman`

### Install React-Native CLI
  - `npm install -g react-native-cli`
  
### Install React-Native Package Manager (rnpm)
  - `npm install rnpm -g`

### Create your react-native nativebase project
  - `react-native init yourNativebaseDemo`
  - `cd yourNativebaseDemo` 
  - `npm install native-base --save `
  - `rnpm link`


Now you can test whether or not that worked by running `react-native run-ios`

From here we will be making a single codebase for our iOS and Android UI's so to start that create a file named `app.js`

Then inside your `index.ios.js` and `index.android.js` files, add this:
```import App from './app';
export default App;```
