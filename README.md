# react-native 公式に tableau を追加した形

## react-native 導入手順

- git
- jdk 11.0.8
- androidstudio 33 tiramisu, adb or nox, gradle 7.5.1 all 
- node 16.20 (nvm)
- watchman

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

### bundler を起動

```shell
npx react-native1 start
```

### js ファイルをバンドルする

```shell
npx react-native bundle --platform android --dev false --entry-file index.js
--bundle-output D:/Dev/AwesomeProject/android/app/src/main/assets/index.android.bundle
--assets-dest D:/Dev/AwesomeProject/android/app/src/main/res --verbose-
```

### android にコンパイル

```.shell
npx react-native run
```
