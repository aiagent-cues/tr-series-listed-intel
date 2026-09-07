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
- 2026-09-07 19:12〜2026-09-08 03:02 の累積は前コミット（直近は 20f-2026-notes-pass9〜pass19 / hino-ir-pass7）を正本とする。

## 2026-09-08 JST 02:21 タイムボックス（1h分）
- 出力: `llmwiki/sources/20f-2026-notes-pass19.md`。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。差替待ちなら注記3金融商品の認識中止、または(4)TMCA PPE、(5)羽村精査確定・eLDT車名工場。

## 2026-09-08 JST 03:02 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001_integrated_jp.pdf は404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 version H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は年2回（6月および9月）。主な更新箇所は2026年6月のまま。sdb27_jp.pdf は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。前パスが残した注記3認識中止・金融負債・デリバティブ方針は[[sources/20f-2026-notes-pass11]]既出のため再掲しない。(4) TMCA PPEは toyota.com.au Past Financial Reports に未掲（TFA年次のみ）。(5) 日野公式ニュースの未収録商品一次を抽出。
- 新事実の核: メルファ一部改良を2026-09-07発売。代表 RR2AJDV-E X UDAQC / A05C 162 kW / 6速AT / 41人 / 税抜 23,615,000円（税込 25,976,500）。ドア連動ニュートラル新設。路線バスは記事本文 2026-08-21（索引は8/19）。ブルーリボン 2WG-KV290Q5-QN7 / 4HK1-TCH 169 kW / 87人 / 税込 33,159,390。レインボー 2WG-KR290J6-PN7 / 4HK1-TCS 153 kW / 61人 / 税込 29,768,200。両件とも工場名・台数非掲。羽村精査確定・eLDT車名工場は仍未掲。
- 出力: `llmwiki/sources/hino-ir-pass7.md`。index / WORKLOG / _meta / sources/integrated-report / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。(4)TMCA PPE未掲。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 04:03 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001_integrated_jp.pdf は404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。主な更新箇所は2026年6月のまま。sdb27_jp.pdf は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。注記3認識中止は第11パス既出、注記35定期預金は第19パス既出のため再掲しない。第19パスが延期した非金融分割CFの税支払行を含む Item 5 非金融/金融分割P/L・CF・SFPを一次抽出。(4) toyota.com.au はメンテナンス表示。TMCA PPE未掲。(5)羽村精査確定・eLDT車名工場は仍未掲。
- 新事実の核: 非金融営業利益 2,923,556 / 金融 851,722。非金融営業CF 5,479,380・投資 +14,967・財務 △1,760,535。税支払 非金融 △1,159,061 / 金融 △81,619。期末現金 非金融 9,885,097 / 金融 2,774,524。金融資産 53,741,709（注記5と一致）。売却目的資産 2,016,804 は全額が非金融流動。
- 出力: `llmwiki/sources/20f-2026-notes-pass20.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。(4)TMCA PPE未掲（サイト復帰待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 04:16 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001_integrated_jp.pdf は404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。主な更新箇所は2026年6月のまま。sdb27_jp.pdf は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。分割CFは第20パス既出のため再掲しない。第4パスが残した顧客所在台数表と地理P/Lの製品・金融分解、Item 4.BのOther（オセアニア含む）3期外部売上を一次抽出。(4) toyota.com.au は403（Cloudflare）。TMCA PPE未掲。(5) 日野2026-09-03は国際物流総合展出展案内のみ。羽村精査・eLDT車名工場は仍未掲。
- 新事実の核: 顧客所在台数 日本 1,991→2,082 / 連結 9,362→9,595。事業所在の日本 3,932＝顧客日本+輸出。Other外部売上 4,169,494→4,373,919→4,606,482。Other営業利益 252,626→328,966。北米金融売上 2,838,119、欧州金融 892,474。
- 出力: `llmwiki/sources/20f-2026-notes-pass21.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。(4)TMCA PPE未掲（サイト復帰待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。
