# React Native App - Travel App UI

This repo is a react native app that using Expo, NativeWind / Tailwind CSS (3.3.2), and React Navigation.

YouTube Link - https://www.youtube.com/watch?v=vV9zIDgT4Ik
Tutorial Repo - https://github.com/syednomishah/Travel-App-React-Native

## Tailwind / NativeWind
Make sure to  use version 3.3.2 in this project and make sure to include the following in `App.js` to get it working:
```
import { NativeWindStyleSheet } from 'nativewind'

NativeWindStyleSheet.setOutput({
  default: 'native',
})
```
Once added in App.js, restart server. Might need to clear cache by running `expo start -c`.
