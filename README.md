# Laravel 8 視覺效果路由

引入 wulfheart 的 pretty_routes 套件來擴增視覺效果路由，`routes` 目錄中的路由檔案定義了所有的 Laravel 路由，這些檔案會自動被框架載入並呈現。

## 使用方式
- 把整個專案複製一份到你的電腦裡，這裡指的「內容」不是只有檔案，而是指所有整個專案的歷史紀錄、分支、標籤等內容都會複製一份下來。
```sh
$ git clone
```
- 將 __.env.example__ 檔案重新命名成 __.env__，如果應用程式金鑰沒有被設定的話，你的使用者 sessions 和其他加密的資料都是不安全的！
- 當你的專案中已經有 composer.lock，可以直接執行指令以讓 Composer 安裝 composer.lock 中指定的套件及版本。
```sh
$ composer install
```
- 產生 Laravel 要使用的一組 32 字元長度的隨機字串 APP_KEY 並存在 .env 內。
```sh
$ php artisan key:generate
```
- 執行 __Artisan__ 指令的 __migrate__ 來執行所有未完成的遷移。
```sh
$ php artisan migrate
```
- 執行安裝 Laravel Mix 引用的依賴項目，並執行所有 Mix 任務。
```sh
$ npm install && npm run dev
```
- 執行 __Artisan__ 指令的 __route:pretty__ 來執行路由視覺效果化。
```sh
$ php artisan route:pretty
```

----

## 畫面截圖
![](https://i.imgur.com/rRpZWMR.png)
> 列出目前所有的路由視覺效果化