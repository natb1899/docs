---
sidebar_position: 2
---

# Change the project name

```js title="Used packages"
rename: ^3.0.0;
```

## Commands

To change the project name on `all platforms`:

```bash
flutter pub global run rename --appname "Application Name"
```

To change the project name on `a specific platform`:

```bash
flutter pub global run rename --appname yourappname -t macOS  //support also ios and android
```

or edit `AndroidManifest.xml` for Android and `info.plist` for iOS

:::caution

Do a flutter clean and restart your application if you have a problem.

:::
