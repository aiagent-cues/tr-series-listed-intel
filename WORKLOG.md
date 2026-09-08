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

## 過去タイムボックス
- 2026-09-08 23:41 の累積は hino-ir-pass15 を正本とする。

## 2026-09-09 JST 00:38 タイムボックス（1h分）
- 選定: 優先(1)統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7）。TCFD円額未掲。第17パスがp112-113/p145-155再抽出不要と明示。(2) SDB登録頁は主な更新箇所（2026年6月）。sdb26_jp HEAD不変 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT。sdb27 / sdb26_jp_09 は404。9月定例未掲。(3) 20-F/Aは404。Exhibitはpass35まで処理済。(4) toyota.com.au は403。
- 実施: (5) 前パス未処理の公式ニュース2026-08-18〜09-07を一次抽出（メルファ / ブルーリボン・レインボー / HCS Logita約50万台 / ダカール2027 / バス協会AI実証）。
- 出力: `llmwiki/sources/hino-ir-pass16.md`。

## 2026-09-09 JST 01:13 タイムボックス（1h分）
- 選定: (1)–(4)差替なし。(5) HINO統合報告2025本文のp16国内3工場集約2028年末・p61連結PPE。
- 出力: `llmwiki/sources/hino-ir-pass17.md`。

## 2026-09-09 JST 03:09 タイムボックス（1h分）
- 選定: 優先(1)統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7）。TCFD円額未掲。(2) SDB登録頁は主な更新箇所（2026年6月）。頁メタ dateStr 2026年06月29日（足元8月日付はニュースウィジェット）。sdb26_jp HEAD不変 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT。sdb27 / sdb26_jp_09 は404。9月定例未掲。(3) 20-F/Aは404。(4) toyota.com.au は403。
- 実施: (5) 前パス未転記の公式ニュース2026-05-20–07-29（リエッセⅡ / プロフィア / セレガ / デュトロ Z EV / ダブル連結コミュニティ）。
- 新事実の核: リエッセⅡ EX GDB110M-ZRTQH 税抜9,865,000円 / GX GDB110M-ZRTEY 税抜8,396,100円。プロフィア 2WG-FW1AHG 25t・2WG-SH1EDGJ 11.5t。セレガ RU1ASDY-FRDDAC 税込50,952,110円。デュトロ Z EV ZAB-XED100V-AAAAA WLTC184km / 46.7kWh / 累計販売2000台以上。ダブル連結コミュニティ発足2026-07-23・11社。
- 出力: `llmwiki/sources/hino-ir-pass18.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。(4)TMCA PPE未掲。(5)羽村精査確定値・FY2026有報工場別PPE・ARCHION工場PPE・電気小型のふそう供給侧車名・NZ訴訟裁判所承認確定日・PL888管轄。
