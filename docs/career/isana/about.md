# イサナドットネット 株式会社（2017/04〜2019/08）職歴詳細

## 機械学習向け医療診断画像アノテーションアプリケーション (2019/03-2019/08)

### 概要

- 機械学習の学習データ収集のため、CT・MRI・X 線画像などに医師が病変に印をつける Web アプリケーション
- 既存アプリケーションへの機能追加・既存バグ修正、管理者機能の簡易な画面デザイン・実装、自動テストの追加を主に実施
- スクラム開発にて実施

### 開発体制

- 自社
  - エンジニア 3 名
  - ディレクター 1 名
- クライアント
  - エンジニア 2 名
  - ディレクター 1 名

### 採用技術

- Ruby on Rails
- jQuery
- RSpec
- Ruby-dicom
- devise
- Python
- Pydicom
- AWS
  - ECS
  - S3
  - Amazon RDS for PostgreSQL

### 担当業務

- 基本設計・詳細設計
- Prott を用いた画面モック作成
- 実装・自動テスト追加
- 既存バグ修正

### 開発について

- Python や Ruby は社内に経験者がほとんどいない開発言語だったため、日々学習や勉強会に参加して、知見を自分の中に吸収しながら開発を進めた
- Rails アプリケーションは Rails 5 から追加された[API 専用アプリケーション](https://railsguides.jp/api_app.html)だったが、新規に管理者機能を持たせるため、調査しながら通常の画面を持てる Rails アプリケーションとして動作するよう設定を変更した
- 管理者機能について、画面モックを作成し、クライアントと画面デザインや設計について週 1 回のビデオミーティングやチャットで認識をすり合わせていた

---

## 医療画像診断アプリケーション開発 (2018/08-2019/03)

### 概要

- [日本医療研究開発機構](https://www.amed.go.jp/)の[医工連携事業](https://www.amed.go.jp/koubo/02/01/0201C_00127.html)としての医療画像診断アプリケーションの開発に参加
  - 医療機器にて撮影した画像を閲覧する診断用アプリケーションを実装
- 開発には途中からアサインされたため、一部実装とユニットテストを担当
- スクラム開発にて実施

### 開発体制

- 自社
  - エンジニア 5 名
  - ディレクター 1 名
- クライアント
  - PO 1 名
  - ディレクター 1 名
  - 画像処理 SDK 開発担当の海外チーム

### 採用技術

- TypeScript
- C++
- OpenCV
- [ITK](https://github.com/InsightSoftwareConsortium/ITK)
- webpack
- Google C++ Testing Framework
- mocha
- Ubuntu16.04（検証用 VM 環境）

### 担当業務

- 環境構築作業
- 実装・ユニットテスト

### 開発について

- 医療画像特有の専門用語も多いため、初期から開発に関わっている上司やクライアントに確認しながら開発を進めた
- SDK の定期更新や VM 環境の不具合など、予期せぬコストがかかるため、開発を主導している上司が抱えきれない作業を他メンバーと協力し、積極的に引き取るようにしていた
- 海外チームも参画していることからプルリクエストやコードレビューの際に、英語でのコミュニケーションを行っていた

---

## VUI チャットボットアプリケーション開発 (2018/03-09)

### 概要

- クライアントの社内での音声チャットボットのデモ向けアプリケーションとして、Android アプリケーションの実装を実施
  - ボットが会話で質問した内容を基に、ユーザーへ健康になる行動変容をもたらすアドバイスを行うアプリケーション
- 要件定義、Azure でのインフラ設計から行い、デモサポートまで一通り担当
- スクラム開発にて実施

### 開発体制

- 自社
  - エンジニア 2 名
  - デザイナー 2 名
  - ディレクター 1 名
- クライアント
  - PO 1 名
  - ステークホルダー 2 名

### 担当業務

- 開発チームリーダー
- インフラ設計
- 技術調査・選定
- 要件定義・基本設計・詳細設計
- サーバーサイド実装・手動テスト
- デモサポート

### 採用技術

- Node.js
- Kotlin
- Express
- botbuilder
- JUnit
- Microsoft Azure
  - Azure SQL Database
  - Storage
  - WebApps
  - Cognitive Services(Text to Speech)
  - Azure Functions
- PowerBI
- Alexa

### 開発について

- 3 ヶ月 × 2 回でスクラム開発を進め、前半は Amazon Echo のアプリケーションとして開発、後半は Android アプリケーションとして開発
- 前半と後半でクライアントのハードウェアを変更しているが、スクラム開発の性質上、ボットのロジックをサーバーサイドに集約するよう設計・実装していたため、手戻りなく開発を進行した
- スクラム開発は社内でも 3 事例目であり、自身もスクラム開発に参加するのは初めてだったため、開発 2 ヶ月目ごろで Scrum Inc のスクラム研修に参加し認定を取得した

---

## 治験説明アプリケーション (2017/11-2018/02)

### 概要

- 紙で行っていた治験概要の説明業務を、音声説明や理解度を確認する機能で置き換えた WebView の iOS アプリケーションを実装
  - アプリケーションで表示するコンテンツは全て静的な Web ページとして実装
  - iPad で見せることから、WebView での iOS アプリケーションとして実装
- 病院側で通信環境を用意できないことが多いため、オフライン専用で実行するアプリケーションとして実装
- 要件定義から、画面デザイン、製造・手動テストまで実施

### 開発体制

- 自社
  - エンジニア 1 名
  - デザイナー 1 名
  - ディレクター 1 名
- クライアント
  - PO 1 名

### 担当業務

- 開発リーダー
- 技術調査・選定
- 要件定義・基本設計・詳細設計
- 実装・手動テスト

### 採用技術

- jQuery
- Cordova

### 開発について

- 今後 Web や Android への同アプリケーションの展開をクライアントが考えていたため、コードの再利用をしやすいハイブリッドアプリケーションを採用
- クライアントと週に 1 度ミーティングを行い、進捗やデモを行い、イメージのズレや手戻りがないよう確認を実施した

---

## 医療者向け患者情報管理システムの開発 (2017/04-2018/03)

### 概要

- スマートフォンアプリケーションで記録された日々の計測結果（血圧、体重等）の管理画面に加え、管理画面を閲覧する医療従事者が情報共有・記録するためのチャットシステムを Web アプリケーションとして構築した
- チャットシステムはチャット機能を持つ OSS を採用し、お客様の要件に合わせたカスタマイズを行った
- ウォーターフォール開発にて実施

### 開発体制

- 自社
  - エンジニア 4 名
  - ディレクター 1 名
- クライアント 3 名
- クライアントが委託した社外体制
  - インフラ設計・構築会社
  - 患者向けスマートフォンアプリケーション開発会社

### 担当業務

- 管理画面
  - 実装・テスト・リリース作業
  - 運用保守
- チャットシステム
  - 基本設計・詳細設計
  - 実装・手動テスト・リリース作業
  - 運用保守

### 採用技術

- Node.js
- Java 8
- [Meteor](https://www.meteor.com/)
- [Vaadin](https://vaadin.com/)
- AWS
  - ECS
  - EC2
  - Aurora MySQL
  - Lambda
  - CloudWatch
  - S3
  - SNS
  - SES
- Docker
- CircleCI

### 開発について

- ローカル環境での Eclipse とアプリケーションサーバーの開発環境の構築で、メンバー間で環境の差異が多かったため、開発に注力できるよう構築手順をチームリーダーと共に作成した
- CircleCI、Docker をプロジェクトで使用するのは社内で本プロジェクトが初だったため、プロジェクト完了後には、社内に知見を発表した
- DB からのデータ取得や Docker のデプロイなど運用時の定期的な作業が多く、効率化のために、シェルスクリプトや、手順書を作成した
- 初期開発後の本番運用前のテスト運用で、不具合が多く見つかった。原因としては、開発リーダーとお客様との間で仕様について認識合わせがうまくいっていなかったためである。私はお客様とその際のお客様との調整と不具合修正を担当した
- 不具合なども多かったが、プロジェクト成果として、1 フェーズ（半年間）200 名の日々の健康情報を利用した医師との健康向上プログラムを運用できた

---
