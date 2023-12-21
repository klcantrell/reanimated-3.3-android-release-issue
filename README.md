Reproduction of non-functioning animations using Reanimated in a React Native Android release build 

Before commit [f0b7ae2](https://github.com/klcantrell/reanimated-3.3-android-release-issue/commit/f0b7ae26a8e818197fbe2ad0fba47ed362a4e69e), issue is present with Reanimated 3.3.0. With commit [f0b7aes](https://github.com/klcantrell/reanimated-3.3-android-release-issue/commit/f0b7ae26a8e818197fbe2ad0fba47ed362a4e69e) and on, issue is fixed with Reanimated 3.4.2.

## Steps to reproduce

1. Run `npm run prebuild` to scaffold the native projects
1. Run `npm run android -- --no-bundler --variant release` to build and install the Android app to a device in release mode
1. Navigate to the podcast list screen as shown in the attached videos and interact with the toggle
