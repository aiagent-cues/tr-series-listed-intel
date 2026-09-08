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

## 2026-09-09 JST 06:09 タイムボックス（1h分）
- 選定: (1)–(4)差替なし。
- 出力: `llmwiki/sources/hino-ir-pass21.md`。

## 2026-09-09 JST 06:22 タイムボックス（1h分）
- 選定: (1)–(4)差替なし。日統合報PDF 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT。sdb26_jp 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT。sdb27 / sdb26_jp_09 / 20-FA 404。toyota.com.au 403。ニュース20260908-* / 20260909-* は404。適時開示2026の最新行は2026-03-27 15:30。
- 実施: (5) 前パス未転記の適時開示・有報附属明細（2026-03-02 上場承認日程 / 同日払込予定日 / 2026-03-11 貸借銘柄 / 2026-03-27 種類別払込完了円額 / FY2025有報個別の工場別増加 / 2026-05-28 技術開発賞受賞者）。
- 新事実の核: 日野売買最終日2026-03-27・上場廃止2026-03-30・ARCHION上場/売買開始2026-04-01・コーツ543A。貸借銘柄選定日2026-04-01。普通270,915,798株で121,370,277,504円、A種175,512,774株で78,629,722,752円（各448円、資本・準備金各224円）。建物増加は新田1,901 / 羽村1,120 / 日野643 / 古河153。土地減少は日野工場中央18・羽和寮508。賞は竹中悠祐ほか、超低床小型BEVパワートレーン。
- 出力: `llmwiki/sources/hino-ir-pass22.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/A未掲。(4)TMCA PPE未掲。(5)羽村精査確定値・FY2026有報工場別PPE・ARCHION工場PPE・小型電動の日野側車名・NZオークランド承認確定日・現地通貨総額・PL888管轄・公取委問題解消措置本文。

## 2026-09-09 JST 07:03 タイムボックス（1h分）
- 選定: (1)統合報2025。日PDF 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag不変。2026未掲。TCFD円額未掲。本文の報酬・5ブランド・水素・RAV4・DE&Iは pass3-6 既出。新事実なしのため(2)へ。
- (2) SDB6月PDFも差替なし（sdb26_jp 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT）。9月定例PDF 404。ただ全社サステナ頁トピックスが2026-08-31更新で、SDB6月本文の5サイト表に無い貞宝認定が公式一次として存在。
- 実施: 貞宝工場「森と桜池」1.9ha・2026-06認定・6サイト目。下山/士別/堤/トヨタの森は2025-09、宮川1,689.28haは2026-03。法は地域生物多様性増進法。OECM国際DBへ順次登録と本文。ハブに2024年TN LEAD/ENCORE調査。
- 出力: `llmwiki/sources/sdb-2026-env-nature-sites.md`。index / WORKLOG / _meta / sources/integrated-report / topics/esg / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB PDF、(3)20-F/A、(4)TMCA PPE、OECMレコードID、(5)羽村精査確定値・FY2026有報工場別PPE・ARCHION工場PPE。
