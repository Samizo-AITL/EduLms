# ⚠️ FMEA（故障モード影響解析）教材

本フォルダでは、品質管理やリスク評価のための手法である **FMEA（Failure Mode and Effects Analysis）** に関する教材とテンプレートを提供します。

FMEAは、**潜在的な故障モード・影響・原因・検出性を系統的に分析**し、対策優先順位を決定するための有力なツールです。製造業・医療・自動車・ITなど幅広い分野で活用されています。

---

## 📝 FMEAとは？

- Failure Mode（故障モード）…どのような壊れ方をするか？
- Effects（影響）…その故障が引き起こす問題は？
- Analysis（解析）…原因、検出方法、対策、リスク評価（RPN）などを洗い出し

FMEAは「予防的な品質管理」を支える **リスクの可視化と優先順位づけの手法** として知られています。

---

## 📁 フォルダ構成

```plaintext
fmea/
├── samples/                      # 記入済みサンプル（Excel / Markdown）
│   ├── fmea_example.xlsx         # 実務を想定した加工工程のFMEA例
│   └── fmea_example.md           # 同内容をMarkdown形式で記載
├── templates/                    # 空テンプレート（Excel / CSV）
│   └── fmea_template.xlsx        # RPN自動計算式入りのFMEA用紙
└── README.md                     # 本ファイル
```

---

## ✅ RPNとは？

| 項目 | 意味         | 評価尺度（例）         |
|------|--------------|------------------------|
| S    | 重大度（Severity） | 1〜10（顧客への影響）     |
| O    | 発生頻度（Occurrence） | 1〜10（どれくらい起こるか） |
| D    | 検出性（Detection） | 1〜10（検出のしやすさ）   |
| RPN  | リスク優先数（S×O×D） | 1〜1000以上（高いほど危険）|

> 📌 RPNが高い項目は優先的に改善が必要です。

---

## 💡 教育活用ポイント

- Excelテンプレートは自動でRPN計算が可能。対策前後の比較記入にも対応。
- サンプルには「加工工程」「検査漏れ」などの事例を記載。現場教育にも活用可能。
- 他教材との連携がしやすく、特に以下と接続可能：

---

## 🔗 関連教材リンク

- [`iso9001/risk_assessment_form.md`](../../iso9001/risk_assessment_form.md)：定性的リスク評価との違いを理解  
- [`training/`](../../training/)：FMEA記入演習や力量教育の一部として活用  
- [`templates/`](../../templates/)：文書管理やPDCAテンプレートとの統合管理  

---

## 🧠 実務展開ヒント

- 設計FMEA（DFMEA）、工程FMEA（PFMEA）、サービスFMEA など、用途別に応用可能
- クロスファンクショナルチーム（設計・製造・品質）による検討が効果的
- MermaidなどでFSM（状態遷移）図と連動すると、プロセス改善への展開も可能

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo / Samizo-AITL
