# Bootstrap & Sass

## 安裝流程
```
// 檢查 node 版本
$ node -v

// 安裝 gulp 到 全域環境(-g) gulp
// Windows 版
$ npm install gulp -g
// Mac 版
$ sudo npm install gulp -g

// 安裝套件非常多, 所以需要安裝時間
$ npm install

// 執行啟動
$ gulp

// 結束
Windows 版 & Mac 版: Ctrl + C

// 直接將檔案部屬到 GitHub 上
$ gulp deploy
```

## 架構簡介
完整的檔案於 `source` 資料夾, `public` 資料夾為編譯後的檔案, `node_modules` 資料夾是 `npm install` 所安裝的檔案, `.publish` 是部屬到 GitHub 上所使用的.

