# docker-laravel 

## 導入手順

1.git cloneする

2.docker-compose build

3.docker-compose up -d

### ポートフォワーディング

* 8000→php
* 80→phpmyadmin

### laravel

* docker-compose exec app bashで入ってcomposerを使って
　<br>```composer create-project --prefer-dist laravel/laravel my-laravel-app```
  <br>で作ってください


※.envとvendorディレクトリは各laravelプロジェクトごとに異なるため、プロジェクトをpullしcomposer updateと.envsampleー＞.envに変更する
