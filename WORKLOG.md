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

## 2026-09-07 JST 16:24 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、dateStr 2026年06月29日、フッタ2026-08-13。9月定例未掲。
- 実施: (3) 20-F/Aは404のまま。親の未処理だった注記13–15の増減明細を一次抽出。同一SEC登録頁の Form SD（提出2026-05-29・対象暦年2025）も未登録だったため併せて一次抽出。(4) TMCA PPEは非掲。注記13も国別内訳なし。
- 新事実の核: PPE取得原価 2026-03-31 36,571,364 / 減価累計 19,504,000 / 帳簿 17,067,364。FY2026減損 8,825（建物3,981+機械4,844）。売却目的振替ネット 482,118は注記11と一致。OLネット 7,855,554（うち賃貸ROU 5,546,865）。借手ROU 901,232 / 負債PV 711,013 / FY2026キャッシュアウト 484,931。無形ネット 1,392,755。Form SDは対象サプライヤー回答率96.6%、TMNA接触124製錠所、Annex突合226行（Gold93/Ta41/Sn55/W37）、JaCER加入、民間監査なし。
- 出力: `llmwiki/sources/20f-2026-notes-pass6.md` / `llmwiki/sources/form-sd-2026.md`。index / WORKLOG / _meta / sources/integrated-report / topics/esg / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。差替待ちなら注記18–21残セル、または(4)TMCA PPE、(5)羽村精査確定・eLDT車名工場。

## 2026-09-07 JST 16:11 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT）。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。登録頁は「主な更新箇所（2026年6月）」、フッタ2026-08-13。9月定例未掲。(3) 20-Fは pass5と同一。amendment URLは404。(4) toyota.com.au Past Reports はTFAのみ。TMCA PPE非掲。
- 実施: (5) 日野IR残件へ移行。ARCHION 2026-08-26「統合プラットフォーム戦略」一次と、同日のレンジャー／ファイター公式、8/25 CJPT-Asiaを抽出。
- 新事実の核: MDTは日野既存PFをふそうへ供給（レンジャー一部改良＋ファイター新型）。eLDTは逆向きで2026年度内生産開始予定。中長期はLDT/MDT/HDTの統合PF新規開発、ブランドは継承。ファイターエンジンはA05C 5.1L直4・全車177kW。東京地区税込 2WG-YC2ABA 11,009.9千円 / 2WG-YE2ACG 16,106.2千円。GVW11t・14tダンプと8t・11tの4WDを新設。販売は9月初旬順次。日野訂正はスキャニングクルーズの「全車速追従」括弧削除のみ。CJPT-Asiaは日野参画の代替でARCHIONがタイ法人へ参加（社長 中嶋裕樹）。工場別PPE・羽村精査確定は未掲。
- 出力: `llmwiki/sources/hino-ir-pass6.md`。index / WORKLOG / _meta / sources/hino-ir / sources/integrated-report / topics/production-management / topics/scm / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/A、(4)TMCA PPEは公式未掲。差替待ちならeLDT車名・工場確定、または羽村精査確定・工場別PPE。

以前のブロックはヒストリの既存コミットに残す。
