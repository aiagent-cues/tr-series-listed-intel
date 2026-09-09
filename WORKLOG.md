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

## 2026-09-09 JST 13:13 タイムボックス（1h分）
- 選定: (1)統合報2025。日PDF 35,488,119 / Last-Modified Fri, 03 Apr 2026 02:00:02 GMT / ETag不変。2026未掲。TCFD円額未掲。新事実なしのため(2)へ。
- (2) SDB6月PDF差替なし（sdb26_jp 11,691,278 / Last-Modified Mon, 29 Jun 2026 04:00:04 GMT）。sdb27 / sdb26_jp_09 / sdb26_jp_202609 404。新事実なしのため(3)へ。
- (3) 20-F_202603_final 5,259,321 / Last-Modified Thu, 11 Jun 2026 01:00:01 GMT。20-F/A 404。新事実なしのため(4)へ。
- (4) toyota.com.au トップ403。TMCA車両PPE未掲。新事実なしのため(5)へ。
- 実施: pass28未処理だったグリーンシュー行使株数。発行体IRに行使開示行は無し。一次は金商法27条の25の変更報告書No.2（報告義務発生2026-08-14、提出2026-08-21）。トヨタ S100YXR7 / ダイムラー S100YY0Y。
- 新事実の核: グリーンシューは上限全株 118,178,300株を行使。トヨタ 59,089,100株・単価249.6円、ダイムラー 59,089,200株・単価249.60円。行使通知2026-08-14、決済2026-08-19。行使後の発行済ベース保有は各25.00%（トヨタ 689,145,728＝A種175,512,774を含む / ダイムラー 689,145,660）。ロックアップ60ヶ月。7/31訂正は「その他の関係会社」追加。
- 出力: `llmwiki/sources/hino-ir-pass29.md`。index / WORKLOG / _meta / sources/integrated-report / sources/hino-ir / topics/ifrs / topics/production-management / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB PDF、(3)20-F/A、(4)TMCA車両PPE、(5)1,500億円の着金日・工場別PPE・人員差分内訳・NZオークランド承認確定日・PL888・トラスティ氏名・近畿以外売却先商号・15条5項別PDF。
