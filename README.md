<div align="center">
   <a href="https://apple.co/458U0ul">
     <img src="https://leafy-wisp-bfecb8.netlify.app/images/screenshot/github_preview.png" alt="Linky">
   </a>
</div>

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
