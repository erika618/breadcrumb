# README

# アプリ名
breadcrumb

<br>

# URL
Herokuによるデプロイ
<br>
https://breadcrumb-20210122.herokuapp.com/
<br>

# 説明

`gretel`というGemを用いて、パンくずリストを表示できるアプリです。
<br>
https://user-images.githubusercontent.com/68714247/105579693-4ad2b800-5dcb-11eb-8215-b2b87c0bc575.mp4
<br>


# 使用しているバージョン等

- ruby 2.6.5
- Rails 6.0.3.4
- MySQL

<br>

# clone
```
% git clone https://github.com/erika618/breadcrumb.git
% cd breadcrumb
% bundle install
% rails db:create
% rails db:migrate
```

<br>

# その他使用しているgem・使うコマンド
```
<!-- rubocop（インデントを整えるため） -->
% bundle exec rubocop -a

```