# MyMeetNote

**ローカルAI議事録ジェネレーター / Local AI Meeting Minutes Generator**

社内会議の録音・音声ファイルから、AIが自動で議事録を生成するデスクトップアプリです。
音声データはすべてローカル処理 — クラウドに会議内容を送信しません。

---

## ダウンロード / Download

👉 [最新バージョンのリリースページ](https://github.com/nthsfdc/MyMeetNote-Releases/releases/latest)

---

## 機能 / Features

- **会議録音** — マイク・システム音声・両方から録音
- **音声インポート** — 音声/動画ファイル (mp3, mp4, wav, m4a...) をインポート
- **テキストインポート** — Slack/Teams等からコピーしたトランスクリプトを処理
- **AIトランスクリプト** — Deepgram nova-3 による高精度文字起こし（日本語・英語・ベトナム語）
- **AI議事録生成** — GPT-4o による構造化議事録（概要・議論・結論・Todo）
- **文書化** — 議事録とは別に、文章形式のドキュメントを自動生成
- **チャット検索** — 全録音セッションをまたいだAIチャット検索（日付フィルター対応）
- **多言語UI** — 日本語 / English

---

## インストール方法 / Installation

1. 下記リリースページから `MyMeetNote Setup x.x.x.exe` をダウンロード
2. インストーラーを実行 → インストール完了
3. デスクトップまたはスタートメニューから起動

> **注意**: Windows SmartScreen の警告が出る場合は「詳細情報」→「実行」をクリックしてください。

---

## 必要なAPIキー / Required API Keys

初回起動後、設定画面で以下のAPIキーを入力してください：

| サービス | 用途 | 取得先 |
|---------|------|--------|
| **Deepgram** | 音声文字起こし (STT) | https://deepgram.com |
| **OpenAI** | 議事録生成・チャット | https://platform.openai.com |

APIキーはOSキーチェーン（Windows Credential Manager）に安全に保存されます。

---

## 動作環境 / System Requirements

- Windows 10 / 11 (x64)
- インターネット接続（APIコール用）

---

## Changelog

See [releases](https://github.com/nthsfdc/MyMeetNote-Releases/releases) for version history.
