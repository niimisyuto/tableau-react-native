# react-native 公式に [tableauのコミュニティソース](https://github.com/tableau/mobile-app-bootstrap-react-native) を追加した形
- android buildToolsVersion = "29.0.3" → "33.0.0"
- gradle version = "3.3.1" → "7.3.1"

https://github.com/niimisyuto/tableau-react-native/assets/71388489/bb665798-8e52-42c1-8e73-84656f37b9a9


## react-native 導入手順

- jdk 11.0.8
- androidstudio 33 tiramisu, adb, gradle 7.5.1 all
- node 16.20 (nvm)
- watchman

- my Info
```
❯ npx react-native info --verbose
info Fetching system and libraries information...
System:
    OS: Windows 10 10.0.22621
    CPU: (12) x64 Intel(R) Core(TM) i7-9750H CPU @ 2.60GH
z
    Memory: 4.98 GB / 15.81 GB
  Binaries:
    Node: 16.20.0 - C:\Program Files\nodejs\node.EXE
    Yarn: Not Found
    npm: 8.19.4 - C:\Program Files\nodejs\npm.CMD
    Watchman: Not Found
  SDKs:
    Android SDK: Not Found
    Windows SDK: Not Found
  IDEs:
    Visual Studio: Not Found
  Languages:
    Java: 11.0.18
  npmPackages:
    @react-native-community/cli: Not Found
    react: 18.2.0 => 18.2.0
    react-native: 0.71.7 => 0.71.7
    react-native-windows: Not Found
  npmGlobalPackages:
    *react-native*: Not Found
debug Checking for a newer version of React Native       
debug Current version: 0.71.7
debug Checking for newer releases on GitHub
debug Latest release: 0.72.0-rc.3
```

## パス通す

- $env=JAVA_HOME = jdk11
- $env=ANDROID_HOME = android\sdk
- $env:Path = android\sdk\platform

## 設定

```shell
git clone
npm i
```

## 実行

### metro を起動

```shell
npx react-native start
```

### bundle + android にコンパイル

```shell
a
```

### react-native 端末 setting

- android 端末上で ctrl + m
