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
- 2026-09-07 19:12〜2026-09-08 04:16 の累積は前コミット（直近は 20f-2026-notes-pass9〜pass21 / hino-ir-pass7）を正本とする。
- 2026-09-08 05:20〜11:20 の累積は 20f-2026-notes-pass23〜pass30 を正本とする。

## 2026-09-08 JST 12:06 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001_integrated_jp.pdf は404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。主な更新箇所は2026年6月のまま。sdb27_jp.pdf は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。注記1–36と Item 15/16 は既出のため再掲しない。未転記だった Item 3.D 個別事象と Item 10 定款・単位株を一次抽出。(4) toyota.com.au は403。(5) 日野適時開示2026頁に9月新規行なし。20260908-* は404。
- 新事実の核: 認証事案は日野2022-03・ダイハツ2023-04。TMCはMLIT指示2024-01-26、報告2024-05-31（7車種・2014年以降）、春正命令2024-07、新規8件/7車種、再発防2024-08。米国関税は2025年引き上げ後提出日時点も存続。発行可能 50,000,000,000 / 発行済 15,794,987,460（2026-03-31）。自己株 1,200,000,000株を 2026-06-30 消却発表（約 7.6%）。単位株 100株。振替代理 三菱UFJ信託。FEFTAは財務省リスト 2025-07-15 でコア業種指定業（2025-04-04公布 / 2025-05-19施行）。
- 出力: `llmwiki/sources/20f-2026-notes-pass31.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Item 4.B Legal Proceedings 本文と Item 10.D Specified Foreign Investor 以降・Item 10.E–H。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定セeLDT車名工場・工場別PPE。

## 2026-09-08 JST 18:09 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。開示委員会別表は本20-F非添付。(4) toyota.com.au は403。(5) 日野ニュース09-08なし。未転記だった古河工場の自然共生サイト（HINO TOPICS 2026-08-10）と、会期初日のHCS国際物流総合展（ニュース 2026-09-03）および HCS 会社概要を一次抽出。
- 新事実の核: 古河は大型・中型トラック製造の中核。自然共生サイト認定 2026-06-30、認定証授与 2026-07-29（さいたま新都心合同庁舎）。ビオトープKOGAは2024-12、池105㎡「みんなの池」、雨水タンク4基（1基8〜9t、満水30〜35t）、植樹約1万本（2026-08）、WG 10→41名。HCSは1986-10-01設立、資本金30百万円、従業員559名（2026-04-01）、年商22,897百万円（2025年度）、代表 岡田克巳。Logitaは日野・三菱ふそうのコネクテッド全国50万台。展示会は2026-09-08〜11、東京ビッグサイト W4-J27、入場3,000円（事前登録無料）。
- 出力: `llmwiki/sources/hino-ir-pass9.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。開示委員会別表は本20-F非添付。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定値・新田/日野/ARCHION工場別PPE最新確定セeLDT車名。
