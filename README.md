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
