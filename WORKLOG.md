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
- 新事実の核: 認証事案は日野2022-03・ダイハツ2023-04。TMCはMLIT指示2024-01-26、報告2024-05-31（7車種・2014年以降）、春正命令2024-07、新規8件/7車種、再発防止2024-08。米国関税は2025年引き上げ後提出日時点も存続。発行可能 50,000,000,000 / 発行済 15,794,987,460（2026-03-31）。自己株 1,200,000,000株を 2026-06-30 消却発表（約 7.6%）。単位株 100株。振替代理 三菱UFJ信託。FEFTAは財務省リスト 2025-07-15 でコア業種指定業（2025-04-04公布 / 2025-05-19施行）。
- 出力: `llmwiki/sources/20f-2026-notes-pass31.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Item 4.B Legal Proceedings 本文と Item 10.D Specified Foreign Investor 以降・Item 10.E–H。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 13:10 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。未転記だった Item 4.B Legal Proceedings 本文と Item 10.D Specified Foreign Investor 以降・Item 10.E–J を一次抽出。(4) toyota.com.au は403。(5) 日野適時開示2026頁に9月新規行なし。20260908-* は404。
- 新事実の核: タカタ集団訴訟の係属地はブラジル・アルゼンチン。豪州DPFは High Court 2024-11-06 が価値低下額計算を一審差戻し、その他請求は一審係属、見積流出は重要性なし。タイ子会社贈賄は2020-04自己申告、2025-06にDOJ・SECが調査終了。日野関連のTMC連結費用は FY2025 281,140百万円。Specified Foreign Investor は外国政府の情報収集に協力義務を負う主体。Specified Core Business Operator への取得は同等主体でも免除不可。不適格は制裁歴・一定の国有企業・SFI。2026年税制改正（公布2026-03-31）で防衛増税を導入し復興増税を縮小、上場配当の非居住者源泉は全体15.315%/20.42%を2047-12-31まで維持（内訳切替は2027-01-01）。米日条約のポートフォリオ配当は原則10%。10.F/G/I/Jは Not applicable。
- 出力: `llmwiki/sources/20f-2026-notes-pass32.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Item 10.E 譲渡益・ADS・相続と Item 11 本文表。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 14:06 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。未転記だった Item 10.E 譲渡益・ADS・相続と Item 11を一次抽出。Item 11本文に数値表は無く注記20参照のみのため Item 12.D ADS手数料も抽出。(4) toyota.com.au は403。(5) 日野適時開示2026頁に9月新規行なし。20260908-004740〜004754は404。
- 新事実の核: 日本国外でのポートフォリオ売却益は原則非課税。Eligible U.S. Holderは必要提出を行えば条約免除。相続税・贈与税は取得者・被相続人・贈与者が非居住でも課され得る。ADS条約軽減は配当支払前と1通と基準日から8カ月以内の1通。TMCはFY2026についてPFICではないと考えるが保証しない。backup withholding 現行24%。branch profits tax 原則30%。Item 11の数値表は注記20が正本。預託機関 BNY Mellon。FY2026に預託機関がTMC/指示先へ支払った合計 $980,058.75。将来の預託機関負担上限 年$300,000。Item 12.A–C / 13 / 14 は Not applicable または None。
- 出力: `llmwiki/sources/20f-2026-notes-pass33.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Item 15以降の未転記があれば別パス。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 15:10 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。注記1–36と Item 10–16 本文は既出のため再掲しない。pass30が番号のみ残した添付 Exhibit 11.1（倫理規範）・15.1（監査人同意）・19.1（内部者取引方針、2026-01改正）を一次抽出。(4) toyota.com.au は403。(5) 日野ニュース20260908-004740〜004755は404。
- 新事実の核: 倫理規範施行 2025-11-01。適用は取締役と執行役員（社長・副社長・フェローを含む）。社外法律事務所の SPEAK-UP。免除は取締役会決議のみ。内部者取引方針は2026-01改正、所管は秘書部と Disclosure Committee。閉鎖期間は4/7/10/1月1日から約5週間。取締役の売買は翌月15日までに内閣総理大臣へ報告（米ADS含む）。内部者名簿は5年保管しFCAへ提出し得る（LSE上場、DTR 2.8）。自己株取得の日次買付情報はCFO・経理担当以外に抑制を適用しない。退任後は公表まで、ただし1年経過で解除。Exhibit 15.1 は Form F-3 No. 333-288168 への組込同意（PwC Japan LLC、名古屋、2026-06-10）。
- 出力: `llmwiki/sources/20f-2026-notes-pass34.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は Exhibit 19.1の重要事実定義表と97.1クローバック本文（FY2024参照組込み）。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 16:00 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。未転記だった Exhibit 19.1 の会社関係者範囲・重要事実数値基準・公表（24時間）と、FY2024 20-F参照組込みの Exhibit 97.1 および Item 6.F を一次抽出。(4) toyota.com.au は403。(5) 日野適時開示2026頁に9月新規行なし。20260908-004740〜004760は404。
- 新事実の核: 会社関係者は3%株主・許認可公務員・契約相手を含む。元関係者は1年、公開買付関係者は6か月。損害は純資3%、提携は売上年10%またはJV資産×持分が純資330%、増資総額1億円、配当増減20%、分割増加10%。バスケット条項あり。公開買付け等は総議決権5%。社内公表は媒体2社以上・TDnet・EDINETのいずれかから24時間（金商法の媒体ルートは12時間）。Item 6.F は None。97.1は2023-11-29採択、運用は Executive Compensation Meeting、無過失、補償禁止、対象は直前3完了事業年度、2022-11-28前の日本法に反する場合は非執行可。原典は 20-F_202403_final.pdf（4,164,579 / Last-Modified 2024-06-25 11:40:01 GMT）。
- 出力: `llmwiki/sources/20f-2026-notes-pass35.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。残は開示委員会の重要事実基準別表（本20-F非添付）。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定・eLDT車名工場・工場別PPE。

## 2026-09-08 JST 17:00 タイムボックス（1h分）
- 選定テーマ: 優先(1) 統合報告2025。登録頁に2026未掲。2026_001 日英とも404。日PDF HEAD不変（35,488,119 / Last-Modified 2026-04-03 02:00:02 GMT / ETag 6f429b141f4b80d241e2ebd43b35c08f-7 / S3 H0V.jlEk4DcD64PpuCNSCAcT5bg0nluM）。英 32,257,390 / 同日。TCFD円額未掲。(2) SDB sdb26_jp HEAD不変（11,691,278 / 2026-06-29 04:00:04 GMT）。sdb27 / sdb26_jp_09 は404。9月定例未掲。
- 実施: (3) 20-F/Aは404。英登録頁 Amendment 列は No。開示委員会別表は本20-F非添付。(4) toyota.com.au は403。(5) 日野ニュース09-08なし。日野拠点頁が参照する移管後公式 https://www.toyota-hamura.co.jp/ を一次抽出。
- 新事実の核: トヨタ自動車羽村は創立2026-04-01、資本金85億円、TMC100%、従業員5,060名（2026-04、派遣含む）、敷地750,000㎡、代表 青木是篤、取締役 川尻忠司・野村英司、監査役 伴智明。事業はTMC・日野からの車両・部品受託。現行車種はLC250・高機動車・1.5tトラック・ダイナ・デュトロ・デュトロZEV。2024年度生産191,472台。日野拠点頁の事業所は日野/新田/古河の3拠点。お客様テクニカルセンターは羽村テストコース内として日野頁に残る。eLDTという車名は羽村製品頁に非掲。
- 出力: `llmwiki/sources/hino-ir-pass8.md`。index / WORKLOG / _meta / sources/integrated-report / topics/ifrs / sources/hino-ir / _last_run 更新。
- 次: (1)2026統合報・TCFD円額、(2)9月SDB、(3)20-F/Aは公式未掲。開示委員会別表は本20-F非添付。(4)TMCA PPE未掲（サイト帰還待ち）。(5)羽村精査確定値・古河/新田/ARCHION工場別PPE最新確定・eLDT車名。
