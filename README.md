
---
# 💫 HotNews
![License](https://img.shields.io/badge/license-Apache-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.1.0-green.svg)
![Version](https://img.shields.io/badge/Language-HSP3.6-yellow.svg)

Let's Make A News Summary！RSSリーダーと生成AIを使い、あなただけのニュースの見出しを作りましょう！

[English Version is here](README_ENG.md)

---

## ⬇️ ダウンロード
[Download](https://github.com/ABATBeliever/HotNews/releases)

---

## 🫠 主な機能
- ウィザードを通じて簡単に記事を作成
![image](https://github.com/user-attachments/assets/a474b107-946a-4f66-b9d5-88227ff9a68c)
- 豊富な出力形式(txt html md json csv)
![image](https://github.com/user-attachments/assets/406b165a-591c-4b72-b5cf-36b3fccde459)
- ヘッドレス版で操作を自動化！FTP自動アップロード機能付き
[自動アップロードの例はこちら](https://abatbeliever.net/app/HotNews/)
![image](https://github.com/user-attachments/assets/63b4b713-cc40-4b86-9c88-546285373715)

---
## 🚀 使用方法

<GUI版>
1. Releaseより、Windows_x64_Wizard_x.x.x.x.zip をダウンロード・解凍。
2. HotNews.exeからウィザードを起動。
3. APIキーと出力形式を入力。

<ヘッドレス版>
1. Releaseより、Windows_x64_HeadLess_x.x.x.x.zipをダウンロード・解凍。
2. data/config.txtにAPIキーや出力形式を入力。
3. headless.exeを起動すると自動で取得されます。

---
## 📦 仕様

| 項目           | 内容                                      |
|----------------|-------------------------------------------|
| 使用言語        | HSP 3.6 x64 (hsp3_64.as)     |
| 依存モジュール  | hspinet.dll, Windows標準RSS解釈機能 |
| AI処理         | APIが利用できる任意のAI（既定:Gemini-2.0-flash）             |
| 出力形式       | txt,html,md,json,csv     |
| その他の機能   | html版のFTPによる自動投稿(ヘッドレス版のみ)     |
| 自動化         | ヘッドレス版,data/config.txtに依存し、引数非対応。      |

---

## ⚖ ライセンス

| 対象 | ライセンス |
|------|------------|
| ソースコード（.hsp） | [Apache License 2.0](LICENSE) |
| HotNewsによる出力ファイル（HotNews*.*） | ライセンス無し* |

*本システムで利用するRSSの元記事および元メディアはそれぞれの著作権に従います。

---

## 🔐 免責事項

- このソフトウェアはAI（既定:Gemini）を用いて自動的にニュースを要約しています。
- 出力される内容の正確性、完全性、有用性について一切の保証は行いません。
- 本システムで利用するRSSの元記事および元メディアはそれぞれの著作権に従います。ご利用の際はご注意ください。

---

## 🐾 お問い合わせ・貢献

バグ報告・提案・改善PR大歓迎！  
気になる点があれば [Issues](https://github.com/ABATBeliever/HotNews/issues) または [Twitter](https://x.com/abatbeliever) にどうぞ。

---

© 2024-2025 ABATbeliever.
