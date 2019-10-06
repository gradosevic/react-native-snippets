# React Native Snippets

## Platform check
Platform.OS === ('android' || 'ios')

## Platform speciffic CSS
styles={{
  ...styles.headerBase,
  ...Platform.select({
    ios: stylesIosSpecific,
    android: stylesAndroidSpecific
 })
}}
