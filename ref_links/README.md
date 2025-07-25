# 📚 ref_links ディレクトリ

このディレクトリは、EduLms システム内で使用される**参照ドキュメント**や**テンプレート**を集約したリソースハブです。  
教育設計者・監査担当者・訓練責任者が共通で参照できる構造資料を収録し、教材・訓練管理の標準化を支援します。

---

## 📁 各ファイルの概要

| ファイル名 | 内容概要 |
|-----------|----------|
| [`audit_report_template.md`](./audit_report_template.md) | 内部監査または教育監査の報告書テンプレート。ISO 9001:2015の7.2/7.3にも準拠。 |
| [`measurement_fsm.mmd`](./measurement_fsm.mmd) | 教育プロセスまたは測定管理に関する状態遷移図（Mermaid記法による FSM記述）。 |
| [`ref_EduController.md`](./ref_EduController.md) | 教育用制御系モジュール（EduController）の仕様・参照資料。 |
| [`ref_EduMecha.md`](./ref_EduMecha.md) | 教育用メカトロ教材（EduMecha）の仕様・構造概要。 |
| [`ref_Edusemi.md`](./ref_Edusemi.md) | 教育用半導体教材（Edusemi）の設計方針・参照アーキテクチャ。（※現在記述中） |

---

## ✅ 利用目的

- 教材開発における共通参照仕様の共有
- 教育訓練記録や監査報告のテンプレート化
- 各モジュール（制御・メカ・半導体）の構造連携設計のガイド

---

## 📌 運用メモ

- Mermaid形式の FSM は、[Mermaid Live Editor](https://mermaid.live) 等でレンダリングして確認してください。
- `ref_*.md` 系は教材設計における「構造参照点」として使用されます。
- [`audit_report_template.md`](./audit_report_template.md) は、[`training_plan_template.md`](../competence/training_plan_template.md) と併せて活用してください。

---

## 🔗 関連ディレクトリ

- [`../competence/`](../competence/)  
  力量管理・教育計画・訓練記録に関するテンプレート群（例：`competence_matrix.md`, `training_plan_template.md`）

- [`../01_parametric_basics/`](../01_parametric_basics/)  
  基礎教材群：パラメトリック設計トレーニング（ブロック・ブラケット等）

- [`../mechatronic/`](../mechatronic/)  
  メカトロ教材統合構成（例：EduController / EduMecha の連携設計）

---
