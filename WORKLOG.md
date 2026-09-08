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
- 2026-09-08 12:06〜17:00 の累積は前コミット（20f-2026-notes-pass31〜pass35 / hino-ir-pass8）を正本とする。
- 2026-09-08 18:09 / 18:23 の累積は hino-ir-pass9 / pass10 を正本とする。

## 2026-09-08 JST 19:11 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。(4) toyota.com.au は403。(5) 日野ニュース09-08なし。未転記だったFY2026半期報告書（提出 2025-11-14、時点 2025-09-30）を一次抽出。
- 新事実の核: 売上高 742,859 / 営業利益 38,073 / 親会社帰属中間純利益 22,502。連結有形 431,821。研開 27,802。羽村SPA 2025-06-10、譲渡価額 1,500億円、新会社資本金 1円、FAはデロイトトーマツFA。ふそう本社 川崎市中原区大倉町10、資本金 35,000（2024-12-31）。ARCHION取締役会9名予定・CxO名簿・ロックアップ60ヶ月。カナダ 55百万CAD（裁承認 2025-05-06/06-02）、米刑事 521.76百万USD、米民事 442.50百万USD、加州民事 236.50百万USD、豪州 87百万AUD（維州上級裁承認 2025-07-18）。
- 出力: `llmwiki/sources/hino-ir-pass11.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定値・FY2026有報の移管後工場別PPE・ARCHION側工場PPE・eLDT車名。
