# 📘 ISO 9001 品質マネジメント教材（QMS / ISO 9001:2015）

このフォルダでは、**ISO 9001:2015 に基づく品質マネジメントシステム（QMS）** の構築・運用・改善に関する教材を提供します。

EduLms全体の「教育訓練・是正・校正・構造可視化」と連動し、実務・教育現場で活用可能な記録様式・プロセス設計・理解支援を目指します。

---

## 📁 教材構成（対応条項とリンク）

| ISO条項 | 内容                     | 教材／リンク先 |
|---------|--------------------------|----------------|
| 4.1     | 組織の状況               | [`context_analysis.md`](./context_analysis.md) |
| 4.2     | 利害関係者のニーズ       | [`stakeholder_map.md`](./stakeholder_map.md) |
| 5.1/5.2 | リーダーシップ・方針     | [`top_commitment.md`](./top_commitment.md), [`quality_policy.md`](./quality_policy.md) |
| 6.1     | リスク及び機会の取扱い   | [`risk_assessment_form.md`](./risk_assessment_form.md) |
| 7.1.5   | 測定資源の管理           | [`measurement_management.md`](./measurement_management.md) |
| 7.2     | 力量の管理               | [`training/`](../training/), [`competence_matrix.md`](./competence_matrix.md) |
| 7.3     | 認識の確保               | [`awareness_checklist.md`](./awareness_checklist.md) |
| 7.5     | 文書化した情報           | [`document_control_template.md`](./document_control_template.md) |
| 8       | 製品・サービスの運用     | [`process_control.md`](./process_control.md), [`qc_tools/`](../qc_tools/) |
| 9.1     | 監視・測定               | [`measurement_management.md`](./measurement_management.md) |
| 9.2     | 内部監査                 | [`audit_report_template.md`](./audit_report_template.md) |
| 9.3     | マネジメントレビュー     | [`qms_overview.md`](./qms_overview.md) |
| 10.1-10.2 | 改善・是正             | [`nonconformity.md`](./nonconformity.md), [`corrective_actions.md`](./corrective_actions.md) |

---

## 🌀 PDCAとの関係性（概要）

| フェーズ | 内容 | 関連教材 |
|----------|------|----------|
| P（計画） | 品質方針、リスク管理、力量管理 | `quality_policy.md`, `risk_assessment_form.md`, `training_plan_template.md` |
| D（実行） | 製造・測定器管理・訓練記録 | `process_control.md`, `measurement_management.md`, `training/` |
| C（確認） | 内部監査、力量評価、測定記録 | `audit_report_template.md`, `training_record_form.md`, `competence_matrix.md` |
| A（改善） | 是正・予防・レビュー | `nonconformity.md`, `corrective_actions.md`, `qms_overview.md` |

> Mermaid構成図：[`mermaid_diagrams/qms_pdca_flow.mmd`](../mermaid_diagrams/qms_pdca_flow.mmd)

---

## 🧠 教育活用のヒント

- 条項単位で分割された教材により、**教育訓練・自己学習・記録設計が柔軟に対応可能**です。
- `training/`以下と統合して運用することで、**力量・認識・トレーサビリティの一元管理**が実現できます。
- Mermaid記法を用いたフロー図や状態遷移図により、**可視化による理解促進**が可能です。

---

## 🔗 関連ディレクトリ

- [`../training/`](../training/)：力量管理・教育計画・記録用教材
- [`../qc_tools/`](../qc_tools/)：QC七つ道具による問題解決ツール群
- [`../templates/`](../templates/)：各種様式テンプレート（Excel/Markdown）
- [`../mermaid_diagrams/`](../mermaid_diagrams/)：QMS構造可視化図（Mermaid）

---

## 📜 ライセンス

MIT License © 2025 Shinichi Samizo / Samizo-AITL
