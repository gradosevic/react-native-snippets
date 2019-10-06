# React Native Snippets

## Platform check

```javascript
Platform.OS === ('android' || 'ios')
```

## Platform speciffic CSS

```javascript
styles={{
  ...styles.headerBase,
  ...Platform.select({
    ios: stylesIosSpecific,
    android: stylesAndroidSpecific
 })
}}
```

## React Navigation

It's only for React Native
```javascript
npm i react-navigation
```
Fore expo useers, it's good to add additional packages
```javascript
expo install react-native-gesture-handler react-native-reanimated
```
