
### Template for React Native project based on typescript, mobx, react-navigation, reanimated, etc.

1. Make sure that you install latest react native cli: `yarn global remove react-native-cli` and `yarn global add @react-native-community/cli`.
2. Run `npx react-native init YourProjectName --template https://github.com/Navipro70/react-native-full-template.git`, replace `YourProjectName` with your name.
3. Run `yarn pods` and `yarn ios` or `yarn android` 🎉🎉🎉

### Some tips

1. After init don't forget to replace fonts at `/assets/fonts` with your real fonts, then run: `npx react-native link` and delete previous fonts from ios and android folders.
2. Setup splash screen https://github.com/zoontek/react-native-bootsplash and don't forget about dark/light splash screens.
