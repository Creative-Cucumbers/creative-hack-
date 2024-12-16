# 🤝 ハンズオン#2

![](../../images/2024-12-16-21-14-03.png)
by OpenAI DALL-E

[TOC]

---

## 3 限目前半

## 1. ▶️ イントロダクション

### 1.1. 🙋 出欠登録

### 1.2. 🧊⛏️ アイスブレイク

```
タイピング得意？
1. 得意
2. 普通
3. 苦手
```

```
mixi知ってる？
1. 使ってた
2. 知ってる
3. 何それ
```

```
OpenAIのアドバンスト・ボイス・モード知ってる？
1. 使った
2. 知ってる
3. 何それ
```

### 1.3. 📌 コース概要

このコースの後半 7 回では、前半で身につけたデザイン思考やシステム設計開発のスキルをさらに発展し、ワークショップやハンズオン、ハッカソンを通して手を動かしながら、他者と協力し目の前の課題に深く向き合い解決方法を探る力を身につけます。

![](../1_introduction/images/2024-11-19-01-38-35.png)
by OpenAI DALL-E

### 1.4. 📅 スケジュール

|   回数   |          1          |            2             |      3       |      4       |           5           |           6           |           7           |
| :------: | :-----------------: | :----------------------: | :----------: | :----------: | :-------------------: | :-------------------: | :-------------------: |
|   日程   |        11/27        |          12/04           |    12/11     |    12/18     |         12/25         |          1/8          |         1/15          |
|  テーマ  | Creative Hack Plus? | アジャイルワークショップ | ハンズオン#1 | ハンズオン#2 | ミニハッカソン#1 計画 | ミニハッカソン#2 実装 | ミニハッカソン#3 発表 |
| 担当講師 |        伊藤         |        伊藤、小島        |     伊藤     |     伊藤     |      伊藤、小島       |      伊藤、小島       |      伊藤、小島       |
|   場所   |      リモート       |        オンサイト        |   リモート   |   リモート   |      オンサイト       |      オンサイト       |      オンサイト       |

### 1.5. 👩‍💻 Creative Hack Plus と BTC (Business Technology Creative)

「Creative Hack Plus」は今まで学んだソリューションの呼び方を変えたもので、コース後半のテーマです。クリエイティブなアイデアや手法を活用して既存の問題を新たな視点で解決し、価値を創造することを指します。既存の枠組みにとらわれない「Creative」と「Hack」が本来持つ「効率的な解決法」や「機転を利かせた手段」という意味に「Plus」を加えることで、個人の課題解決にとどまらず、他者の課題解決や持続可能なビジネスモデルの提案へと発展させる意図を込めました。また、クロステックデザインコースで重視している BTC（Business Technology Creative）とも以下のように対応しています。

| **Creative Hack Plus** | **Business Technology Creative** | **説明**                                                                             |
| ---------------------- | -------------------------------- | ------------------------------------------------------------------------------------ |
| **Creative**           | Creative                         | 新しい視点や発想で問題を解決する創造性。                                             |
| **Hack**               | Technology                       | 技術を活かして迅速かつ柔軟に課題に取り組む姿勢。                                     |
| **Plus**               | Business                         | 個人の課題解決を越えた持続可能な価値創造、ビジネスモデルの構築、社会へのインパクト。 |

---

### 1.6. 🤖 前回振り返り

前回の授業では、AI アプリ開発プラットフォーム「Dify」を使用して、実際に AI アプリを開発しながらアジャイル開発について学びました。「関西弁チャットボット」や「授業レポート作成支援アプリ」などのテーマで MVP を意識したアプリ作成を行い、アプリケーション開発を体験しました。また、アジャイル開発の基本的な考え方や手法についても触れ、プロジェクトの方向性を共有するインセプションデッキやビジネスモデルキャンバスの概念を紹介しました。

### 1.7. 📋 本日の内容

## 2. 前回の復習

- Dify の登録
- gemini API key を取得
- AI アプリの開発
- アジャイル開発の一部
- システムモデル設定

## 3. 応用編：プログラミング言語を用いた AI アプリ開発

- プログラミング言語を用いて生成 AI を呼び出す方法
  - アーキテクチャ
  - 実行環境: [CodeSandbox](https://codesandbox.io/)
  - API の仕様もしくは使用例を取得
  - 生成 AI に Gemini API + HTML + JavaScript + CSS でチャットアプリを作りたい旨を指示
  - CodeSandbox に貼り付けて実行
  - 動作確認

![](../../images/2024-12-16-23-07-37.png)

## 4. プラットフォーム

### ノーコード・ローコード開発ツール

- AI アプリ開発ツール
  - [Dify.AI · The Innovation Engine for Generative AI Applications](https://dify.ai/)
  - [Coze: Next-Gen AI App Developing Platform](https://www.coze.com/)
  - [Introducing GPTs | OpenAI](https://openai.com/index/introducing-gpts/)
- ノーコード
  - Kintone
  - Power Apps
  - Salesforce
  - Bubble
- iPaaS
  - Zapier か Make で、簡単な連携を試してもらう
  - iOS ショートカット
  - Zapier
  - Make
- IoT
  - MESH
  - toio

### プログラミング開発環境

- AI アシスト開発環境
  - v0
  - Bolt.new
- AI コードアシスタント
  - GitHub Copilot
  - Cursor
  - Continue
- オンライン開発環境
  - CodeSandbox
  - StackBlitz
  - CodePen
  - Google Colab
- デプロイ環境
  - クラウド（AWS, Google Cloud, Azure）
  - Vercel
  - Netlify

## 3 限後半

## 5. イントロダクション

- 今日、作るものの紹介
  - Dify による外部 API (Application Programming Interface) 呼び出し
  - 生成 AI (LLM: Large Language Model)によるデータの加工
  - Bolt.new による画面の作成と Dify の API 呼び出し
- 使うもの
  - Dify (dify.ai)
  - Bolt (bolt.new)
  - 外部 API
- 来週からのハッカソン予告
  - アイデアを出す
  - Dify を使って、プロトタイプ
  - Bolt.new を使って UI 改善
- API とは？
  - Application Programming Interface
  - ソフトウェア同士がやり取りをするための「窓口」や「橋渡し」のようなもの
  - ソフトウェアの部品化を促進し、説明書の役割を果たす
  - Web API: インターネットを介して動作する API のこと
- Web API の例
  - OpenWeather API: [Current weather and forecast - OpenWeatherMap](https://openweathermap.org/)
  - PokeAPI: [PokéAPI](https://pokeapi.co/)
  - Star Wars API: [SWAPI - Star Wars API Integrations - Pipedream](https://pipedream.com/apps/swapi)

* 著作物を扱うときは、著作権・商標に注意してください。
* 参考：[ご利用について｜ポケットモンスターオフィシャルサイト](https://www.pokemon.co.jp/rules/)

## 4. API 呼び出し

- Dify のエージェントで、OpenWeather API を利用
  - API 取得
  - ツールとして認証
  - エージェントで呼び出し
- カスタムツール登録
  - API の仕様
  - OpenAPI 仕様を用いたカスタムツール登録
- エージェント
  - カスタムツール呼び出し

### 4 限前半

## 5. ワークフロー

- ワークフロー
  - シンプルな入力出力で LLM 呼び出し
    - 途中結果の確認
  - 条件分岐を使った LLM 切り替え
    - 動作テスト
  - ツール呼び出し
    - OpenWeather API 呼び出し
  - コードブロックを利用
    - 必要な部分をフィルタリングして取得
    - Python で処理
  - LLM とカスタムツールとコードブロックの統合
    - 組み合わせ
    - デバッグ

## 4 限後半

## 6. Dify を API として呼び出す

- Bolt.new の登録・制限
  - 使い方
- ワークフローを API として利用
  - アーキテクチャ
  - API key を取得
  - API key の注意点
  - API の仕様を取得
- Bolt.new から API 呼び出し
  - Bolt.new から、API 呼び出し（セキュリティ的に API key はユーザー入力とする）
  - 本当は、認証の仕組みを実装する必要がある
  - セキュリティは非機能要件と呼ばれている

## 7. 🏁 まとめ

このハンズオンでは、生成 AI 活用スキルを実践的に学びました。Dify を利用した外部 API（OpenWeather API など）の呼び出しや、LLM を用いたデータ加工を体験。また、Bolt.new での UI 作成と Dify ワークフローを統合し、実際のアプリケーション構築を進行しました。API の仕組みやセキュリティの基礎知識も学び、ツールやコードを組み合わせた効率的な開発プロセスを習得しました。次回は、最後のハッカソンに取り組んでいきます。
