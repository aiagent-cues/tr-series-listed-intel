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
- 2026-09-08 05:20〜11:06 の累積は 20f-2026-notes-pass23〜pass29 を正本とする。

## 2026-09-08 JST 11:20 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001_integrated_jp.pdf は404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。主な更新箇所は2026年6月のまま。sdb27_jp.pdf は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。注記1–36は第29パス既出のため再掲しない。未転記だった Item 15 ICFR、Item 16A–16E・16K、Exhibit 12.1/13.1/15.1 を一次抽出。(4) toyota.com.au は403。(5) 日野適時開示2026頁に9月新規行なし。20260908-* は404。
- 新事実の核: ICFRはCOSO 2013で2026-03-31有効、FY2026中の重要変更なし。PwC Japan LLC（PCAOB 2743、2006年〜、Nagoya、報告書日 2026-06-10）。監査等委員会に financial expert を置かないと決定。PwCネットワーク報酬 FY2026 9,435（Audit 8,780）。期末後自己株TOB 1,192,330,962株×3,067円≒ 3.65兆円（2026-03-31〜04-27）。SOX 302/906は近健太CEO・宮崎洋一CFO、2026-06-10。同意書の組込先 Form F-3 333-288168。重要サイバー事故は未発生と本文。
- 出力: `llmwiki/sources/20f-2026-notes-pass30.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Item 3.D リスク個別と Item 10 定款単位株。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。
