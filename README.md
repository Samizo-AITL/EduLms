# 🎓 EduLms - Integrated Learning Management System for Structured Education and Quality Practice

**EduLms** は、ISO 9001 / ISO 14001 / QCツール / 教育訓練 / FSM構造可視化を統合し、  
**教育の再利用 × 記録テンプレート × 管理プロセス可視化**を支援する  
軽量かつ構造的な **LMS（Learning Management System）教材リポジトリ**です。
> 🇯🇵 このページは日本語版です ｜ 🇺🇸 [English version available here](./README_en.md)

> 💡 **LMS（Learning Management System）とは？**  
> 単なる訓練ではなく、**教材の構成管理・訓練計画・力量記録・進捗評価を含む学習の設計と運用基盤**を意味します。  
> EduLmsは、これをMarkdownとGitで構造化・可視化します。

## 📦 機能 / Features

- ✅ ISO 9001:2015 / ISO 14001:2015 の各章に対応した教材・テンプレート
- ✅ 教育訓練（7.2）・認識向上（7.3）・力量トレーサビリティを支援
- ✅ PDCAテンプレ、監査・是正・校正のFSM可視化
- ✅ Edusemi / EduMecha / EduController と連携した再利用教材構造
- ✅ Git + Mermaid + Markdown による構成管理と学習プロセス記録

---

## 📁 ディレクトリ構成

```plaintext
EduLms/
├── iso9001/              # 品質管理（PDCA、是正、校正など）
├── iso14001/             # 環境管理（環境方針、リスク、法令対応）
├── training/             # 教育訓練・力量・認識向上教材
├── qc_tools/             # QC7ツール：パレート・管理図など
├── templates/            # 様式テンプレート：PDCA・記録・文書管理
├── mermaid_diagrams/     # FSM・PDCAなどのプロセス図
└── ref_links/            # 他教材（Edusemi等）との接続記録　
```

---

## 📂 フォルダ別リンク一覧 / Directory Links

| フォルダ名 | 内容 | リンク |
|------------|------|--------|
| `iso9001/` | 品質管理（PDCA、是正、校正、監査 等） | [📁 iso9001](./iso9001/) |
| `iso14001/` | 環境管理（環境方針、法令対応、リスク管理 等） | [📁 iso14001](./iso14001/) |
| `training/` | 教育訓練、認識向上、力量記録 等 | [📁 training](./training/) |
| `qc_tools/` | QC七つ道具（パレート図、ヒストグラム、管理図 等） | [📁 qc_tools](./qc_tools/) |
| `templates/` | 記録様式、PDCAテンプレート、文書管理フォーム 等 | [📁 templates](./templates/) |
| `mermaid_diagrams/` | FSM図、PDCAプロセス図、構造可視化用Mermaidファイル群 | [📁 mermaid_diagrams](./mermaid_diagrams/) |
| `ref_links/` | 他教材（Edusemi, EduController 等）とのリンク・再利用記録 | [📁 ref_links](./ref_links/) 

---

## 🔗 関連プロジェクト / Related Projects

| プロジェクト     | 内容                                               |
|------------------|----------------------------------------------------|
| [Edusemi](https://github.com/samizo-aitl/Edusemi)         | 半導体・材料工学教材（技術教育との接続）               |
| [EduMecha](https://github.com/samizo-aitl/EduMecha)       | 測定器・構造設計教育教材（校正・図面連携）              |
| [EduController](https://github.com/samizo-aitl/EduController) | FSM制御・AI訓練教材（訓練プロセスとリンク）             |

---

## 🧠 教育と構造設計の接続

- **FSM可視化**：訓練・監査・校正などの教育プロセスを状態遷移で記述
- **教材リンク構造**：Edusemiや他教材との双方向リンクを `ref_links/` に記載
- **PDCA管理**：是正処置・再訓練・文書改訂を記録テンプレで一貫管理

---

## 📜 ライセンス / License

MIT License  
Copyright (c) 2025  
Shinichi Samizo / Samizo-AITL

---

## 👤 執筆者情報 / Author

**三溝 真一（Shinichi Samizo）**  
- 信州大学大学院電気電子工学　修了  
- 元 セイコーエプソン株式会社 技術者（1997年〜）  

📌 **経験領域**：
- 半導体デバイス(ロジック/メモリ/高耐圧混載)  
- 薄膜ピエゾアクチュエータ  
- PrecisionCoreプリントヘッド製品化  

📬 **連絡先**
- ✉️ Email: [shin3t72@gmail.com](mailto:shin3t72@gmail.com)  
- 🐦 X (Twitter): [https://x.com/shin3t72](https://x.com/shin3t72)  
- 💻 GitHub: [https://samizo-aitl.github.io/](https://samizo-aitl.github.io/)

---

## 💬 フィードバック・ご意見募集

本リポジトリ「EduLms」は、現場の教育訓練・品質管理・構造的な教材展開を支援する目的で設計されています。

- 実際の訓練・監査・校正業務での活用アイデア
- テンプレートやFSM図の改善点
- 他教材（Edusemi, EduMecha など）との連携要望
- GitHub PagesやMarkdownによる運用へのご質問

など、どんな内容でも構いません。  
以下の Discussion にてお気軽にコメントをお寄せください：

👉 [Discussions フィードバックスレッド](https://github.com/Samizo-AITL/EduLms/discussions)

皆さまからのご意見を教材改善に活かしてまいります。

---
