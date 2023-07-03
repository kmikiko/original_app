# README

## 開発言語
* Ruby 3.0.1
* Ruby on Rails 6.1.7

## 就業Termの技術
* Devise
* お気に入り機能
* フォロー機能
* AWS(EC2)へのデプロイ

## カリキュラム外の技術
* Spotify WebAPIを使用した楽曲再生機能
* Action cable を使った送信時リロードなしのコメント機能
* ransack を使用した検索機能

## 実行手順

```
$ git clone git@github.com:kmikiko/original_app.git
$ cd original_app
$ bundle
$ rails db:create
$ rails db:migrate
$ rails db:seed
$ rails s
```  

## カタログ設計, テーブル設計
https://docs.google.com/spreadsheets/d/1rgskN4CPZRHm1_0nyAryxIcdYGyQ6PzMTHMbZoDAzsw/edit?hl=JA#gid=2017131208


## ワイヤーフレーム
https://www.figma.com/file/vuSW4oWcpo730zwOtS08XB/Untitled?type=design&node-id=0-1&mode=design&t=W2ii61JIkdBxISu1-0
![ワイヤーフレーム3 ](https://github.com/kmikiko/original_app/assets/127947837/a453b8d0-7495-4e05-a8d5-636a65a507b9)
![ワイヤーフレーム2 ](https://github.com/kmikiko/original_app/assets/127947837/e459f80a-66ef-4efa-a456-f946cbfad72c)
![ワイヤーフレーム１](https://github.com/kmikiko/original_app/assets/127947837/f9729a2d-5459-447e-b65d-78ea10f082df)


## 画面遷移図
![original_app画面遷移 drawio ](https://github.com/kmikiko/original_app/assets/127947837/98664acb-8f34-402c-8d4e-4c5b7ce99331)


## ER図　
![original_app_er drawio ](https://github.com/kmikiko/original_app/assets/127947837/c2600800-9bb3-41c9-a7a7-c658832487fb)