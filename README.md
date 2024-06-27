<div align="center">
   <a href="https://apple.co/458U0ul">
     <img src="https://leafy-wisp-bfecb8.netlify.app/images/screenshot/github_preview.png" alt="Linky">
   </a>
    <h3>Linky</h3>
</div>
<p align="center">
  <em>
    Gesture-based app launcher for iOS: Open apps & shortcuts quickly
    <br/><br/>
    <b>10k views, 1k downloads on the App Store!</b>
  </em>
</p>
<p align="center">
  <a href="https://github.com/search?q=repo%3Akwsong0113%2Fimagine++language%3ATypeScript&type=code" target="_blank">
    <img src="https://img.shields.io/github/languages/top/kwsong0113/imagine" alt="Language">
  </a>
  <a href="https://apple.co/458U0ul" target="_blank">
    <img src="https://img.shields.io/itunes/v/6449445087?logo=Apple&label=App%20Store" alt="App store">
  </a>
   <img src="https://img.shields.io/badge/iOS-12.4+-blue?logo=Apple" alt="MIT license">
  <a href="https://github.com/kwsong0113/imagine/blob/master/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/License-MIT-teal.svg" alt="MIT license">
  </a>
</p>


## Getting Started
### Installation
Open a Terminal in the project root and run...

Install all dependencies:
```shell
yarn install
```
Install all pods:
``` shell
cd ios && pod install
```
### Running on Simulator
```shell
yarn ios
```

## Built With
Linky iOS is built using [React Native] and [TypeScript].

### User Interface
- [NativeBase] - UI library
- [Reanimated] & [React Native Gesture Handler] - For building interactive UIs
### Features
- [React Native Skia] - Drawing a gesture on canvas
- **[$Q Recognizer]** - **Gesture recognition**
- [Redux Toolkit] & [Redux Persist] & [Async Storage] - Managing application state, data and storage
- [i18next] - Internalization

### Analytics
- [Firebase] - Data analysis & Screen tracking (with [React Navigation])

### DevOps
Linky utilizes both App Store releases and CodePush for streamlined deployment.
- Xcode Cloud - Continuous deployment to the App Store
- [CodePush] - For Deploying updates directly to users

## License
Linky is licensed under the terms of the MIT license.
