---
id: topic-ai
type: topic
title: AI開発
updated: 2026-09-06
sources:
  - https://global.toyota/en/newsroom/corporate/44256155.html
  - https://xtech.nikkei.com/atcl/nxt/column/18/03367/082900038/
  - https://www.nikkei.com/article/DGXZQOUC154MR0V10C26A7000000/
  - https://global.toyota/pages/global_toyota/ir/library/annual/2025_001_integrated_jp.pdf
  - https://global.toyota/pages/global_toyota/sustainability/report/sdb/sdb26_jp.pdf
tags: [ai, sdv, woven, training]
---

# AI開発（TRシリーズ訓練トピック）

## 学習目標
1. トヨタのAIを「車載」「工場」「都市」「経営」の4層で分類できる。
2. SDV / E2E自動運転の投資論理を説明できる。
3. 生成AIを使っても公式情報と伝聞を混同しない。

## 4層アーキテクチャ
| 層 | 中核 | 2026年時点の事実 |
|---|---|---|
| 車載 | E2E自動運転・Arene | L2++を2028年量産、L4商用を2030年まで。L2++とL4で中核モデル共通化 |
| 工場 | Digital KAIZEN / ロボット | 混流生産ラインでバッファ最適化。NVIDIAと工場ロボットAI協業 |
| 都市 | Woven City AI Vision Engine | VLM。インフラカメラで視認外の衝歩者を予測し警告。SDK外販 |
| 経営 | Akio AI等 | 会長の意思決定スタイルを学習した内部AI。次世代育成用 |

## 教材ケース
1. **共通モデル戦略**: L2++とL4で同じE2E核を使い投資を売る。
2. **人補完AI**: Vision Engineは代替ではなく直感補完が公表旨趣。
3. **プライバシー**: Data FabricをESG・ガバナンス課題と接続させる。

## 統合報告2025のAIガバナンス（p153-154）
出典: [[sources/integrated-report-2025-pass3]] / [[sources/integrated-report-2025-pass4]]。
AI基本方針、開発者/利用者向けAIガイドライン、AIガバナンス推進会議。情報セキュリティの第三者評価ベースはNIST SP800-82/53、ISO 27001/27002、IEC 62443。
GAIA 11カテゴリー（IR2025 p153注）:
1. AD/ADAS
2. AIエージェント
3. モビリティス3.0
4. ソフトウエア効率化
5. カスタマーリレーション
6. ノウハウ伝授
7. 材料設計
8. 製造
9. 業務効率化
10. ロボティクス
11. 車両設計

Woven City工程（p40）: 2020-01 CES → 2021-02地鎮祭 → 2022-10安全祈願 → 2024-10竣工 → 2025-09ローンチ。

## SDB 2026年6月のAI・車載・知財
出典: [[sources/sdb-2026-safety]]（2026-09-06 20:15 JST）。
- GAIAは「10カテゴリー」（拡大検討）。列挙: AD/ADAS、AIエージェント、モビリティス3.0、ソフトウェア効率化、ノウハウ伝授、材料設計、製造、業務効率化、ロボティクス、車両設計。IRの「11カテゴリー」との差はカスタマーリレーション。文書と更新月が違うため両方残す。
- 社内にAIガイドラインに加え免許制度。教育は全従業員のリテラシー。
- Mobility Teammate Concept。Advanced Driveを2021-04のLSとMIRAIに設定。ソフト更新は無線または有線。
- TSS累計 6,100万台（2026-03）。RCCに匠ドライバー運転のAI解析を使うと記載。
- 知財2025年: 出願約19,000 / 登録約10,000。ポートフォリオ（出願中+登録）は電池20%・電動車18%・コネクティッド10%・自動運転10%。法律事務所約110。

## SDB 2026-06 のコネクティッドGHG把握
出典: [[sources/sdb-2026-env-plant]] p40 / p75-76（2026-09-06 23:15 JST）。
- 基盤ラベル: DCM → TBDC → MSPF / TSC。OTA、API、Smart Key Box / TransLogを並記。
- 対象はDCM搭載のエンジン車およびHEV。期間は日本 2025-04-01〜2026-03-31。
- 保証付き削減量: 省エネルート 0.06 / エアコ内気 749 / S-FLOW 39 / エコSW 375 / ACC 7 / 先読みSOC 2 / タイヤ空気圧 2（kt-CO2e、◆）。
- 教材: 車載データを燃費制御の実証値に繰り込む場合の範囲（WtW、IEA Mobility Model）と保証規準を区別する。
