# 📊 Pareto 図リソース（qc_tools/pareto）

このディレクトリは、**パレート図（Pareto Chart）**を活用した教育訓練・品質改善活動を支援するための  
テンプレート・サンプル・自動化資料を格納しています。

パレート図は、「重要少数・些少多数（80:20の法則）」に基づく課題分析の基本手法です。  
本資料は、教育現場・QC活動・トラブル分析における視覚的判断支援を目的としています。

---

## 📁 ディレクトリ構成

```plaintext
pareto/
├── samples/               # パレート図のサンプル（Markdown / PNG / Excel）
│   ├── pareto_example.md  # Mermaid記法によるパレート例
│   └── pareto_chart.xlsx  # Excel形式の入力・自動グラフ
├── templates/             # 汎用テンプレート（CSV / Excel）
│   └── pareto_template.xlsx
└── README.md              # このファイル
```

---

## 📂 samples/ サンプル

| ファイル名 | 内容 |
|------------|------|
| [`pareto_example.md`](./samples/pareto_example.md) | Mermaid記法を用いたパレート図サンプル。Git上でも視覚化可能。 |
| [`pareto_chart.xlsx`](./samples/pareto_chart.xlsx) | 頻度データを入力するだけで、パレート図が自動生成されるExcelサンプル。 |

---

## 📂 templates/ テンプレート

| ファイル名 | 内容 |
|------------|------|
| [`pareto_template.xlsx`](./templates/pareto_template.xlsx) | 汎用パレート分析テンプレート。QCサークル活動やトラブル報告に利用可。 |

---

## ✅ 利用目的

- 教育訓練における**トラブル分類・影響度分析**の視覚化  
- QC七つ道具の一環としてのパレート手法トレーニング  
- 改善活動（PDCA）における優先度判断の補助資料  

---

## 🛠️ 補足情報

- Excel形式のテンプレートは、**カテゴリと件数を入力するだけで**グラフが更新される構造です。  
- Mermaid形式の例は、[Mermaid Live Editor](https://mermaid.live/) 等でも視覚化できます。

---

## 🔗 関連リンク・セクション

- [`../fishbone/`](../fishbone/) – 特性要因図との併用で原因分析の幅を拡張  
- [`../../mermaid_diagrams/`](../../mermaid_diagrams/) – Mermaid図で可視化する教育教材の統合例  
- [`../../templates/`](../../templates/) – PDCAやトレーサビリティとの構造連携に活用  

---
