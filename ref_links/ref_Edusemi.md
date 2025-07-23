# 🔗 Edusemi連携記録 – 技術教材と訓練管理の接続（ISO 9001:2015 7.2対応）

本ドキュメントは、Edusemiに収録された技術教材と、  
本リポジトリ（EduLms）における訓練計画・力量記録との**リンク構造**を定義・管理します。

---

## 🎓 目的

- 再利用可能な教材を訓練計画・実施・評価記録とリンク
- 教育訓練（7.2）に教材コンテンツを直接接続することで、教育PDCAを実現
- Edusemiの章構成と、訓練記録の参照性を向上させる

---

## 📚 接続記録例

| 技術テーマ            | 教材リンク                                                 | 対象者     | 接続先記録ファイル                         |
|-----------------------|------------------------------------------------------------|------------|--------------------------------------------|
| 半導体の信頼性評価     | `Edusemi/basics/ch4_mos_reliability.md`                   | 設計・品質 | `training_plan_template.md` / `training_record_form.md` |
| D値と歩留まり         | `Edusemi/basics/ch6_defect_density.md`                    | 品質保証   | `competence_matrix.md`                     |
| 高耐圧デバイス（SiC） | `Edusemi/plus/materials/sic_properties.md`                | 開発技術者 | `awareness_policy.md`                      |
| 教育演習全般           | `Edusemi/README.md`                                        | 全般       | 各訓練ファイルから参照可                   |

---

## 🧠 使用方法

- 訓練計画や力量マトリクスにおける**技術教育項目の教材リンク**として活用
- Mermaid/FSMで可視化された訓練プロセスにリンク埋め込み可能
- Edusemi 側からも「訓練ログへの逆リンク」設定を推奨

---

## 🔄 推奨保存・管理方法

- このファイルは `ref_links/` に保持し、教材更新時に参照先を更新
- Gitで教育計画と教材改訂を履歴管理

---

## 📎 関連リンク

- [Edusemi GitHub](https://github.com/samizo-aitl/Edusemi)
- `training_plan_template.md`
- `training_record_form.md`
- `competence_matrix.md`
