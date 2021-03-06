**README.md**

# J-Packer(仮)

# 概要

**海外旅行をした際の宿泊先で日本人宿を探す際に、**
**ネットで検索をかけなくてもアプリが位置情報を特定して日本人宿を探してくれる。**
**海外旅行に行く人全般むけのアプリだが、どちらかというとバックパッカー向け**

日本人宿：「世界各地に点在している、日本人が経営する安宿」のことで
バックパッカーがよく利用するゲストハウスのような場所。
わからないことがあれば誰かに質問することがいつでもでき、旅の仲間ができやすいことも魅力。

# コンセプト
訪れた国の日本人宿を簡単に見つけることができる

# バージョン情報
* Ruby 2.6.5
* Rails 5.2.4
* Postgresql 13.1

# 機能一覧
* ユーザー登録（画像含む）
* ログイン、ログアウト機能  
* ゲストログイン
* 位置情報特定機能 
* 宿検索機能
* 宿先詳細ページ
* 予約ページ
* コミュニティー画面
* コメント機能 
* いいね機能
* 日本人宿以外のホテル検索（タブで切り替え）
* 泊まった宿のレビュー 
* 個人情報登録
* 過去に泊まったところ 
* 管理者機能
* ホテル登録（宿主用のログイン機能）
* ホテル周辺のお店情報  
* 決済機能   
* スマホ対応 

# カタログ設計
https://docs.google.com/spreadsheets/d/1Tc0FE-ffoBvK5L20tNceU-WdeQINK9RC0-crG0NmXUs/edit#gid=0

# テーブル設計
ER図：https://cacoo.com/diagrams/n6fyPFohq5aakEym/9E725?reload_rt=1616654748335_0 

テーブル：https://docs.google.com/spreadsheets/d/1Tc0FE-ffoBvK5L20tNceU-WdeQINK9RC0-crG0NmXUs/edit#gid=1447470511

# 画面遷移図
https://docs.google.com/spreadsheets/d/1Tc0FE-ffoBvK5L20tNceU-WdeQINK9RC0-crG0NmXUs/edit#gid=773858931

# 画面ワイヤーフレーム
https://cacoo.com/diagrams/n6fyPFohq5aakEym/F59BB?reload_rt=1616654748335_0

# 使用予定Gem/技術
* devise
* gem devise-i18n
* ransac
* rails admin
* cancancan
* dotenv-rails
* gon
* geocoder
* bootstrap4
* active storage  or  carrier wave
* AWS

(猶予があれば)

* Payjp
* jpmobile
* OAuth