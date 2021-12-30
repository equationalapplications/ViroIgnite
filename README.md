# ViroReact with Ignite React Native AR/VR

By Kurt VanDusen, Founder, [Equational Applications LLC](https://www.equationalapplications.com/), Grand Rapids, MI, USA.

This is an example of adding [ViroCommunity ViroReact](https://github.com/ViroCommunity/viro) to an existing React Native project. We will start with the boilerplate from Ignite version 7.8.4 and then manually add and link @viro-community/react-viro version 2.22.0 for augmented reality and virtual reality capabilities.

## Start with Ignite boilerplate for React Native

[Ignite React Native stack](https://github.com/infinitered/ignite)

Currently includes:

- React Native
- React Navigation
- MobX State Tree
- TypeScript
- And more!

## How to Install Viro in an existing project?

If you are integrating ViroReact into an existing project, have a look at our [Installation instructions](https://github.com/ViroCommunity/viro/blob/main/readmes/INSTALL.md). Please note that this does _not_ work with Expo Managed Workflows. Sorry!

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

You must run ViroReact on a physical device. The Android and iOS emulators are not supported.