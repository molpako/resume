---
layout: doc
---

# 職務経歴書

## 基本情報

|key|value|
|---|---|
|氏名|坂尾恭理（Sakao Kyouri）|
|生年月日|1993-02-22|
|居住地|福岡県福岡市|
|最終学歴|九州工業大学情報工学部卒|
|資格| 基本情報技術者、統計検定2級|


## 各種アカウント

<p style="display: flex; gap: 8px; flex-wrap: wrap;">
  <a href="https://github.com/molpako" target="_blank"><img alt="Github" src="https://img.shields.io/badge/molpako-%2312100E.svg?&style=flat-square&logo=Github&logoColor=white" /></a>
  <a href="https://x.com/molpako" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/@molpako-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white" /></a>
  <a href="https://molpako.hatenablog.com/" target="_blank"><img alt="Hate" src="https://img.shields.io/badge/molpako-00A4DE.svg?&style=flat-square&logo=hatenabookmark&logoColor=white" /></a>
</p>

## 職務経歴

### 2018-04 〜 現在 [GMOペパボ株式会社](https://pepabo.com/)

レンタルサーバーなどのホスティングサービスのインフラ運用に従事。2020-09 から現在まで メール/DNS サービスの信頼性向上を目的としたチームで業務を行っている。

- 主な使用技術
    - Go, Python, Nginx, MySQL, Ansible, Puppeet, Postfix, Dovecot, Ceph, MySQL
- 主な担当プロジェクト
    - スパムメール受信・送信対策
    - Gmailのメール送信者ガイドラインの適用
    - 送信時における通数の制限デーモンの開発（Go）
    - メールサービスのログイン認可デーモンの開発（Go）
    - Dovecot の quota service のクライアントであるポリシーサービスの開発（Go）
    - チームドキュメントをSphinxで構築
    - Nagios から Prometheus/Alertmanager のモダンな監視へ移行
    - systemd socket を使ったダウンタイムの少ないデーモンの立ち上げ
    - オンコール対応
- テックブログ
    - [「Pepabo Tech Conference 21 夏のSREまつり」開催レポート（一部）](https://tech.pepabo.com/2023/09/20/pepabotech/)
    - [メール送信を Postfix の Policy Delegation で制御する](https://tech.pepabo.com/2023/05/29/hosting-mre-policy-delegation/)


### 2016-04 〜 2018-03 [エコー電子工業](https://echo.e-aera.jp/)

新卒入社。受託や請負で、システム開発プロジェクトのインフラ担当者を経験。Ansibleを導入し、指名でのリピート案件を獲得し、新人賞受賞。

- 主な使用技術
    - ESXi, Ansible, Java
- 主な担当プロジェクト
    - 金融系プロジェクトの開発チームとして参画
    - システム開発プロジェクトのインフラ開発


## 業務での経験スキル

###  Go を使ったデーモンの設計・開発（5年〜

主にメールサービスと連携するデーモンを Go で開発していました。まず動くものを軽量プロトタイプとして作り、必要な要件を確認してから設計・開発に入る手法を実践していました。コーディングでは [Effective Go](https://go.dev/doc/effective_go), [Google Go Style](https://google.github.io/styleguide/go/) などの文献や標準ライブラリの実装を参考にして、より標準的な実装になるように意識しています。


### メール/DNS分野における専門的知識

メール（SMTP,POP,IMAP）サービスの運用経験があります。メールの信頼性を高めるために、送信ドメイン認証や不正クライアント対策を導入をしました。


### Ansible(molecule), Puppet を使った IaC 開発

Ansible と Puppet を使用し、Infrastructure as Code (IaC) の開発を行っていました。テストには molecule を活用し、インフラ構築の自動化と構成管理を効率的に実施しました。

### Prometheus/Alertmanger を使った監視設計

Nagios を使用したシンプルな閾値監視から、Prometheus/Alertmanager でメトリクスを使ったより柔軟な監視設計へ移行を進めました。

参考にした書籍

- [入門 監視 - モダンなモニタリングのためのデザインパターン](https://www.oreilly.co.jp/books/9784873118642/)
- [入門 Prometheus - インフラとアプリケーションのパフォーマンスモニタリング](https://www.oreilly.co.jp/books/9784873118772/)

## 意欲・興味

- Go または Python 環境での開発
- Cephなどの分散ストレージの運用
- 大規模トラフィック環境でのパフォーマンスチューニング
- 短いサイクルのアジャイル開発

## 業務外での経験スキル

- GAE と Datastore を使ったアプリケーション開発 
- スクレイピングと GCP Pub/Sub を使ってデータパイプライン構築
- pandas/jupyter notebook と sklearn を使った簡単なデータ分析と機械学習
- Ceph/Rook の構築や検証
- OSS へのコントリビュート
    - [prometheus-community/ansible fix(mysqld_exporter): Change condition for mysqld_exporter_host check](https://github.com/prometheus-community/ansible/pull/270)
    - [ceph/ceph doc/cephfs: fix architecture link to correct relative path](https://github.com/ceph/ceph/pull/56333)
    - [readthedocs/recommonmark Fix contents directive](https://github.com/readthedocs/recommonmark/pull/126)

## プライベートでしていること

- [DDD の学習](https://github.com/molpako/Architecture-Patterns-with-Python)
- 統計検定準1級の学習
