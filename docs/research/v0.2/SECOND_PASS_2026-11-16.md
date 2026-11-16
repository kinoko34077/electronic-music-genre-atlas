# Deep Research v0.2 — 2026-11-16 第2回再調査の結果と引継ぎ

**受入判定: 未達。GitHub直接保存への是正記録。**

## 原報告の実行状態と制限
- Deep Research job `plan-2026-11-16T11:55:00Z-v0.2` は終了（finished_successfully）だが、その**内部計画はstep-1完了・step-2進行中・step-3〜5未着手**。これは「依頼した研究が完了した」と同義ではない。
- 原報告本文には51カテゴリの調査所見、曲名付き候補と置換案、参考資料が直接表で掲載された。**510行すべての曲別データは提示されていない。**
- 原Deep ResearchはGitHubへの書込手段がなく、PRやIssueを作っていないと明言。ZIPを生成していない。
- この回復作業では、ユーザー/後続AIが読めるよう原報告本文の**実名付き曲行174件**をGitHub内へ保存した。既存68件を黙って削除・選定せず、別台帳のまま残した。採用0、実再生0、独立再監査0。

## 成果物（ZIPではない）
- [第2回候補台帳 CSV](../../../data/v0.2/deep_research_second_pass_2026-11-16.csv) — **174曲行・46カテゴリに実名あり**（初期98・現在76）。元レポートの主張に基づき出典候補URL、グレード、処置とステータスを持つが、すべて`PROVISIONAL_NOT_ACCEPTED`。
- [件数・欠損状態 JSON](../../../data/v0.2/deep_research_second_pass_manifest.json)。
- [前回68候補 CSV](../../../data/v0.2/track_leads.csv) — 引き続き別台帳、上書きしていない。
- [研究Issue #1](https://github.com/kinoko34077/electronic-music-genre-atlas/issues/1)。
- [仕様正本](../../SPECIFICATION.md)。

## 51系統の補足と分類判断（原報告の要約、再検証前）
- **#03 Complextro**: 初期5曲は曲単位候補がある一方、2022–26の現代5曲が資料で成立せず。
- **#19 HexD**: 成立史の概略のみ確認、採用を支える10曲分の強い記事本文証拠なし。
- **#20 Sigilkore／#22 Krushclub**: Odetari/Lumi Athenaを現代Sigilkoreへ機械分類せず、Krushclubへ再分類検討。
- **#27 Dariacore／#28 Hyperflip**: 別系統の名では重複使用が多く、無条件で同じ曲を複製しない。
- **#36 Axxcelerationist/Neo Rage／#50 Hyper Melodic Tearout**: 固定ラベル維持、独立ジャンル資料不足として分類例外候補。10曲で数合わせしない。
- **#39 Original Phonk／#40 Drift Phonk**: 歴史・曲例の混同を防ぎ、独立に扱う。
- **#42 Funk Automotivo／#43 Brazilian Phonk**: 重複するが同一とはしない。
- **#49 Cinematic Bass**: Danny Olson中心の限定的に持続するスタイル名として資料があるが、大規模独立ジャンルとしての地位は主張しない。
- **#04 Glitch Hop (Bass)／#51 Glitch Hop (実験Hip Hop)**: 独立して評価。

## 以前より具体的になった置換・新規候補の例
| ID | 今回の新候補・再評価 | 以前の弱い案からの処置 | 原報告の出典URL |
|---|---|---|---|
| G01-N-02 | Cesco & Hamdi — Swing King (2024) | SHOSH等のアーティスト紹介のみを代表性とみなさず置換候補 | [Beatportal](https://www.beatportal.com/articles/781122-140-deep-dubstep-grime-the-top-selling-tracks-artists-and-labels-of-2024) |
| G08-N-01 | STAYC — Teddy Bear (2023) | EDM全般の年間ランキングだけに依存したFuture Bass候補からの差替案 | [SONAA](https://sonaa.ca/en/styles/bass/future-bass/) |
| G14-N-05 | Sub Focus & bbyclose — On & On (2025) | D&Bの現代選定を2025年情報へ更新 | [Beatportal](https://www.beatportal.com/articles/1209892-drum-bass-the-top-selling-tracks-artists-and-labels-of-2025) |
| G20/G22 | Odetari／Lumi Athena系 | SigilkoreからKrushclubへの分類再評価 | [Pitchfork](https://pitchfork.com/thepitch/luci4-unleashed-a-generation-of-glitchy-underground-rap/) |
| G44-N-01 | CRRDR — SORRY BUT THE LATINCORE (2025) | ラテン系融合の曲別候補 | [CRRDR公式](https://crrdr.bandcamp.com/track/sorry-but-the-latincore) |

## 未解決・再開時の最初の動作
1. 今回の表は**174件**。51カテゴリ×10曲＝510の正規完成データではない。実名曲行が0だった5系統: 19, 23, 28, 36, 50。これらも履歴調査の対象ではあったが、曲単位根拠まで引継げていない。
2. 曲別に出典記事を実読し、**記事がその特定の曲の代表性を明示するか**判定。SONAA等のジャンルガイドを引用しただけなら掲載曲の適合も別途確認。レポートのA/Bは`grade_as_reported`であり採用根拠の検証済みではない。
3. 曲のオリジナルリリース年、版、録音に対する権利者の個別URLを確認。Bandcampの`/album/`は原則として曲直接URLではないため格下げし、音源ページの実再生・日本での可用性も別々に確認。
4. 51×10の確定枠のうち実名候補がまだない全slotを識別し、新曲を探して追加。失敗時も研究Issueに記録。元の258未充足枠IDは引継ぎ失敗により不明であり推測補完しない。
5. 開始・結果・blocked/next actionをIssue #1で管理し、バッチ単位でブランチ→PR→mainへ保存。**ZIP・一時生成物を引継ぎ手段に使用しない**。
