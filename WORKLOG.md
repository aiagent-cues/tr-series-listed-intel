# 作業プロトコル（10時間箱）

本チャット単位で実時間10時間待機することはできないため、**10時間分の収集・整合手順を標準作業として定義**し、初期コーパスを投入し、GitHub Actionsで継続収集する。

## 標準タイムボックス（累計【10時間】

|ブロック|時間|担当|出力|
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

## 2026-09-07 JST 12:20 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第17パス指定の Climate Public Policies 2025（32p）16団体×6項目セルを日英並読。年号なし別名PDFは2024-05の旧バイナリと確認。
- 新事実の核: 評価期間2025-07-21〜12-01。不整合0 / 部分的整合1（NAM削減目標）/ 公開確認不可11。TBCSD炭素価格のみ前年改善*。英p23のNAM炭素価格はAlignedだが英p28・日p23/p28は公開確認不可。WBCSDの佐藤恒治は2026-01にExecutive Committee就任予定。JH2A会長は佐藤、自動車会議所会長は豊田章男。TMTバンポーが2025-06-06に国外初OECM候補（10ha、植物119/動物528、教育6.2万人）。TMP ELV2号を2025-07-01設定（850台/年、SEA5件目）。
- 出力: `llmwiki/sources/integrated-report-2025-pass18.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: 詳細頁の出典クローリング、または(2)9月SDB。差替PDF/掲出待ち。

## 2026-09-07 JST 12:07 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第16パス指定の印刷p145-155・TCFD円額は第3-8パスで処理済みと確認。未記録のTCFD会議体（2025-06、開催回数）とCDP/ISO範囲のSDB差、本冊引用のClimate Public PoliciesをHEAD。2025年版（32p、Last-Modified 2025-12-29）が公式配布済み。
- 新事実の核: サステナビリティ会議5回 / 分科会3回 / CN戦略2回 / GRC5回（2024年度）。CDP 2025-07は気候A・水B（SDBの水A-と時点差）。ISO14001は本冊126社（2024）対SDB 124社（2025）。第8次環境取組プランは2025-10公表・2026-04開始。GX推進法2025-05-28、義務化2026-04（直接排出10万トン以上）。EPA提案へ2025-09-22コメント。TMNAサプライヤー年5.5%。レビュー16団体（追加RTC）。電動車累計3,175万台（2025-03末）。GOA設定1995。
- 出力: `llmwiki/sources/integrated-report-2025-pass17.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: Climate Policies 2025の16団体セル評価。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 11:20 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第15パス残の印刷p98-99（会長年頭の創業住宅・モビリティ宣言）を日英並読。英注46社と英p71福岡落ちは差替なしと再確認。同伴一次は75年史住宅項とトヨタT&S建設公式。
- 新事実の核: 会長の前回年頭は2023（3年ぶり）。動画は終戦直後の不燃住宅研究。1950年施設部プレコンがユタカプレコン独立（社長豊田佐助、現トヨタT&S建設）。喜一郎1952没・同年章一郎入社。1968全豊田技術会議の新事業3要件で住宅を選定。2019トヨタホーム株主懸談会で章一郎が平屋+空飛ぶクルマ。モビリティカンパニー宣言は2018。2009就任から9年で継承者。会長3役割は人材育成（普通の会社化防止）/グループのあり方/文化プロモーション。75年史は1946-03平山ガラス転用、1950-06-07設立・資本金2,400万円。英注はなお "Japan and from 46 overseas companies"。
- 出力: `llmwiki/sources/integrated-report-2025-pass16.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: 印刷p145-155残表、TCFD影響額。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 11:07 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。
- 出力: `llmwiki/sources/integrated-report-2025-pass15.md`。

## 2026-09-07 JST 10:36 タイムボックス（1h分）
- 出力: `llmwiki/sources/integrated-report-2025-pass14.md`。

## 2026-09-07 JST 10:18 タイムボックス（1h分）
- 出力: `llmwiki/sources/integrated-report-2025-pass13.md`。

## 2026-09-07 JST 09:00 タイムボックス（1h分）
- 出力: `llmwiki/sources/integrated-report-2025-pass12.md`。

以前のブロックはヒストリの既存コミットに残す。
