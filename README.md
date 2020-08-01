# 履歴書 (curriculum-vitae)

## 基本情報

| key | value             |
|:----|:------------------|
| ID  | yorisilo (依り代) |


## 私に関する技術キーワード
- Mac
- emacs
- golang
- web エンジニア
- バックエンドエンジニア
- docker
- kubernetes
- screwdriver
- vespa
- スクラム

## スキル
### プログラミング言語
- Golang
  - 広告配信バックエンドシステムの新規開発、保守、運用
  - WebAPI, Message Queue I/F を持つアプリケーションの開発
  - HDFS との連携
  - 疎結合なアプリケーション(マイクロサービスアーキテクチャの導入を行った)の開発
  - クリーンアーキテクチャを用いたアプリケーションの設計、開発
  - パフォーマンス・チューニング(並行処理)
- Python
  - デプロイスクリプトの改修(ansible, chef からの利用)
- OCaml
  - プログラム生成を行う言語の型システムの構築(大学院時代の研究)
- JavaScript
  - 広告クリエイティブの開発
- Ruby (Ruby on Rails)
  - Rails(バージョン4系) で構築された web サービスの機能追加、改修
- C++
  - 独自検索エンジンクライアントの開発保守運用
- Haskell
  - 趣味で多少書いた程度
- HTML, CSS

### DB, KVS
- HDFS
  - 利用経験
- Cassandra
  - 利用経験

### 検索エンジン
- Vespa
  - 保守、運用
  - Vespa 用クライアントの開発、保守、運用

### その他
- 実機、VM、 PaaS, CaaS のそれぞれのアプリケーションの設計、開発、保守、運用
- Git (GitHub) によるバージョン管理
- Screwdriverを用いたCI/CDパイプライン構築
  - GitHubのPR作成、マージにフックしテスト実行、デプロイ、などの自動化
- Splunk, prometheus, grafana によるメトリクスの可視化
- build pack を用いた PaaS でのアプリケーションの設計、開発、保守、運用
- kubernetes を用いた CaaS でのアプリケーションの設計、開発、保守、運用
- スクラムマスターとして、スクラム開発の補佐に従事
- OJTメンターとして新人の育成に従事

### 自然言語
- 日本語
  - ネイティブ
- 英語
  - かんたんな日常会話ができる

## 職務経歴
### 2017-10 - 2018-01
- 広告配信のバックエンドシステムで用いる独自検索エンジンまわりの設計、開発、保守、運用
- 言語は主に C++ を利用していた
- 実機、VMを利用した開発が主

#### 使用した主な技術
- c++
- chef
- fabric
- jenkins
- mdbm
- screwdriver など

#### 主な業務内容
- 開発フロー整備
  - git-flow もどきの運用だったものを github-flow へ統一
- 独自検索エンジンのクライアントの保守運用およびリファクタリング
- 独自検索エンジンの保守運用
- リリースジョブ修正

### 2018-02 - 現在(2019-10)
- 広告配信のバックエンドシステムで用いる検索エンジン vespa まわりの設計、開発、保守、運用
- 言語は主に golang を利用している
- PaaS, Caas での開発が主

#### 使用した主な技術
- golang
- vespa
- pulsar (Message Queue)
- PaaS
- CaaS
- kubernetes
- concourse
- screwdriver
- athenz
- splunk
- prometheus
- grafana など

#### 主な業務内容
##### 広告Item更新用システムの刷新
- 設計、開発、テスト、保守運用を担当
- golang による WebAPI の開発
- クリーンアーキテクチャの導入
- マイクロサービスアーキテクチャの導入
  - PaaS でのアプリケーション作成(VM -> PaaS への移行)
  - pulsar(Message Queue) を用いたアプリケーション間の疎結合化
- 監視、メトリクス可視化
- 単体テスト、結合テストの自動化
  - ネットワークを介した結合試験のため外部 Mock アプリケーションの作成
- CI/CD による各環境(dev, staging, prodなど)のデプロイ自動化
- concourse から screwdriver へ CI/CD 環境を移行

##### 広告Item更新用システムの新規開発(機械学習のためのデータを用意するコンポーネントの作成)
- 設計、開発、テスト、保守運用、各種担当者とのスケジュール調整を担当
- golang による開発
- PaaS, CaaS でのアプリケーション作成
- 並行処理などによるパフォーマンス・チューニング
- kubernetes の利用
  - ingress, service, deployment を使ったアプリケーションの作成
- HDFS との連携

##### 既存広告更新システムの PaaS から CaaS への移行および既存コンポーネントの処理を共通化
- 設計、開発、テスト、保守運用を担当
- golang による開発
- MQ(pulsar) を利用するコードのライブラリ化
- kubernetes の利用
  - ingress, service, deployment を使ったアプリケーションの作成

##### オンラインフィットネス新規サービスの開発
- 設計、開発、保守運用を担当
- 使用技術
  - framework: react with typescript
  - hosting: netlify
  - CI/CD: github actions
  - DB: firestore
  - realtime 配信PF: agora

##### tensorflow-servering を用いた機械学習プラットフォームを VM から CaaS への移行 (現在進行中)
- kubernetes の利用
  - ingress, service, deployment を使ったアプリケーションの作成
- パフォーマンスチューニング

## 課外活動(趣味など)
### ポッドキャスト
- 映画が好きなので、主に映画について話すポッドキャストをしている。
- 配信用ポッドキャストサイトを jeykyll + github pages で構築し、itunes で配信している。 近々 gatsby + netlify に移行予定
  - 配信サイト [yorisilo podcast](http://yorisilo.github.io/podcast/)

### 社内/社外勉強会
- 圏論勉強会の主催(ベーシック圏論の輪読会) [docs/read_basic_category_theory at master · yorisilo/docs](https://github.com/yorisilo/docs/tree/master/read_basic_category_theory)
- 電子回路における複素数のありがたさ [docs/impedance at master · yorisilo/docs](https://github.com/yorisilo/docs/tree/master/impedance)
- クリーンアーキテクチャについて [docs/clean-architecture at master · yorisilo/docs](https://github.com/yorisilo/docs/tree/master/clean-architecture)
- haskell での副作用の扱い方 [docs/side-effect-on-haskell at master · yorisilo/docs](https://github.com/yorisilo/docs/tree/master/side-effect-on-haskell)
- 再帰関数の効率的な書き方 with CPS [docs/recursive at master · yorisilo/docs](https://github.com/yorisilo/docs/tree/master/recursive)
- NIC を探し当てろ [go\-httpd/network\.md at master · yorisilo/go\-httpd](https://github.com/yorisilo/go-httpd/blob/master/slide/02/network.md)
- TCP/IP の息吹を感じよ [go\-httpd/networkcomand\.md at master · yorisilo/go\-httpd](https://github.com/yorisilo/go-httpd/blob/master/slide/02/networkcomand.md)

### 論文
- [Staging with Control: Type-Safe Multi-stage Programming with Control Operators (GPCE 2017 - 16th International Conference on Generative Programming: Concepts & Experience) - GPCE 2017](https://conf.researchr.org/details/gpce-2017/gpce-2017/14/Staging-with-Control-Type-Safe-Multi-stage-Programming-with-Control-Operators)

## 労働環境の希望
- 技術への理解がある
  - 技術に関して知的好奇心旺盛な人が多い環境
  - 技術的な相談が盛んに行われる社内の空気
  - (電子)書籍購入費、勉強会参加費の補助があるとうれしい
  - 社内勉強会などがよく行われている

- モダンな開発環境
  - 自動化の推進
  - CI/CD
  - アジャイル開発
  - Docker を使える

- フレックス制度
  - リモート勤務制度
  - コアタイムなしだとうれしい。あっても短めだとうれしい。

- 開発環境を選べる
  - MacBook での開発
  - エディタの選択の自由
  - マルチディスプレイ

- 評価基準の透明性
  - 期待しているもの、期待されているものが明確で透明性がある
  - 目標設定はあくまでも目標、それ以外のことを行った場合でもきちんと評価される風土

- 労働環境
  - 残業なし

# 参考
- この履歴書は次のテンプレートを使用している [okohs/Curriculum-Vitae-template: This is template of curriculum vitae. Please use this template when need your curriculum vitae.](https://github.com/okohs/Curriculum-Vitae-template)
