# react-native 公式に [tableauのコミュニティソース](https://github.com/tableau/mobile-app-bootstrap-react-native) を追加した形

https://github.com/niimisyuto/tableau-react-native/assets/71388489/bb665798-8e52-42c1-8e73-84656f37b9a9


## react-native 導入手順

- git
- jdk 11.0.8
- androidstudio 33 tiramisu, adb, gradle 7.5.1 all
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

### metro を起動

```shell
npx react-native start
```

### bundle + android にコンパイル

```shell
a
```

### react-native debug モード

- android 端末上で ctrl + m
