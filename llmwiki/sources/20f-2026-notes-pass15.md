---
id: sources-20f-2026-notes-pass15
type: source-extract
title: Form 20-F FY2026 第15パス（注記3 外貨・売却目的判定・従業員給付認識単位・株式報酬方針 / 現金同等物・棚卸NRV）
updated: 2026-09-08
period: FY2026
sources:
  - https://global.toyota/pages/global_toyota/ir/library/sec/20-F_202603_final.pdf
  - https://global.toyota/en/ir/library/sec/
  - https://global.toyota/jp/ir/library/sec/
  - https://www.sec.gov/Archives/edgar/data/1094517/000119312526264811/0001193125-26-264811-index.htm
  - https://global.toyota/jp/ir/library/annual/
  - https://global.toyota/jp/sustainability/report/sdb/
tags: [20-f, notes, ifrs, primary, fy2026, pass-15, ias-21, ias-19, ifrs-2, ias-7, ias-2, ifrs-5]
---

# Form 20-F FY2026 第15パス（注記3 外貨・給付・株式報酬の認識単位）

調査時点: 2026-09-08 00:01 JST。公式一次情報の要約のみ。字句再現はしない。親パス既出のIAS 19期末純額・割引率・資産クラス、IFRS 2のRS/RSU/ESOP付与履歴と費用3期は再掲しない。通読は [[sources/20f-2026-notes]] 〜 [[sources/20f-2026-notes-pass14]]。

印刷頁は公式PDF F-12（外貨）、F-13（現金同等物）、F-18（棚卸・売却目的）、F-21〜F-22（従業員給付）、F-23（株式報酬）。PDF頁170 / 171 / 176 / 179–181。pdfinfo: 264頁 / Creation 2026-06-10 05:52:15 UTC / Mod 2026-06-10 06:33:11 UTC。

## 優先テーマの差替確認（本時点）

| 対象 | HTTP | 値 |
|---|---|---|
| 統合報告2025 日PDF | 200 | 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 version H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM |
| 統合報告2025 英PDF | 200 | 32,257,390 / 同日 Last-Modified / ETag 38c6c7536f07e5864b11e71518d075f2-7 / S3 version _H1V.omeW_Sb_LTXDClA5n2QVz2JkFrj |
| 2026_001_integrated_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年02月27日。表示は統合報告書2025（33.9MB／168ページ）。OGPも integrated_ogp_2025_jp.jpg |
| sdb26_jp.pdf | 200 | 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT / ETag 5d99d52f54b74bd6c67520210d322c83-3 / S3 version ty4iDeHrXxAZHh87VnhCFAsDcIoO1yOy |
| sdb26_en.pdf | 200 | 9,687,236 / 同日 Last-Modified / ETag 22a9d9db33aa448a137fcdb2a4e484a7-2 / S3 version staEiHcf3aZRTRajvHOtLV8.oTtLJJb8 |
| sdb27_jp.pdf | 404 | 未掲。登録頁 dateStr 2026年06月29日。主な更新箇所は2026年6月。年2回（6月および9月） |
| 20-F_202603_final.pdf | 200 | 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT / ETag b0e64e363ef4dc1f9b21441333eb0c8d-2 / S3 version KsbQIrdqL4z.4I6gq4Qditi8YSQkRnQk |
| 20-FA_202603_final.pdf / 20-F_202603_final_amendment.pdf | 404 | 未掲。英登録頁 dateStr Jun. 11, 2026、表示 2026 Form 20-F（PDF: 5.01 MB / 264 pp.）。日登録頁 dateStr 2026年06月11日 |

登録頁: https://global.toyota/jp/ir/library/annual/ 、https://global.toyota/jp/sustainability/report/sdb/ 、https://global.toyota/en/ir/library/sec/ 、https://global.toyota/jp/ir/library/sec/

本パス: 第14パスが残していた注記3の外貨換算、売却目的の判定文、従業員給付の認識単位、株式報酬の測定単位。現金同等物の構成と棚卸のNRV定義も同節のため一次抽出。

## 注記3 外貨換算（F-12、IAS 21）

機能通貨は在外子会社・関連会社・共同支配企業ごとに定め、親の表示通貨は円。

取引: 発生日の為替で各社の機能通貨へ換算。外貨建ての金銭債権債務は報告期間末日のレート。公正価値測定の非金銭項目は公正価値測定日のレート。決済差および期末換算差は純損益。ただしその他の包括利益を通じて公正価値測定する資本性金融資産から生じる換算差はOCI。

在外営業活動体（機能通貨が円以外の子会社・関連会社・共同支配企業）: 資産・負債は報告期間末日レート、収益・費用は期中平均。ただし為替が大きく変動する場合は平均を使わない、と本文。換算差はOCIに認識し、財政状態計算書のその他の資本の構成要素に累積。支配・重要な影響力・共同支配を失う処分時に、当該営業活動体に係る累積換算差を資本から純損益へ組替。部分処分やヘッジ指定の追加規定は注記3の本見出しに無い。

## 注記3 現金及び現金同等物（F-13、IAS 7方針セル）

構成は手元現金、要求払預金、取得日から満期3か月以内で価値変動リスクが僅少な、現金に容易に転換できる短期投資。金額表は本見出しに無く、連結CF計算書の期末残高へ委譲（親パス既出の数値は再掲しない）。

## 注記3 棚卸のNRV（F-18、IAS 2）

測定は原価と正味実現可能価額のいずれか低い方。原価は購入原価・加工費・現在の場所および状態にするまでのその他の原価。原価計算は原則として加重平均。NRVは通常の事業過程における見積売価から、製品完成までの見積原価および見積販売費を控除した額、と本文。評価減の円額は注記3に無く、注記10にも評価減行は無い（親パス既出）。

## 注記3 売却目的の判定単位（F-18、IFRS 5方針。分類額は注記11へ）

分類対象は、継続的使用ではなく主として売却取引で回収する非流動資産または資産グループ。同時要件: (1) 1年以内の売却が高確率、(2) 現状のままで即時売却可能、(3) 適切な階層の経営者が売却計画にコミット。分類後は減価・償却を停止。測定は帳簿価額と売却費用控除後公正価値の低い方。処分グループの構成会社名・羽村除外は注記11（親パス既出）へ委譲し、注記3は判定文のみ。

## 注記3 従業員給付の認識単位（F-21〜F-22、IAS 19方針。円額は注記23）

制度は確定給付と確定拠出の両方。

確定給付: 債務の現在価値と勤務費用は、原則として制度ごとに予測単位積立法。純額は確定給付債務の現在価値−制度資産の公正価値。制度資産が債務を上回る場合に認識できる資産は、制度からの返還および将来拠出の減額という形で利用可能な経済的便益の現在価値を上限（資産上限）。当期勤務費用と純利息は純損益。過去勤務費用は発生時に純損益。再測定（数理計算上の差異を含む）は発生時にOCIへ認識し、直ちに利益剰余金へ振替。OCIに残留させない、と本文。

確定拠出: 従業員が勤務を提供した時点で、拠出の支払義務を純損益に認識。

注記4の見積り一覧は「Employee benefit obligations」を注記3本見出しと注記23へ委譲するだけで、割引率の数値や感応度は注記4本文に無い。

## 注記3 株式報酬の測定単位（F-23、IFRS 2方針。制度別株数は注記31）

注記3の本見出しが書く制度は、株式交付型ESOP信託。測定は付与日における当社普通株式の公正価値。費用は付与日から権利確定日までの権利確定期間にわたり認識。RSの年額上限・RSU代替・過年度付与表は注記31にあり、注記3の本段落には出てこない。

## 未処理

- 20-F/A（探した amendment URL は 404）。
- 2026統合報告・TCFD円額、SDB 9月定例PDF。
- 注記3金融商品の当初認識・認識中止・分類変更の残セル（ECL/収益は [[sources/20f-2026-notes-pass11]]）。
- TMCA PPE、日野工場別PPE・羽村精査確定・eLDT車名工場。
