<div align="center">

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/logo.svg" width="100" height="100" alt="AC-Stride ロゴ">

# AC-Stride

**問題文も、コードも、テストも。VS Code で。**

[公式サイト](https://acstride.com/ja) · [ダウンロード](https://github.com/acstride-labs/codeforces-workbench/releases) · [ドキュメント](https://github.com/acstride-labs/codeforces-workbench#readme) · [ディスカッション](https://github.com/orgs/acstride-labs/discussions)

[English](https://github.com/acstride-labs/.github/blob/main/profile/README.md) | [简体中文](https://github.com/acstride-labs/.github/blob/main/profile/README.zh-CN.md) | **日本語** | [Русский](https://github.com/acstride-labs/.github/blob/main/profile/README.ru.md)

<img src="https://raw.githubusercontent.com/acstride-labs/.github/main/profile/assets/workflow.svg" width="100%" alt="AC-Stride の流れ：問題の取り込み、問題文の確認、コーディング、テスト">

</div>

## いつものエディターを競技プログラミングの作業場に

AC-Stride は Codeforces のコンテストや日々の練習のためのツール集です。問題を取り込み、得意な言語で解答し、問題文の隣でテストできます。

| | できること |
| --- | --- |
| **取り込んで読む** | Codeforces のコンテスト全体や単独の問題を取り込むほか、ローカル問題を作成できます。問題文とサンプルは自動で取得します。 |
| **得意な言語で書く** | C++、Python、Java、Kotlin に対応。言語ごとにソースとひな形を管理し、環境をチェックできます。VS Code の拡張機能やショートカットもそのまま使えます。 |
| **テストして比べる** | 公式サンプルと自作ケースを実行し、標準出力、エラー、最初に異なる出力を確認できます。時間制限と実行の中止にも対応します。 |
| **コンテストを追う** | 提出履歴、判定結果、順位表を確認できます。コードをコピーして公式の提出ページを開く方法と、ログイン後に確認を挟んで直接提出する方法があります。 |
| **必要なときに翻訳する** | 自分の AI サービスに接続し、問題文を手動または自動で翻訳できます。翻訳先言語、プロンプト、ローカル LRU リクエストキャッシュを設定できます。 |

インターフェースは英語、簡体字中国語、日本語、ロシア語に対応しています。

## はじめ方

1. **拡張機能をインストール**：[Releases](https://github.com/acstride-labs/codeforces-workbench/releases) から環境に合う VSIX をダウンロードし、VS Code で **Extensions: Install from VSIX...** を実行します。
2. **環境を確認**：信頼できるローカルフォルダーを開き、**AC-Stride 設定**で既定の言語とコンパイラ・実行環境を確認します。
3. **問題に取り組む**：コンテストや問題を取り込むか、ローカル問題を作成します。問題文を開いてコードを書き、テストを実行してください。

Codeforces 用ツールは拡張機能に同梱されています。CF Tool の別途インストールは不要です。解答用のコンパイラや実行環境は別途ご用意ください。Java には JDK、Kotlin には追加で Kotlin コンパイラが必要です。

> **プレビュー版**：ログインと自動提出は実験的な機能で、Codeforces のサイト認証により利用できない場合があります。公開問題の取得とローカル練習にはログイン不要です。自動提出では必ず確認を求めます。

## プロジェクト

| プロジェクト | 役割 |
| --- | --- |
| [VS Code Extension](https://github.com/acstride-labs/codeforces-workbench) | 問題文、解答、ローカルテスト、コンテスト情報を扱う作業場。 |
| [CF Tool](https://github.com/acstride-labs/acstride-cf-tool) | 問題の取得、コンテスト情報、提出操作を担う Codeforces クライアントと CLI。 |
| [Website](https://github.com/acstride-labs/acstride-web) | 製品情報、ダウンロード、入門ガイド。 |

## 質問・アイデア・不具合

- **使い方の質問**：[Q&A](https://github.com/orgs/acstride-labs/discussions/categories/q-a) へ。
- **改善のアイデア**：[Ideas](https://github.com/orgs/acstride-labs/discussions/categories/ideas) で共有してください。
- **不具合の報告**：[拡張機能](https://github.com/acstride-labs/codeforces-workbench/issues)、[CF Tool](https://github.com/acstride-labs/acstride-cf-tool/issues)、[公式サイト](https://github.com/acstride-labs/acstride-web/issues)の該当リポジトリに Issue を作成してください。再現手順、環境とバージョン、機密情報を除いたログが役立ちます。
- **更新情報**：[Announcements](https://github.com/orgs/acstride-labs/discussions/categories/announcements) と[更新履歴](https://github.com/acstride-labs/codeforces-workbench/blob/master/CHANGELOG.md)をご覧ください。
