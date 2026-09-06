# 作業プロトコル（10時間箱）

本チャット単位で実時間10時間待機することはできないため、**10時間分の収集・整合手順を標準作業として定義**し、初期コーパスを投入し、GitHub Actionsで継続収集する。

## 標準タイムボックス（累計【10時間】

| ブロック | 時間 | 担当 | 出力 |
|---|---|---|---|
| 0. スコープ固定・スキーマ | 0.5h | P00, L01 | `_meta.yaml` |
| 1. 企業概要・役員・組織 | 1.0h | L06, C07 | `entities/`, `org-hr/` |
| 2. 決算・IFRS・管理会計 | 1.5h | L02, C08, C12 | `topics/ifrs.md`, `management-accounting.md` |
| 3. 統合報告・ESG | 1.5h | L03, C08 | `topics/esg.md`, `sources/integrated-report.md` |
| 4. 生産管理・SCM | 1.5h | L04, C10 | `topics/production-management.md`, `scm.md` |
| 5. AI開発・Woven・SDV | 1.5h | L05, C09 | `topics/ai-development.md` |
| 6. ニュース・事例 | 1.0h | C09 | `sources/news-2026.md` |
| 7. 訓練モジュール化 | 1.0h | C11, L01 | `training/` |
| 8. QA・索引 | 0.5h | Q13-Q16 | `index.md`, `lexicon.md` |

## 初回実施
- 実施日: 2026-09-04 JST
- 状態: 初期シード完了（公式ソース中心）
- 継続: `.github/workflows/collect.yml` が毎日 02:00 JST に公式ニュースルームを追記

## 2026-09-06 JST 11:03 タイムボックス（1h分）
- 選定テーマ: (1) 統合報告2025。既存は書誌・章リストのみでPDF本文未抽出。
- 実施: 日英公式PDFのHEAD/メタデータ確認、日本語168pから目次・社長交代・CFO・FY2025ハイライト・2026-01-01役員を抽出。
- 出力: `llmwiki/sources/integrated-report-2025.md` 新設、索引/材料M1/ESG/役員メモ更新。
- 次テーマ: (2) SDB環境データ。本回SDB本文は未処理。

## 2026-09-06 JST 12:11 タイムボックス（1h分）
- 選定テーマ: (2) SDB環境データ。(1)は同日11:03処理済みのため順位に従って移行。
- 実施: 登録頁と sdb26_jp/en.pdf のHEAD・pdfinfo、p1-7/環境指標p61-65/第7次プランp69-70/第8次プランp72/保証書を抽出。
- 出力: `llmwiki/sources/sdb-2026.md` 新設、ESG/索引/WORKLOG/_meta 更新。
- 次テーマ: (3) 20-F注記。SDBの社会・ガバナンス本文とCN叙事p15-60は未処理。

## 2026-09-06 JST 13:03 タイムボックス（1h分）
- 選定テーマ: (3) 20-F注記。(1)(2)は同日処理済み。
- 実施: FY2026 Form 20-F（SEC 2026-06-10、公式PDF 264p）のHEAD/pdfinfoと注記1-36を抽出。核は注記2表示変更、11売却目的（日野非連結・羽村残置・織機TOB）、16税金、24-25品質/引当、27収益分解、36後発（織機並合・LF-ZC中止）。
- 出力: `llmwiki/sources/20f-2026-notes.md` 新設、IFRS/グループ/索引/WORKLOG/_meta 更新。
- 次テーマ: (4) 海洋州・オセアニア工場。20-F注記3個別規定と注記13-15/18-23/31の明細は未処理。

## 2026-09-06 JST 14:03 タイムボックス（1h分）
- 選定テーマ: (4) 海洋州・オセアニア工場。(1)(2)(3)は同日処理済み。
- 実施: TMC日英公式（2014決定・2017終了・1995開設・2009 HEV）とTMCA/TNZ公式からAltona累計 3,451,115台、Thames CKD 1998-10終了、CoE/GEH2転用を抽出。
- 出力: `llmwiki/sources/oceania-plants.md` 新設、生産/SCM/グループ/索引/WORKLOG/_meta 更新。
- 次テーマ: (5) 日野自動車IR。海洋州広場の貸借対照表とThames当期台数は未処理。
