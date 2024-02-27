# JCV Cloud：究極の顔認識ソリューション

[English readme](README.md) | [ホームページ](https://www.japancv.co.jp/)

JCV Cloudは、GitHubを通じて無料で提供される、openAPIベースの顔認識サービスです。このクラウドベースのサービスは、インターネットに接続されたどんなデバイスでも使えます。設定や使用に機械学習の専門知識は一切不要です。

<p align="center">
    <a target="_blank" href="https://cloud.japancv.co.jp/en/signin">
        <img src="https://www.japancv.co.jp/wp/wp-content/themes/japancv/assets/images/company/img_03.png" alt="JCV-logo" height="250px"/>
    </a>
</p>

<p align="center">
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/license-Apache2.0-green" alt="License" />
  </a>
</p>

## 主な特長

- **REST API**: JCV Cloudは、顔認識、顔検証、顔検出、ランドマーク検出、マスク検出、頭部姿勢検出、年齢と性別の識別など、多岐にわたるサービスをREST APIを通じて提供します。
- **ロール管理システム**: 顔認識サービスのセキュリティを強化し、アクセス権を誰に与えるかを管理します。
- **多様なモデルサポート**: CPUでもGPUでも動作可能。あなたの好みに合わせて様々な認識モデルを選べます。
- **最先端のライブラリ**: JCV Cloudは最先端の技術を活用し、その分野でのNISTランキング2位にランクされています。

## なぜJCV Cloudを選ぶのか？

JCV Cloudは、個人から組織まで、多岐にわたるニーズに応える堅牢なソリューションです。ローカルサーバーやクラウドのどちらでもデプロイできる柔軟性、直感的でユーザーフレンドリーな操作性を提供します。高品質の顔認識ソリューションが必要なら、JCV Cloudが最適な選択肢です。

## ニュースとアップデート
JCV Cloudの最新情報は[更新履歴](https://docs.cloud.japancv.co.jp/changelog)ページでチェックしてください。

### JCV 開発ブログ
開発スタッフによる公式ブログです。

JPN | https://www.japancv.co.jp/news/11174/

ENG| https://www.japancv.co.jp/en/news/11177/ 

## クイックスタート
早速始めたい方は、[クイックスタートガイド](docs/QuickStart_Anysee_jp.md)に従って設定を進めてください。また、[対話型ドキュメンテーション](https://docs.cloud.japancv.co.jp/reference/anysee-create-entity)や[モデルエクスプローラ](https://cloud.japancv.co.jp/en/model-explorer/detection)で実際の操作を体験することもできます。

## ドキュメンテーション
アプリケーションの詳細、機能の説明、使い方、技術要件については[完全なドキュメンテーション](https://docs.cloud.japancv.co.jp/docs)を参照してください。

## 例
ここにいくつかの例を用意しています。ぜひ手を動かしてみてください！
### 顔検出の例
このプロジェクトは、任意の画像内のすべての顔を検出し、その年齢、性別、感情、ヘアスタイルなどを予測します。[ノートブック](examples/01_Face_detection_example/face_detection.ipynb)や[Google Colab](https://colab.research.google.com/drive/1MT56jHH0_ZCxvS09-ojF8jiT3eV6Ik_l?usp=sharing)をチェックしてみてください。

<img src="https://github.com/japancv/JCV-Cloud-Face-Recognition/blob/main/examples/01_Face_detection_example/result2.jpg?raw=true" alt="sample" width="200"/>

### 顔品質登録検索の例
カスタマイズ可能な品質閾値を通過した登録顔を探すためのこのプロジェクトの[ノートブック](examples/02_Face_quality_register_search_example/face_quality_register_search.ipynb)をチェックしてみてください。

### 基本的な顔認識の例
このプロジェクトは、あなたの顔が登場するすべての箇所を検出してフォトアルバムを整理します。[ノートブック](examples/03_%20Face_Recognition_example/face_compare.ipynb)または [Google Colab](https://colab.research.google.com/drive/1AN4chF-8UhVyVLy-jR_U8NUsqfDhAjBd?usp=sharing)をチェックしてみてください。

<img src="https://github.com/japancv/JCV-Cloud-Face-Recognition/blob/main/examples/03_%20Face_Recognition_example/compared_2.jpg?raw=true" alt="sample" width="400"/>

## 貢献
JCV Cloudの改善にご協力いただける方は、[貢献ガイドライン](docs/Contribution_guidelines.md)をご覧ください。

## ライセンス
JCV Cloudは[Apache 2.0ライセンス](https://www.apache.org/licenses/LICENSE-2.0.html)でライセンスされています。詳細はライセンスページをご覧ください。

## サポート
サポートが必要な場合や問題が発生した場合は、[サポートページ](https://docs.cloud.japancv.co.jp/docs/anysee-faq#q3-how-can-i-contact-support)をご覧いただくか、GitHubで[問題を報告](https://github.com/japancv/JCV-Cloud-Face-Recognition/issues)してください。

JCV Cloudで顔認識の新しい世界を体験しませんか？今すぐ始めてみてください。顔認識の未来へようこそ！

アプリケーションに関する詳細な情報、その機能の完全な説明、使用方法、技術要件については、[ドキュメンテーション](https://docs.cloud.japancv.co.jp/docs)をご覧ください。
