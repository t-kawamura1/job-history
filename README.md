# 職務経歴書

## 個人データ
| 項目 | 内容                                                   |
| ---- | ------------------------------------------------------ |
| 氏名 | 河村　智之                                             |
| X    | [@kossari](https://twitter.com/kossari)                |
| Blog | [ベーコンになります。](https://itiiki.hatenablog.com/) |
| Zenn | [@tkawa01](https://zenn.dev/tkawa01)                   |

## 職務要約
- 2021年11月、株式会社Sales Naviにソフトウェアエンジニアとして入社
    - 2年半の間、自社製品である営業組織向けSaaS「Sales Navi」の開発（詳細設計・実装・運用保守）に従事
    - エンジニア未経験かつフルリモートワークの挑戦的なキャリアスタート
    - チームメンバー・上司と綿密にコミュケーションをとりながら日々の開発業務を遂行
    - より良い設計と実装を模索し、プロダクトの迅速な機能提供と品質向上に努めた

## 活かせる経験・知識・技術
- TypeScriptの型を活用したモデリング
- コンポーネント設計・状態管理に関する知見
- 漸進的なリファクタリングによるアプリケーションの機能改善
- 仕様策定前後のドキュメント作成
- 関数・クラス・コンポーネントの単体テスト

## スキル
### 言語
| 名称       | バージョン      | 実務使用歴 | スキル感                                                   |
| ---------- | --------------- | ---------- | ---------------------------------------------------------- |
| TypeScript | 4.9             | 2年半      | 一番手足として扱える言語。型でモデリングを考えるのが楽しい |
| Java       | 17              | 数か月     | コードリーディング・簡単なCRUDの実装ができる               |
| HTML       | Living Standard | 2年半      | 日常業務に支障なし。a11y等の知見は少ない                   |
| CSS        | 3               | 2年半      | Sass（SCSS）で実装ができる                                 |

### フレームワーク
| 名称             | バージョン | 実務使用歴 | スキル感                                                   |
| ---------------- | ---------- | ---------- | ---------------------------------------------------------- |
| Angular　        | 12-16      | 2年半      | ・1からのプロジェクト作成<br>・バージョンアップデート随時実施<br>・おおよその機能～最新機能まで扱える |
| Angular Material | 12-16      | 2年半      | ライブラリを活用したコンポーネント～ページ作成が可能       |
| Spring Boot      | 17         | 数か月     | コードリーディング・簡単なCRUDの実装ができる               |

### テストフレームワーク
| 名称             | 実務使用歴 | スキル感                                                         |
| ---------------- | ---------- | ---------------------------------------------------------------- |
| Jasmine　        | 2年半      | 実装とセットで単体テストを書いていたため、ひととおりの記述が可能 |
| JUnit5           | 数か月     | 仕様は深掘りしていないが、見よう見まねで書けるレベル             |

### その他業務で使用していたもの
- VSC：Git, GitHub
- インフラ： Docker, AWS, WSL2
- 開発手法：アジャイル, スクラム
- ドキュメント：MkDocs, Docusaurus
- タスク管理：Jira

### 実務以外で経験のあるもの
カッコ内はバージョン
- Vue.js (2)
- Ruby on Rails (5-6)
- Jest

## 職務経歴
### 2021/11 - 現在　[株式会社Sales Navi](https://www.salesnavi.co.jp/)（現職）
- セールスイネーブルメント（営業におけるナレッジの標準化、誰もが成果を出せるチームをつくる総合的な取り組み）を実現するSaaS「**[Sales Navi](https://lp.salesnavi.co.jp/)**」の開発
    - アプリケーションの詳細設計・実装、運用保守を担当
    - フロントエンドをリードする立場として、以下の改善施策を立案・実施
        - TypeScriptにおける値クラスの欠点への代替策として、[Branded Type](https://zenn.dev/okunokentaro/articles/01gmpkp9gzfyr1za5wvrxt0vy6)を導入
        - 未整備だったエラーハンドリングの方針を策定し、簡易な[Result型](https://zenn.dev/koudai/articles/ff415ca6755054)を導入
        - [軽量DDD](https://zenn.dev/backstage/articles/8e7a574d8c26a1#%E6%88%A6%E8%A1%93%E7%9A%84%E8%A8%AD%E8%A8%88)に陥っていたアーキテクチャを見直し、層ごとの役割を再規定・不要なパターンを廃止
        - バックエンドAPIとの疎通確認やエラーケース検証のため、[Mock Service Worker](https://mswjs.io/)を導入
        - フレームワークのアップデートを随時実施し、その手順をドキュメント化
        - フロントエンドの進行中・未着手タスクを整理・共有し、メンバー間のタスク割り振りを容易に

### 2016/4 - 2021/3　京都市役所
- 建築職として以下の業務を通じ、歴史都市・京都のまちづくりに貢献
    - 2016/04 - 2018/03 建築指導課
        - 市民・事業者間の建築紛争調整・調停
        - 建築協定を活用した住民主体のまちづくり支援・連絡協議会運営
    - 2018/04 - 2021/03 景観政策課
        - 景観法・条例に基づく建築物のデザイン誘導・認定
- 日々の窓口・電話応対を通じ、多様な主体との意見調整・交渉方法を学ぶ

## やりたいこと・興味のあること
- フロントエンドの深化
- バックエンドも習得していきた
- 関数型プログラミングを学ぶ
- 対人スキルも向上させる（対顧客・社内マネジメント）
- よりよいチーム開発の模索

## 仕事のスタンス・大切にする価値観
- 常に改善・向上を試みる
    - 過去の自分のコードよりもきれいに
    - 書籍等から学んだ手法を取り入れる
    - 言語やフレームワークの新機能を活用してより良い解決を目指す
- チームで開発を進める
    - 言語・フレームワークの新機能に関する知識共有
    - 新たに導入した設計や仕組みのドキュメント等での共有
    - チームで議論して仕事を進め、改善していく
- 仕事を楽しむ
    - 成長は喜び
    - 困難を挑戦と捉え前向きに取り組む
    - 自分の仕事で他者を楽しませたい
