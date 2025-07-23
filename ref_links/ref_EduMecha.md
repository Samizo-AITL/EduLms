# 🔗 EduMecha連携記録 – 測定器管理・設計教育との接続

本ドキュメントは、EduMechaで構成された**構造設計・測定器取扱い・制御実装教材**と、  
本リポジトリ（EduLms）における**校正訓練・力量記録・手順書管理**の接続を定義します。

---

## 🧭 目的

- ISO 9001の7.1.5（測定機器）と 8.5（運用制御）への**技術教材的補完**
- 測定器教育を `training/`, `iso9001/` の記録ファイルとリンク
- EduMecha側で図面記載された計測機器を文書管理と接続

---

## 📚 接続記録例

| 教材テーマ           | EduMecha教材リンク                                           | 対象者     | 接続ファイル例                                   |
|----------------------|--------------------------------------------------------------|------------|--------------------------------------------------|
| 測定器の実装構造     | `EduMecha/docs/section2_sensor_layout.md`                   | 技術・製造 | `measurement_management.md`, `training_plan_template.md` |
| 校正作業とFSM制御    | `EduMecha/docs/fsm_calibration_sequence.md`                 | 品質保証   | `measurement_fsm.mmd`, `traceability_register.md`        |
| CAD図面と検査設計     | `EduMecha/models/assy_caliper_mecha.md`                     | 設計担当   | `document_control_template.md`, `training_record_form.md`|

---

## 🧠 使用上のポイント

- FSMと測定器の接続教材を、校正・再訓練・評価記録にリンク
- Mermaid図にて制御連動／教育フローを視覚化可能
- EduMecha内の設計図／仕様に「測定器教育あり」タグを追加すると効果的

---

## 📎 関連ファイル・接続

- `measurement_management.md`（測定管理方針）
- `traceability_register.md`（トレーサビリティ記録）
- `training/` 以下の教育訓練テンプレート群
- [EduMecha GitHub](https://github.com/samizo-aitl/EduMecha)
