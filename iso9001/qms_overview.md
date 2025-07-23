# 📘 QMS全体構成（ISO 9001:2015 概要とPDCA）

本ドキュメントは、ISO 9001に基づく**品質マネジメントシステム（QMS）**の全体像を構造的に整理し、  
EduLms教材全体の中でPDCAとの接続位置を可視化するための要約ページです。

---

## 🌀 品質マネジメントの基本構造：PDCA

| フェーズ | 対応項目           | 関連文書例                      |
|----------|--------------------|---------------------------------|
| P（計画） | 品質方針、目標設定、リスク機会 | `qms_overview.md`, `training_plan_template.md` |
| D（実行） | 製品提供、教育訓練、測定機器 | `process_control.md`, `measurement_management.md` |
| C（確認） | 監査、測定、力量評価          | `audit/`, `training_record_form.md` |
| A（改善） | 是正・予防措置、レビュー       | `nonconformity.md`, `corrective_actions.md` |

---

## 🧩 教育構造としての接続

- `training/` → 7.2 力量 / 7.3 認識
- `qc_tools/` → 製造工程の統計管理
- `mermaid_diagrams/qms_pdca_flow.mmd` → PDCAモデル可視化

---

## 📎 関連リンク

- [ISO 9001:2015 – Clause 4–10](https://www.iso.org/standard/62085.html)
- [training/competence_matrix.md](../training/competence_matrix.md)
- [qc_tools/qc7tools_overview.md](../qc_tools/qc7tools_overview.md)
