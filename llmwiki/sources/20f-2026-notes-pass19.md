---
id: sources-20f-2026-notes-pass19
type: source-extract
title: Form 20-F FY2026 第19パス（注記33組織残セル / 注記34関連の相手区分 / 連結CF税金支払）
updated: 2026-09-08
period: FY2026
sources:
  - https://global.toyota/pages/global_toyota/ir/library/sec/20-F_202603_final.pdf
  - https://global.toyota/en/ir/library/sec/
  - https://global.toyota/jp/ir/library/sec/
  - https://www.sec.gov/Archives/edgar/data/1094517/000119312526264811/0001193125-26-264811-index.htm
  - https://global.toyota/jp/ir/library/annual/
  - https://global.toyota/jp/sustainability/report/sdb/
tags: [20-f, notes, ifrs, primary, fy2026, pass-19, ifrs-12, ias-24, ias-7]
---

# Form 20-F FY2026 第19パス（注記33残セル / 注記34相手区分 / 連結CF税支払）

調査時点: 2026-09-08 02:21 JST。公式一次情報の要約のみ。字句再現はしない。親パス既出の連結証券化債権8,267,069・担保債務8,664,183・非連結SPE期末1,049,995・関連売上合計4,095,328・仕入合計14,239,543・配当502,793→304,211・KMP報酬4,405・定期預金純増減は再掲しない。通読は [[sources/20f-2026-notes]] 〜 [[sources/20f-2026-notes-pass18]]。

印刷頁は公式PDF F-85（注記33）、F-86〜F-87（注記34(1)の相手区分と注記35）、連結CF本表（印刷頁のCash flows表、税支払行）。pdfinfo: 264頁 / Creation 2026-06-10 05:52:15 UTC / Mod 2026-06-10 06:33:11 UTC。

## 優先テーマの差替確認（本時点）

| 対象 | HTTP | 値 |
|---|---|---|
| 統合報告2025 日PDF | 200 | 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 version H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM |
| 統合報告2025 英PDF | 200 | 32,257,390 / 同日 Last-Modified / ETag 38c6c7536f07e5864b11e71518d075f2-7 / S3 version _H1V.omeW_Sb_LTXDClA5n2QVz2JkFrj |
| 2026_001_integrated_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年02月27日。表示は統合報告書2025（33.9MB／168ページ） |
| sdb26_jp.pdf | 200 | 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT / ETag 5d99d52f54b74bd6c67520210d322c83-3 / S3 version ty4iDeHrXxAZHh87VnhCFAsDcIoO1yOy |
| sdb26_en.pdf | 200 | 9,687,236 / 同日 Last-Modified / ETag 22a9d9db33aa448a137fcdb2a4e484a7-2 / S3 version staEiHcf3aZRTRajvHOtLV8.oTtLJJb8 |
| sdb27_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年06月29日。表示は主な更新箇所（2026年6月）。年2回（6月および9月） |
| 20-F_202603_final.pdf | 200 | 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT / ETag b0e64e363ef4dc1f9b21441333eb0c8d-2 / S3 version KsbQIrdqL4z.4I6gq4Qditi8YSQkRnQk |
| 20-FA_202603_final.pdf / 20-F_202603_final_amendment.pdf | 404 | 未掲。英登録頁 dateStr Jun. 11, 2026、表示 2026 Form 20-F（PDF: 5.01 MB / 264 pp.）。日登録頁 dateStr 2026年06月11日 |

登録頁: https://global.toyota/jp/ir/library/annual/ 、https://global.toyota/jp/sustainability/report/sdb/ 、https://global.toyota/en/ir/library/sec/ 、https://global.toyota/jp/ir/library/sec/

本パス: 第18パスが残していた注記33の組織・SPE認識単位を一次抽出。親ファイルが合計のみ残していた注記34のAssociates/JV分解と、第18パスが次候補とした連結CFの「Income taxes paid, net of refunds」を一次抽出。KMP報酬表は [[org-hr/officers-2026]] / 第5パス既出のため再計しない。

## 注記33(1) 主要子会社の記載単位（F-85、本パスの核）

事業の見出しは自動車・金融・その他の3区分。その他は情報技術関連とその他、と本文。

自動車の製造主体は国内がTMC・日野・ダイハツ（一部は国内外注）、海外はToyota Motor Manufacturing Kentucky, Inc. ほか。部品はTMCほか。販売は国内がTOYOTA Mobility Tokyo Inc. などの販売店、海外がToyota Motor Sales, U.S.A., Inc. などの販売店。金融は国内がトヨタファイナンス株式会社ほか、海外がToyota Motor Credit Corporationほか。

注記33(1)に持分比率・所在地・資本金の表は無い。日野の2026-04-01非連結は注記11・注記36へ委譲。

## 注記33(2) ストラクチャード・エンティティ（F-85〜F-86）

### 連結SPE

金融債権およびリース車両を流動性・資金調達目的でSPEへ移転する。トヨタは経済パフォーマンスに最も重要な活動を指図するパワーを持つと判定して連結する。

債権者はトヨタが保証した債務を除き、トヨタの一般信用へ遡及しない。証券化前後で信用・金利・期限前償還リスクは増分しない、と本文。

投資信託その他SPEのうち、損失吸収義務または重要になり得る便益受領権と、資産運用者経由の指図パワーを同時に持つものは連結する。

連結証券化の残高比較（百万円、親パスはFY2026のみ既出）:

| | 2025-03-31 | 2026-03-31 |
|---|---:|---:|
| 金融サービス関連債権 | 7,280,835 | 8,267,069 |
| 担保付債務 | 7,486,241 | 8,664,183 |

### 非連結SPE

議決権等が支配の主因にならないよう契約で設計された投資信託・SPEをストラクチャードに分類する。指図パワーを欠くため非連結。公正価値で「その他の金融資産」に含める。損失の最大エクスポージャーは投資の帳簿価額に限る。契約上要求されない支援は提供しない、と本文。

| | 2025-03-31 | 2026-03-31 |
|---|---:|---:|
| 投資信託の帳簿 | 167,038 | 113,204 |
| その他SPEの帳簿 | 2,517,967 | 1,049,995 |

非連結投資信託の比較年167,038は親パス非掲。非連結SPEの比較年2,517,967も親パス非掲。

## 注記34(1) Associates / JV の分解（F-86〜F-87、百万円）

相手先氏名表は無い。通常の営業過程外の取引は行わない、と本文。配当の比較年は親パス既出。

期末残高:

| | 2025-03-31 | 2026-03-31 |
|---|---:|---:|
| 売掛等 Associates | 466,420 | 599,558 |
| 売掛等 JV | 79,251 | 106,776 |
| 売掛等 計 | 545,671 | 706,334 |
| 買掛等 Associates | 1,576,129 | 1,844,886 |
| 買掛等 JV | 8,573 | 20,180 |
| 買掛等 計 | 1,584,702 | 1,865,066 |

期間取引（親パスはFY2025-FY2026の売上合計とJV/関連売上のみ既出。仕入の相手区分とFY2024は本パス）:

| | FY2024 | FY2025 | FY2026 |
|---|---:|---:|---:|
| 売上 Associates | 3,137,067 | 3,420,576 | 2,933,464 |
| 売上 JV | 662,202 | 622,056 | 1,161,865 |
| 仕入 Associates | 12,426,770 | 12,889,776 | 14,090,055 |
| 仕入 JV | 75,042 | 82,963 | 149,488 |

貸付残高行は注記34(1)に無い。取締役関係先の独立表も注記34に無い。

## 連結CFの税金支払（本表、百万円）

第18パスが次候補とした「Income taxes paid, net of refunds」。連結キャッシュ・フロー計算書の営業CF行。

| | FY2024 | FY2025 | FY2026 |
|---|---:|---:|---:|
| 法人税等の支払（還付差引後） | △1,124,322 | △2,501,315 | △1,240,680 |

Item 5本文はFY2026の支払減を1,260.7十億円と記述。差は2,501,315−1,240,680=1,260,635。非金融事業の分割CFにある税支払行（2,347,622 / 1,159,061）は本表と対象が異なるため本パスでは引用しない。

## 未処理

- 20-F/A（探した amendment URL は 404）。
- 2026統合報告・TCFD円額、SDB 9月定例PDF。
- 注記3金融商品の認識中止・条件変更の独立方針文（当初認識は注記3に契約当事者になった時、とある。専用パス未作成）。
- TMCA PPE、日野工場別PPE・羽村精査確定・eLDT車名工場。
