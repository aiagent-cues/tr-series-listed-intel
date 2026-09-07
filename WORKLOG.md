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

## 2026-09-07 JST 14:11 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。amendment URLは404。
- 実施: (2) SDB環境の未抽出セルへ移行。第7次プランNo.5残部・No.6-7・No.9-19とp41制御説明、第8次CE/NP/管理行を日PDFから一次抽出。
- 新事実の核: 運搬船LNG切替は目標2隻に対し2025年度3隻。販売店は対象72国・新築100%・改築一部未達で整体未達（叙事の71国達成と層差）。Dismantlers目標15ヵ所→22ヵ所。環境異常は生産8件+非生産2件、重大違反なし。Today for Tomorrowは2020年度終了。第8次の廃棄物・取水原単位は2019年度以下（電池会社連結化で水使用増と注記）。省エネルートは2022-07から日本純正ナビ2017年モデル以降。raBitは2022-07民間7社。SinoHytec生産は2024-08。FC外販7d2f計3,000台以上（2025-12）。次世代FCは耐久2倍・航続20%増・2026年度実用化。
- 出力: `llmwiki/sources/sdb-2026-env-plan-review.md`。index / WORKLOG / _meta / topics/esg / topics/production-management / sources/integrated-report / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。差替待ちなら(4)TMCA PPEまたは(5)日野IR残件。

## 2026-09-07 JST 13:07 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。
- 実施: 第18パス指定のClimate Public Policies 2025詳細頁p24-31を日英並読し、注[1]-[83]のAnnot URLを一次抽出。p1変更点とp32のレビュー対象外一覧も記録。
- 新事実の核: 2024→2025の冊子変更は根拠リンク明示・気候科学クライテリア追加・15→16。JAMAは2035電動車100%と多経路シナリオをIPCC 1.5整合と自己位置づけ。第6次エネ基の2030水素アンモニア1%（JH2A）。ACEAは2035新車CO2ゼロ支持・2030 EV50%に充電約6,000万・CPは遅くとも2027。Hydrogen Council設立趣旨は2℃、AR6の1.8℃シナリオ。NAM約14,000社で短中期削減目標なしが部分的整合の根拠。TBCSDはタイ2050 CN/2065 NZと43社以上。RTCは2030熱排出30%減と1,000万ドルChallenge。p32にBASC/CHAdeMO/FCCJ/WWF J等18団体。JH2A[28]はSharePoint。AAI[40]注はNLR、実リンクはNREL/DriveElectric。同友会[23]実ホストはInfluenceMap。
- 出力: `llmwiki/sources/integrated-report-2025-pass19.md`。index / WORKLOG / _meta / topics/esg / sources/integrated-report / _last_run 更新。
- 次: TCFD円額は未掲。(2)9月SDB、(3)20-F/A、(4)TMCA PPEは公式未掲。差替待ちならSDB環境表の未抽出セルへ。

以前のブロックはヒストリの既存コミットに残す。
