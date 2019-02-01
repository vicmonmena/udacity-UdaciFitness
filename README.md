## About this project

This project learns you to build a React Native app using most of the main features:
- React Native Components (View, Text, StatusBar, TouchableOpacity)
- React Native & Redux
- Look&Feel resources (icons, colors, fonts, images ...)
- React Native styling - CSS (StyleSheet)
- Navigation (TabNavigator, StackNavigator, )
- Customize UI based on Platform
- Expo components (AppLoading)

## How to run

```yarn start```

## Once the app is running

### Press `?` for command options, then:

- Press `a` to run on Android device/emulator,
- Press `i` to run on iOS simulator.
- Press `r` to restart bundler, or shift-r to restart and clear cache.

## Notes

### About `mapDispatchToProps`

Think of it as a way to format a dispatch before it gets to the component. So instead of having all that logic in the component, we put it in mapDispatchToProps then the component can simply call props.remove() or props.goBack