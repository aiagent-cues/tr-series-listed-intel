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

## 2026-09-07 JST 16:11 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、フッタ2026-08-13。9月定例未掲。(3) 20-Fは pass5と同一。amendment URLは404。(4) toyota.com.au Past Reports はTFAのみ。TMCA PPE非掲。
- 実施: (5) 日野IR残件へ移行。ARCHION 2026-08-26「統合プラットフォーム戦略」一次と、同日のレンジャー／ファイター公式、8/25 CJPT-Asiaを抽出。
- 新事実の核: MDTは日野既存PFをふそうへ供給（レンジャー一部改良＋ファイター新型）。eLDTは逆向きで2026年度内生産開始予定。中長期はLDT/MDT/HDTの統合PF新規開発、ブランドは継承。ファイターエンジンはA05C 5.1L直4・全車177kW。東京地区税込 2WG-YC2ABA 11,009.9千円 / 2WG-YE2ACG 16,106.2千円。GVW11t・14tダンプと8t・11tの4WDを新設。販売は9月初旬順次。日野訂正はスキャニングクルーズの「全車速追従」括弧削除のみ。CJPT-Asiaは日野参画の代替でARCHIONがタイ法人へ参加（社長 中嶋裕樹）。工場別PPE・羽村精査確定は未掲。
- 出力: `llmwiki/sources/hino-ir-pass6.md`。index / WORKLOG / _meta / sources/hino-ir / sources/integrated-report / topics/production-management / topics/scm / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/A、(4)TMCA PPEは公式未掲。差替待ちならeLDT車名・工場確定、または羽村精査確定・工場別PPE。

## 2026-09-07 JST 15:14 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、フッタ2026-08-13。9月定例未掲。(3) 20-Fは pass5と同一。amendment URLは404。(4) toyota.com.au Past Reports はTFAのみ。TMCA PPE非掲。
- 実施: (5) 日野IR残件へ移行。ARCHION 2027年3月期1Q（2026-08-12公表、IFRSプロフォーマ比較）を一次抽出。
- 新事実の核: 連結売上台数 59,714（四捨五入60千、+14%）。売上収益 5,979億円 / 負ののれん前営業利益 290億円（率4.9%）。負ののれん暫定 2,332億円を含む営業利益 2,623 / 親会社帰属 2,515。通期見通し 230千台 / 売上24,250 / 負ののれん前営業1,100（率4.5%）。オセアニア1Q 1,913（豪州1,693、いずれも−29%）、通期見通し9,000。インドネシア政府受注がSEA+51%の主因。中東−82%。売出し後の予想持分はトヨタ25%・議決権19.9%。羽村売却益はPPAの時価純資産に含むが精査確定値は未掲。
- 出力: `llmwiki/sources/hino-ir-pass5.md`。index / WORKLOG / _meta / sources/hino-ir / sources/integrated-report / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/A、(4)TMCA PPEは公式未掲。差替待ちなら日野工場別PPE・羽村精査確定、またはARCHION 8/26統合プラットフォーム一次。

## 2026-09-07 JST 14:11 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」。9月定例未掲。(3) 20-Fは pass5と同一。amendment URLは404。
- 実施: (2) SDB環境の未抽出セルへ移行。第7次プランNo.5残部・No.6-7・No.9-19とp41制御説明、第8次CE/NP/管理行を日PDFから一次抽出。
- 新事実の核: 運搬船LNG切替は目標2隻に対し2025年度3隻。販売店は対象72国・新節190%・改節一部未達で整体未達（叙事の71国達成と層差）。Dismantlers目標15ヵ所→22ヵ所。環境異常は生産8件+非生産2件、重大違反なし。Today for Tomorrowは2020年度終了。第8次の廃棄物・取水原単位は2019年度以下（電池会社連結化で水使用増と注記）。省エネルートは2022-07から日本純正ナビ2017年モデル以降。raBitは2022-07民間7社。SinoHytec生産は2024-08。FC外販累計計3,000台以上（2025-12）。次世代FCは耐久2倍・航続20%増・2026年度実用化。
- 出力: `llmwiki/sources/sdb-2026-env-plan-review.md`。index / WORKLOG / _meta / topics/esg / topics/production-management / sources/integrated-report / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。差替待ちなら(4)TMCA PPEまたは(5)日野IR残件。

以前のブロックはヒストリの既存コミットに残す。
