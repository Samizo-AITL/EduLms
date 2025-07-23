# 🔗 EduController連携記録 – FSM制御・AI統合制御教材との接続

本ドキュメントは、EduControllerに収録された**制御理論・FSM・AI統合制御教材**と、  
本リポジトリ（EduLms）における**教育訓練・力量管理・是正処置支援**との接続構造を整理します。

---

## 🎯 目的

- FSMやPID・AI制御教材を「力量開発の訓練項目」としてリンク
- 制御トレーニングのPDCA管理 → `training_plan_template.md` に接続
- 是正処置後の再教育に FSM訓練シナリオを活用

---

## 📚 接続記録例

| 教材テーマ             | EduControllerリンク                                     | 対象者     | 接続ファイル例                                     |
|------------------------|--------------------------------------------------------|------------|----------------------------------------------------|
| FSM構造制御            | `EduController/part05_fsm_control/README.md`          | 制御担当   | `training_record_form.md`, `training_fsm.mmd`     |
| PID×FSMハイブリッド制御 | `EduController/part06_pid_fsm/README.md`              | AI開発技術者| `competence_matrix.md`, `pdca_template.md`         |
| LLM統合制御PoC         | `EduController/part09_llm_integration/README.md`      | 設計教育責任者 | `awareness_policy.md`, `ref_Edusemi.md`          |

---

## 🧠 活用方法

- FSMベース訓練シナリオ → `training_fsm.mmd` と連携してPDCA管理
- Edusemiで扱うセンサ応用などと接続し、**縦断的教材設計**に対応
- 是正・逸脱教育への「構造的制御の視点」導入

---

## 📎 関連リンク

- [EduController GitHub](https://github.com/samizo-aitl/EduController)
- `training_plan_template.md`
- `training_fsm.mmd`
- `nonconformity.md`
