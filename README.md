# ViroReact with Ignite  

By Kurt VanDusen, sole member, Equational Applications LLC of Grand Rapids, MI, USA.

This is an example of adding @viro-community/react-viro to an existing React Native project. We will start with the boilerplate from Ignite and then manually add and link ViroReact for augmented reality capabilities.

[ViroCommunity ViroReact on GitHub](https://github.com/ViroCommunity/viro)

## The latest and greatest boilerplate for Infinite Red opinions

This is the boilerplate that [Infinite Red](https://infinite.red) uses as a way to test bleeding-edge changes to our React Native stack.


Currently includes:

- React Native
- React Navigation
- MobX State Tree
- TypeScript
- And more!

## Quick Start

1. `git clone https://github.com/equationalapplications/ViroIgnite`
2. `cd ViroIgnite`
3. `yarn install`
4. (optional) `npx react-native-rename <newName> -b <bundleIdentifier>`
5. `npx pod-install` (iOS)
6. `npx react-native run-android` or `npx react-native run-ios`

Note: for optional step 4 above, use your own app name and bundle identifier. For example, `npx react-native-rename ViroApp -b com.example.viroapp`

If `npx react-native run-android` fails with EACCESS gradlew.bat or EACCESS gradlew, run `chmod +x gradlew.bat` or `chmod +x gradlew`.

The variant arguments are not needed for debug or release.

You must run ViroReact on a physical device. The Android and iOS emulators are not supported. See [this](https://docs.viromedia.com/docs/installing-viro-android) for more information.

## How to Install Viro in an existing project?

If you are integrating ViroReact into an existing project, have a look at our [Installation instructions](https://github.com/ViroCommunity/viro/blob/main/readmes/INSTALL.md). Please note that this does _not_ work with Expo Managed Workflows. Sorry!