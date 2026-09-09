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
- 2026-09-09 12:00 の詳細は hino-ir-pass27 を正本とする。
- 2026-09-09 12:03 の詳細は hino-ir-pass28 を正本とする。
- 2026-09-09 13:13 の詳細は hino-ir-pass29 を正本とする。

## 2026-09-09 JST 14:21 タイムボックス（1h分）
- 選定: (1)統合報2025。日PDF 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag不変。2026未掲。TCFD円額未掲。新事実なしのため(2)へ。
- (2) SDB6月PDF差替なし（sdb26_jp 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT）。sdb27 / sdb26_jp_09 / sdb26_jp_202609 404。新事実なしのため(3)へ。
- (3) 20-F_202603_final 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT。20-F/A 404。新事実なしのため(4)へ。
- (4) toyota.com.au は13:13時点の403からCloudflare HTML 366,699へ。投資家サブパスも同サイズ。TMCA車両PPE未掲。新事実なしのため(5)へ。
- 実施: 未処理だった「PL888」とNZオークランド承認。一次は日野FY2026第3四半期短信日英と2025-12-25適時開示。
- 新事実の核: PL888は事件番号ではない。短信特別損失の PL訴訟和解金 **888百万円**（英: product liability）。NZは2025-03-03パーマストンノース支部提起、**2025-08-05オークランド支部へ移送**。和解金 NZD 10.9 million（開示概算980百万円）、計上は **959百万円**。短信時点で承認確定日未掲。発行体IRにCIV/PL番号は無い。
- 出力: `llmwiki/sources/hino-ir-pass30.md`。index / WORKLOG / _meta / sources/integrated-report / sources/hino-ir / topics/ifrs / topics/production-management / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB PDF、(3)20-F/A、(4)TMCA車両PPE、(5)1,500億円の着金日・工場別PPE・人員差分内訳・NZ承認確定日の発行体経過開示・PL訴訟の裁判所・トラスティ氏名・近畿以外売却先商号・15条5項別PDF。
