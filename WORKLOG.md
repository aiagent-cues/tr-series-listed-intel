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

## 2026-09-07 JST 10:36 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、9月定例未掲。(3) 20-Fは pass5と同一。第13パス残のp73-87は第4・5パス済みなため、第4パス要約残の印刷p68-72を継続。
- 実施: 統合報告2025日PDF印刷p68-72を英PDFテキスト層と並読。TTRI/TTDCは本冊外の公式一次で正式名を確定。
- 新事実の核: TME法人はNV/SA。SinoHytecはBeijing SinoHytec。中国中長期計画2021-2035でFCトラック年間数万台。GLP中国2024-11。FOR-U / Shenzhen Dekun で2025年からFC大型50台（海外初幹線トライアル）。Daimler Truck Holding AG 2023-05 / BMW 2024-09。Hyliko累計6万km・パリ2024五輪。第3世代FCはセル共通化、日2026年度=英fiscal 2027。本社工場水素パーク2026、5–20MW水電解。万博西ゲートセブンイレブンの水素カートリッジ。UCC水素焙煎コーヒー。CJPT 2021年設立。METI 2025-05で5重点地域。日は福岡含む / 英METI文は福岡落ち。FCトラック2025-12末約200 / FCバス約180。TTRI=公益財団法人豊田都市交通研究所。TTDC=トヨタテクニカルディベロップメント株式会社（2006-04）。
- 出力: `llmwiki/sources/integrated-report-2025-pass14.md`。index / WORKLOG / _meta / topics/esg 更新。
- 次: 英p71の福岡落ち訂正有無。印刷p88以降の社長交代実言差分。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 10:18 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、9月定例未掲。(3) 20-Fは pass5と同一。PDF差替は無いが、第12パス残の5ブランド残年表が未抽出のため(1)を継続。
- 実施: 統合報告2025日PDF印刷p26-37（PDF p27-38）を英PDFテキスト層と並読。
- 新事実の核: 初代センチュリー完成1967（開発開始1963は既出）。開発現場は関東自動車工業東富士独身寮。終戦㼪カ月後の自動車協会（英名 Automobile Business & Culture Association of Japan の前身、豊田が現会長）。トヨタ「あなた目掛けて」。IMV Originはアフリカ農村・未完成出荷。K-OPENは軽FRオープン。KAYOIBAKOはダイハツ小/トヨタ大。LSを1989旗艦からLuxury Spaceへ再定義、LSコンセプトは6輪。海は自律カタマラン。2025-12-05裸野Woven CityインベンターガレージでGR GT/GR GT3/LFA Concept WP。初のアルミ一体骨格・FR。約14年前ペブル「退屈」評。ニュル約20年前は中古スープラ+GAZOO Racing、2007年公式初は中古アルテッツァ。燃料は従来+e-fuel、LFA Conceptは電動。マスタードライバー就任は「15年前」。
- 出力: `llmwiki/sources/integrated-report-2025-pass13.md`。index / WORKLOG / _meta / topics/esg 更新。
- 次: TTRI/TTDC正式名は本冊に無し。印刷p73-77水素残図、p78-80 SDV表、p81-87 RAV4装備。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 09:00 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、9月定例未掲。(3) 20-Fは pass5と同一。PDF差替は無いが、第11パス残の印刷p19-24が未抽出のため(1)を継続。
- 実施: 統合報告2025日PDF印刷p19-24（PDF p20-25）を英PDFテキスト層と並読。
- 新事実の核: 2テーマ（スポーツカー/ロングセラー）。86・スープラは他社協業、自前はGRヤリス。変革3本柱はTNGA・カンパニー制・マスタードライバー。2021-12 TGR体制発表。スーパー耐久は蒸郡で小林可夢偉と同乗。WRC再開はトミ・マキネン、現代表ラトバラが今シーズン三重冠。2025-06ニュル6年ぶり、109号車GRヤリスがクラス優勝、DAT実証、モリゾウ走走。陸上部1937、柔道1938、1951全トヨタ大会、1970年代35部。IOC/IPCは2017-パリ2024の初モビリティWP、GTTA約300/50カ国、SOグローバルパートナー2017。
- 出力: `llmwiki/sources/integrated-report-2025-pass12.md` をplaceholderから本文化。index / WORKLOG / _meta / topics/esg 更新。
- 次: TTRI/TTDC正式名と5ブランド残年表。(2)(3)(4)は差替PDF/掲出待ち。

## 2026-09-07 JST 07:28 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。第10パス残の系譜図残りノードを処理。
- 出力: `llmwiki/sources/integrated-report-2025-pass11.md`。

## 2026-09-07 JST 07:15 タイムボックス（1h分）
- 出力: `llmwiki/sources/integrated-report-2025-pass10.md`。

## 2026-09-07 JST 06:03 タイムボックス（1h分）
- 出力: `llmwiki/sources/integrated-report-2025-pass9.md`。

以前のブロックはヒストリの既存コミットに残す。
