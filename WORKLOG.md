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

## 2026-09-07 JST 04:16 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。(3) 20-Fは pass5と同一。PDF差替は無いが、第5パスが残した印刷p140-143のDE&I一次表があるため(1)を継続。
- 実施: 統合報告2025日PDF（168p）と英PDFからDE&I節を抽出。印刷頁=PDF頁−1。
- 新事実の核: 女性管理職2030年に2014年比5倍、新卒女性事務40%/技術10%。地域別女性比率2024年度（英はFY2025表記）グローバル採用23/正社員15/管理職12/経営幹部5。欧州・中国経営幹部0%、日本経営幹部20%。Loops 477人（2025-06）。同性婚・事実婚同等制度2020-07。グローバル女性会議2024年約160人。全員活躍ウィーク2025-07で30コンテンツ。日英の46社注記が不一致。
- 出力: `llmwiki/sources/integrated-report-2025-pass6.md` 新設。index / WORKLOG / _meta / topics/esg / people-metrics 更新。
- 次: 印刷p150-155のIR安全・品質とSDB差分。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 04:03 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。(3) 20-Fは pass5と同一。(4) TMCA Past Reportsは403。PDF差替は無いが、p73-87・p132-138に未抽出の一次数値が残るため(1)を継続。
- 実施: 統合報告2025日PDF（168p）から液体水素・CN燃料・CE・SDV基盤・RAV4・119・WB実数を抽出。
- 新事実の核: 水素エンジン仲間8→60社、連続30ラップ、raBit 2022-07/大熊2024-11、CN燃料4社2024-05、NTT合意2024-10・通信22倍/計算150倍、Arene SDK/Tools/Data、RAV4 EV150km・総1,350km・GR 320hp・累計1,500万台、e-Palette 2025-09 / L4は2027年度、WB SWLS 22.5→22.8・EG 60→64%。
- 出力: `llmwiki/sources/integrated-report-2025-pass5.md` 新設。index / WORKLOG / _meta / topics / people-metrics 更新。
- 次: p139-143 DE&I人数表。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 03:03 タイムボックス（1h分）
- 選定テーマ: 優先順 (1)統合報告2025は登録頁に2026未掲、日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB環境データも HEAD不変（11,691,278 / Last-Modified 2026-06-29 04:00:04 GMT）。(3) 20-Fは 00:10 pass5と同一。(4) TMCA車両会社PPEは非掲出継続。新事実なしのため (5) 日野IR残件へ移行。
- 実施: 日野統合報告書2025（69p / 26,543,734 bytes / Creation 2025-10-23）を公式URLから取得し非財務を抽出。
- 新事実の核: R&D550億・特許2,302・再エネ271,925MWh・水2,741千t。マテリアリティは2023-12特定。工場CO2は2013比▲60%。S1/S2/S3は12.4/8.4/4,835万t。FC実証4台で43万km・水素27t。古河SSA79件。女性管理職59人、男性育休73.6%。豪販社NSW議決権100%。
- 出力: `llmwiki/sources/hino-ir-pass4.md` 新設。index / WORKLOG / _meta / hino-ir / group / esg / production-management / scm / people-metrics 更新。
- 次: 羽村確定値と工場別PPEは公式未掲継続。(1)(2)は9月/10月差替PDF待ち。

以前のブロックはヒストリの既存コミットに残す。
