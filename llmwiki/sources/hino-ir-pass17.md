---
id: sources-hino-ir-pass17
type: source-extract
title: Hino IR pass17（統合報告書2025本文・国内3工場集約期限と連結有形）
updated: 2026-09-09
period: FY2025-YE / 2028-horizon
sources:
  - https://www.hino.co.jp/corp/for_investors/pdf/integrated_report/integrated_report_2025_jp.pdf
  - https://www.hino.co.jp/corp/for_investors/
  - https://www.hino.co.jp/corp/news/2026/
  - https://www.hino.co.jp/corp/for_investors/disclosure/2026.html
  - https://www.hino.co.jp/corp/for_investors/financial_statements.html
  - https://www.hino.co.jp/corp/sustainability/parts/pdf/environment_TCFD.pdf
  - https://archion.co.jp/ir/library/
  - https://www.toyota-hamura.co.jp/company/profile/
  - https://global.toyota/jp/ir/library/annual/
  - https://global.toyota/jp/sustainability/report/sdb/
  - https://global.toyota/en/ir/library/sec/
  - https://global.toyota/pages/global_toyota/ir/library/sec/20-F_202603_final.pdf
  - https://www.toyota.com.au/explore/corporate/investors/past-reports
tags: [hino, 7205, integrated-report, ppe, plant, koga, nitta, kawasaki, archion, primary, pass-17, j-gaap]
---

# 日野自動車IR 第17パス（HINO統合報告書2025本文の工場・連結PPE）

調査時点: 2026-09-09 01:13 JST。第1–16パスは[[sources/hino-ir]]〜[[sources/hino-ir-pass16]]。公式一次情報の要約のみ。字句再現はしない。FY2025有報の工場別帳簿、3Q説明会括弧率、メルファ／路線バス価格、ARCHION統合PF供給は再掲しない。

## 優先テーマの差替確認（本時点）

| 対象 | HTTP | 値 |
|---|---|---|
| 統合報告2025 日PDF | 200 | 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 |
| 統合報告2025 英PDF | 200 | 32,257,390 / 同日 Last-Modified / ETag 38c6c7536f07e5864b11e71518d075f2-7 |
| 2026_001_integrated_jp.pdf / _en.pdf | 404 | 登録頁は統合報告書2025（33.9MB／168ページ）。2026未掲 |
| sdb26_jp.pdf | 200 | 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT / ETag 5d99d52f54b74bd6c67520210d322c83-3 |
| sdb26_en.pdf | 200 | 9,687,236 / 同日 Last-Modified / ETag 22a9d9db33aa448a137fcdb2a4e484a7-2 |
| sdb27_jp.pdf / sdb26_jp_09.pdf / sdb26_en_09.pdf | 404 | 登録頁は主な更新箇所（2026年6月）。頁メタ dateStr 2026年06月29日。年2回（6月および9月）。9月定例未掲 |
| 20-F_202603_final.pdf | 200 | 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT / ETag b0e64e363ef4dc1f9b21441333eb0c8d-2 |
| 20-FA / amendment（TMCサイト） | 404 | 英登録頁は 2026 Form 20-F。Amendment列は No |
| TMCA Past Financial Reports | 403 | Cloudflare challenge。PPE新見なし |
| 日野ニュース 20260908-* / 20260909-* | 404 | 最新行 20260907-004742。次行 20260903-004725 |
| 日野適時開示2026 | 200 | 9月新規行なし。最新日付行 2026-03-27 15:30 |
| HINO統合報告2025 PDF | 200 | 26,543,734 / Last-Modified Mon, 16 Feb 2026 05:46:23 GMT / ETag 1950676-64aea799b9db7 / 69頁 |
| 日野 TCFD PDF | 200 | 1,424,592 / Last-Modified Mon, 16 Feb 2026 05:22:12 GMT |

(1)トヨタ統合報告2025は差替なし。TCFD円額未掲。(2) SDB 9月定例PDF未掲。(3) 20-F/A未掲。(4) toyota.com.au は403。

本パス: 優先(5)の未処理だった **HINO統合報告書2025本文** から、国内トラック工場の集約期限と連結有形固定資産の10年系列を一次抽出。工場別帳簿は[[sources/hino-ir-pass10]]（FY2025有報、2025-03-31）が正本。本報に工場別円額表は無い。

## 書誌

| 項目 | 値 |
|---|---|
| 文書 | 日野グループ 統合報告書2025（INTEGRATED REPORT 25） |
| PDF | https://www.hino.co.jp/corp/for_investors/pdf/integrated_report/integrated_report_2025_jp.pdf |
| HEAD（本時点） | 200 / 26,543,734 / Last-Modified Mon, 16 Feb 2026 05:46:23 GMT |
| pdfinfo | 69頁 / Creation 2025-10-23 03:08:58 UTC / Mod 2025-10-23 03:09:46 UTC / InDesign 19.4 |
| 対象期間 | 2024-04-01〜2025-03-31（一部期間外） |
| 発行時期 | 2025年10月 |
| 企画 | 日野自動車株式会社 経営企画部 |
| 会計 | 日本基準の連結要約。TMC Form 20-F（IFRS）と合算しない |

## 国内トラック生産拠点の集約（p16）

出典: 同上 p16「4社協業、2社経営統合について」。金額は非掲。

| 事実 | 値 |
|---|---|
| 期限 | 2028年末まで |
| 起点 | 現在完所ある国内トラック生産拠点 |
| 着地 | 3カ所 |
| 残す拠点 | 川崎製作所（神奈川県川崎市）／古河工場（茨城県古河市）／新田工場（群馬県太田市） |
| 並記 | 生産拠点・物流ネットワークの最適化。間接機能の集約と重複領域の最適化 |

照合（混用禁止）:
- FY2025有報の提出会社4行は日野工場・羽村工場・新田・古河。本報の「現在5カ所」は三菱ふそう側を含むARCHION国内トラック拠点の数え方であり、有報4行と一致しない。
- 着地3カ所に **羽村と日野工場は含まれない**。羽村は2026-04-01移管後の toyota-hamura 範囲。日野工場の帳簿は[[sources/hino-ir-pass10]]。
- 川崎製作所の工場別PPEは日野FY2025有報に無い。ARCHION有報PDFも未掲。円額は本報でも非掲。

同頁の新会社概要（2025-10-09時点で選任予定と本文が注記）: 社名 ARCHION株式会社、本社 東京都品川区。CEO カール・デッペン / CFO ヘタル・ラリギ / CTO 小木曽聡 / 非常勤取締役 伊勢清貴・クリスチャン・ヘルマン。独立社外取締役4名は「11月上旬に決定し公表予定」と本文。2026-08-26 ARCHION公式の肩書（デッペン／アーリャ／クスマノ）と時点が異なる。混用しない。

## 連結有形固定資産ほか（p61、百万円、各年3月期）

工場別内訳は非掲。連結合計のみ。2024.3→2025.3。

| 科目 | 2024.3 | 2025.3 |
|---|---:|---:|
| 有形固定資産 | 444,513 | 442,836 |
| 無形固定資産および投資その他の資産 | 211,553 | 199,166 |
| 流動資産 | 808,307 | 836,177 |
| 総資産 | 1,464,375 | 1,478,180 |
| 流動負債 | 853,141 | 1,021,370 |
| 固定負債 | 147,813 | 205,789 |
| 純資産 | 463,420 | 251,020 |
| 有利子負債 | 373,789 | 407,529 |
| 設備投資 | 73,747 | 71,019 |
| 減価償却費 | 56,479 | 59,484 |
| 研究開発費 | 55,285 | 54,955 |
| 自己資本比率 | 26.8% | 12.1% |
| 自己資本利益率 | 4.5% | △76.3% |
| 営業利益率 | △0.5% | 3.4% |
| 1株当たり当期純利益（円） | 29.77 | △379.34 |
| 1株当たり配当（円） | — | — |

有形は **1,677百万円減**（444,513→442,836）。設備投資71,019はFY2025有報の連結合計と一致（[[sources/hino-ir-pass10]]）。純資産の減少は認証関連損失を含む当期純損失2,177.53億円と整合するが、本表は要約であり特別損失の内訳表ではない。

10年の有形固定資産（百万円）: 2016.3 398,397 / 2017.3 425,076 / 2018.3 428,751 / 2019.3 433,589 / 2020.3 435,217 / 2021.3 435,087 / 2022.3 444,293 / 2023.3 440,187 / 2024.3 444,513 / 2025.3 442,836。

## 会社情報（p66、2025-03-31）

資本金 72,717百万円。売上高 1,697,229百万円。営業利益 57,490百万円。従業員 33,608人。代表取締役社長CEO 小木曽聡（本報時点。3Q適時開示の異動後の現行CEOと混用しない）。発行済 574,580,850株。証券コード 7205。東証プライム／名証プレミア。

主要株主（千株／持株比率、自己株式控除）: トヨタ自動車 287,897（50.14%）／日本マスタートラスト信託銀行（信託口）姡21（10.30%）／日本カストディ銀行（信託口）18,746（3.27%）。

## TCFD本文（p54）

4℃シナリオと2℃未満シナリオの定性整理。円額の感応度表は非掲。別冊 https://www.hino.co.jp/corp/sustainability/parts/pdf/environment_TCFD.pdf も Last-Modified 不変。

## 未処理

- 20-F/A、2026統合報・トヨタTCFD円額、SDB9月定例。
- TMCA PPE（toyota.com.au 403）。
- 羽村精査確定値・FY2026有報工場別PPE。
- 川崎・中津・富山・ポルトガルの工場別固定資産円額（ARCHION有報PDF未掲、本報も非掲）。
- 電気小型の日野側車名。NZ裁判所承認確定日。PL888管轄。
