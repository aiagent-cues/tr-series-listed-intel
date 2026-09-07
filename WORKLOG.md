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

## 2026-09-07 JST 13:07 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第18パス指定のClimate Public Policies 2025詳細頁p24-31を日英並読し、注[1]-[83]のAnnot URLを一次抽出。p1変更点とp32のレビュー対象外一覧も記録。
- 新事実の核: 2024→2025の冊子変更は根拠リンク明示・気候科学クライテリア追加・15→16。JAMAは2035電動車100%と多経路シナリオをIPCC 1.5整合と自己位置づけ。第6次エネ基の2030水素アンモニア1%（JH2A）。ACEAは2035新車CO2ゼロ支持・2030 EV50%に充電約6,000万・CPは遅くとも2027。Hydrogen Council設立趣旨は2℃、AR6の1.8℃シナリオ。NAM約14,000社で短中期削減目標なしが部分的整合の根拠。TBCSDはタイ2050 CN/2065 NZと43社以上。RTCは2030熱排出30%減と1,000万ドルChallenge。p32にBASC/CHAdeMO/FCCJ/WWF J等18団体。JH2A[28]はSharePoint。AAI[40]注はNLR、実リンクはNREL/DriveElectric。同友会[23]実ホストはInfluenceMap。
- 出力: `llmwiki/sources/integrated-report-2025-pass19.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: TCFD円額は未掲。(2)9月SDB、(3)20-F/A、(4)TMCA PPEは公式未掲。差替待ちならSDB環境表の未抽出セルへ。

## 2026-09-07 JST 12:20 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第17パス指定の Climate Public Policies 2025（32p）16団体×6項目セルを日英並読。年号なし別名PDFは2024-05の旧バイナリと確認。
- 新事実の核: 評価期間2025-07-21〜12-01。不整合0 / 部分的整合1（NAM削減目標）/ 公開確認不可11。TBCSD炭素価格のみ前年改善*。英p23のNAM炭素価格はAlignedだが英p28・日p23/p28は公開確認不可。WBCSDの佐藤恒治は2026-01にExecutive Committee就任予定。JH2A会長は佐藤、自動車会議所会長は豊田章男。TMTバンポーが2025-06-06に国外初OECM候補（10ha、植物119/動物528、教育6.2万人）。TMP ELV2号を2025-07-01設定（850台/年、SEA5件目）。
- 出力: `llmwiki/sources/integrated-report-2025-pass18.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: 詳細頁の出典クローリング、または(2)9月SDB。差替PDF/掲出待ち。

以前のブロックはヒストリの既存コミットに残す。
