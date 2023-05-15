# react-native 導入手順

- vscode
- jdk
- androidstudio
- node
- git

## react-native 公式に tableau を追加した形

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
