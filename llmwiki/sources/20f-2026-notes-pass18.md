---
id: sources-20f-2026-notes-pass18
type: source-extract
title: Form 20-F FY2026 第18パス（注記3税金の当期/繰延表示単位 / SFP純額 / 注記22相殺）
updated: 2026-09-08
period: FY2026
sources:
  - https://global.toyota/pages/global_toyota/ir/library/sec/20-F_202603_final.pdf
  - https://global.toyota/en/ir/library/sec/
  - https://global.toyota/jp/ir/library/sec/
  - https://www.sec.gov/Archives/edgar/data/1094517/000119312526264811/0001193125-26-264811-index.htm
  - https://global.toyota/jp/ir/library/annual/
  - https://global.toyota/jp/sustainability/report/sdb/
tags: [20-f, notes, ifrs, primary, fy2026, pass-18, ias-12, ifrs-7]
---

# Form 20-F FY2026 第18パス（注記3税金表示単位 / 注記22）

調査時点: 2026-09-08 02:08 JST。公式一次情報の要約のみ。字句再現はしない。親パス既出の法定30.9%・実効22.7%・Pillar Two「重要影響なし」+IAS 12一時例外・DTA総額2,906,926・DTL総額3,935,835・純負債1,028,909・未認識2,663,620・当期国内1,053,788/在外419,137は再掲しない。通読は [[sources/20f-2026-notes]] 〜 [[sources/20f-2026-notes-pass17]]。

印刷頁は公式PDF F-22（注記3「Income taxes」）、F-8前後（連結財政状態計算書の税金行）、F-39（注記16総額）、F-24（注記4見積りリスト）、F-60前後（注記22）。pdfinfo: 264頁 / Creation 2026-06-10 05:52:15 UTC / Mod 2026-06-10 06:33:11 UTC。

## 優先テーマの差替確認（本時点）

| 対象 | HTTP | 値 |
|---|---|---|
| 統合報告2025 日PDF | 200 | 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 version H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM |
| 統合報告2025 英PDF | 200 | 32,257,390 / 同日 Last-Modified / ETag 38c6c7536f07e5864b11e71518d075f2-7 / S3 version _H1V.omeW_Sb_LTXDClA5n2QVz2JkFrj |
| 2026_001_integrated_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年02月27日。表示は統合報告書2025（33.9MB／168ページ）。OGP integrated_ogp_2025_jp.jpg |
| sdb26_jp.pdf | 200 | 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT / ETag 5d99d52f54b74bd6c67520210d322c83-3 / S3 version ty4iDeHrXxAZHh87VnhCFAsDcIoO1yOy |
| sdb26_en.pdf | 200 | 9,687,236 / 同日 Last-Modified / ETag 22a9d9db33aa448a137fcdb2a4e484a7-2 / S3 version staEiHcf3aZRTRajvHOtLV8.oTtLJJb8 |
| sdb27_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年06月29日。表示は主な更新箇所（2026年6月）。年2回（6月および09月） |
| 20-F_202603_final.pdf | 200 | 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT / ETag b0e64e363ef4dc1f9b21441333eb0c8d-2 / S3 version KsbQIrdqL4z.4I6gq4Qditi8YSQkRnQk |
| 20-FA_202603_final.pdf / 20-F_202603_final_amendment.pdf | 404 | 未掲。英登録頁 dateStr Jun. 11, 2026、表示 2026 Form 20-F（PDF: 5.01 MB / 264 pp.）。日登録頁 dateStr 2026年06月11日 |

登録頁: https://global.toyota/jp/ir/library/annual/ 、https://global.toyota/jp/sustainability/report/sdb/ 、https://global.toyota/en/ir/library/sec/ 、https://global.toyota/jp/ir/library/sec/

本パス: 第17パスが残していた注記3法人所得税の「当期/繰延の集計・表示単位」を一次抽出。税率・未認識・Pillar Two金額は注記16既出のため再計しない。同時に未抽出だった注記22（主契約付の未相殺デリバティブ）を一次抽出。

## 注記3 Income taxes の認識・表示単位（F-22、本パスの核）

方針文の集計定義は1文のみ。法人税等費用は当期税金と繰延税金の合計として表示する。

当期税金単位の独立見出しは注記3に無い。次を注記3本見出しに書かない。

- 当期税負債の計上定義（税務当局への支払要請が生じた場合の文）
- 不確定税務位置 / IFRIC 23 の見出し
- 当期税資産・負債の相殺要件
- 繰延税資産・負債の相殺要件（同一税務当局・法的実施可能権など）
- 繰延の流動/非流動分類

繰延の認識対象と測定・子会社投資DTLの非認識2要件は [[sources/20f-2026-notes-pass13]]。注記4の見積りリストは繰延税資産の回収可能性を注記3「Income taxes」と注記16へ委譲するだけで、追加の金額閾値や見積り年数は注記4本文に無い。

注記3の未適用新基準表はIFRS 18一行のみ（強制2027-01-01以後開始、TMC適用予定は2028-03-31終了期、影響は金融セグメントの顧客金融、評価中）。同表に他基準行は無い。

## 連結SFPの当期税・繰延純額（百万円、本パスで一次掲記）

注記16の繰延は総額行のみ。財政状態計算書は相殺後の純額で掲記する。

| 科目 | 2025-03-31 | 2026-03-31 |
|---|---:|---:|
| 未収法人税（流動資産） | 216,528 | 235,425 |
| 未払法人税（流動負債） | 505,500 | 711,675 |
| 繰延税資産（非流動、純額） | 517,869 | 555,596 |
| 繰延税負債（非流動、純額） | 1,659,433 | 1,584,505 |
| SFP純額の負債超 | 1,141,564 | 1,028,909 |

SFP純額の負債超は注記16の総額純額（DTA 2,906,926 − DTL 3,935,835 = 負債超1,028,909）と一致する。相殺幅の独立表は注記16に無い。繰延は全額が非流動。未収・未払の当期税は流動のみ。

当期税のSFPネット（未払−未収）: FY2025 288,972 / FY2026 476,250。貸借対照として注記16(2)の当期税費用FY2026 1,472,925がある。

## 注記22 金融資産・負債の相殺（F-60前後、百万円）

対象は実効のある主契約または類似契約に繋がるが、相殺要件を全ては満たさないため財政状態計算書上相殺していない金額。将来の相殺権と担保は、相手の破産等で債務不履行が生じた場合に限り実行可能、と本文。

| | 縸額 | 未相殺金融商品 | 未相殺担保 | ネット |
|---|---:|---:|---:|---:|
| 2025-03-31 その他金融資産 デリバティブ | 483,378 | △131,836 | △67,495 | 284,046 |
| 2025-03-31 その他金融負債 デリバティブ | 319,881 | △131,836 | △73,689 | 114,356 |
| 2026-03-31 その他金融資産 デリバティブ | 479,447 | △138,762 | △63,177 | 277,508 |
| 2026-03-31 その他金融負債 デリバティブ | 357,955 | △138,762 | △23,138 | 196,055 |

財政状態計算書上、相殺要件を満たして実際に相殺した額はimmaterial、と注記22末尾。相殺対象の科目はデリバティブのみ。貸付・金融債権・社債の相殺行は注記22に無い。

## 未処理

- 20-F/A（探した amendment URL は 404）。
- 2026統合報告・TCFD円額、SDB 9月定例PDF。
- 注記3の方針見出しは本パスで当期税の独立定義が無いことを確認。残る独立見出しは新基準表（IFRS 18以外行なし）のみ。
- TMCA PPE、日野工場別PPE・羽村精査確定・eLDT車名工場。
