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
- 2026-09-09 06:09–11:01 の詳細は各passファイルを正本とする（pass21–26）。

## 2026-09-09 JST 12:00 タイムボックス（1h分）
- 選定: (1)統合報2025。日PDF 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag不変。2026未掲。TCFD円額未掲。新事実なしのため(2)へ。
- (2) SDB6月PDF差替なし（sdb26_jp 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT）。sdb27 / sdb26_jp_09 / sdb26_jp_202609 404。貞宝6サイトは07:03既出。新事実なしのため(3)へ。
- (3) 20-F_202603_final 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT。20-F/A 404。新事実なしのため(4)へ。
- (4) toyota.com.au トップ403。TMCA車両PPE未掲。豪州競争法の公式登録は日野/ふそう側の製造拠点なしを一次で固定。(5)と併せて実施。
- 実施: 日野FY2025有報の羽村株式譲渡価額、ACCC/CCSクリアランス、ARCHION売出し完了と議決権。
- 新事実の核: 吸収分割は対価なし、トヨタへの株式譲渡は1,500億円。ACCC Not opposed 2025-09-10（51日、製造拠点なし）。CCS 400-140-2025-004、決定2025-10-07、s.54非抵触。売出受渡2026-07-29。売出後議決権 トヨタ19.9% / ダイムラートラック26.7%。売出前トヨタ 1,142,162,628株（41.43%）。
- 出力: `llmwiki/sources/hino-ir-pass27.md`。index / WORKLOG / _meta / sources/integrated-report / sources/hino-ir / topics/ifrs / topics/production-management / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB PDF、(3)20-F/A、(4)TMCA車両PPE、(5)1,500億円の着金日・工場別PPE・人員差分内訳・NZオークランド承認確定日・PL888・トラスティ氏名・近畿以外売却先商号・売出円単価。
