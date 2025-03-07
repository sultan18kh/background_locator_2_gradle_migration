# Looking for Maintainers
This project is no longer actively maintained. If you are interested in becoming a maintainer, please open an issue or contact me directly !

# background_locator_2 ! [![pub package](https://img.shields.io/pub/v/background_locator_2.svg)](https://pub.dartlang.org/packages/background_locator_2) ![](https://img.shields.io/github/contributors/Yukams/background_locator_fixed) ![](https://img.shields.io/github/license/Yukams/background_locator_fixed)

This package is a V2 of the background_locator package, fixing it and making it work for the newest versions of Flutter. Please read the wiki in order to make this plugin work with flutter 3.x.

A Flutter plugin for getting location updates even when the app is killed.

## Fork Information

This is a fork of the original background_locator_2 plugin with the following improvements:

- Added compatibility with Android Gradle Plugin 8.0+
- Fixed JVM target compatibility issues
- Updated Gradle and Kotlin dependencies
- Added proper namespace to Android build.gradle

## Usage with this fork

To use this fork in your Flutter project, add the following to your `pubspec.yaml`:

```yaml
dependencies:
  background_locator_2:
    git:
      url: https://github.com/sultan18kh/background_locator_2_gradle_migration.git
      ref: fix/gradle-compatibility
```

![demo](https://raw.githubusercontent.com/RomanJos/background_locator/master/demo.gif)

Refer to [wiki](https://github.com/Yukams/background_locator_fixed/wiki) page for install and setup instruction or jump to specific subject with below links:

* [Installation](https://github.com/Yukams/background_locator_fixed/wiki/Installation)
* [Setup](https://github.com/Yukams/background_locator_fixed/wiki/Setup)
* [How to use](https://github.com/Yukams/background_locator_fixed/wiki/How-to-use)
* [Use other plugins in callback](https://github.com/Yukams/background_locator_fixed/wiki/Use-other-plugins-in-callback)
* [Stop on app terminate](https://github.com/Yukams/background_locator_fixed/wiki/Stop-on-app-terminate)
* [LocationSettings options](https://github.com/Yukams/background_locator_fixed/wiki/LocationSettings-options)
* [Restart service on device reboot (Android only)](https://github.com/Yukams/background_locator_fixed/wiki/Restart-service-on-device-reboot)

##  License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Contributor
Thanks to all who contributed on this plugin to fix bugs and adding new feature, including:
* [Rekab](https://github.com/rekabhq) (creator of V1)
* [Gerardo Ibarra](https://github.com/gpibarra)
* [RomanJos](https://github.com/RomanJos)
* [Marcelo Henrique Neppel](https://github.com/marceloneppel)
* [Sultan Khan](https://github.com/sultan18kh) (creator of fork)
