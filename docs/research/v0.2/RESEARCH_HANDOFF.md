# v0.2 Deep Research 引継ぎ正本 — 2026-11-16

**状態:** 未完了。研究用の可視レポートから候補を復元して、リポジトリ上に直接保存した。**v0.2の510曲完成版ではない。**

## 今回の是正

ユーザーの指定により、Deep Researchの後続作業の**引継ぎ先はこのGitHubリポジトリのみ**とする。独立ZIP・ローカル生成物・Chat本文だけで成果を保持しない。ユーザーも直前の成果物ZIP/CSVを確認できていないため、それらを提出済み・利用可能・import済みと扱わない。

- 研究基準: [SPECIFICATION.md](../../SPECIFICATION.md)
- 所有Issue: [#1](https://github.com/kinoko34077/electronic-music-genre-atlas/issues/1)（進捗・根拠・未達・次Action）
- 固定510枠の旧資料: [review_queue_2026-11-15.csv](../../../data/review_queue_2026-11-15.csv)（すべてCANDIDATE_UNVERIFIED）。
- **v0.2の研究候補**: [data/v0.2/track_leads.csv](../../../data/v0.2/track_leads.csv)、[manifest.json](../../../data/v0.2/manifest.json)。
- 直前の分類の参考レビュー: [Deep Research round 1](../DEEP_RESEARCH_ROUND1_REVIEW_2026-11-16.md)。

## v0.2の報告状態と、実際に保存できた状態を分離

| 項目 | 元のDeep Researchによる報告 | このGitHub引継ぎで実際に確認できた内容 |
|---|---|---|
| 最初のv0.2 | 252 SELECTED / 258 UNFILLED | **原本CSV/JSONが手元に無いため、行レベル未検証** |
| v0.2改訂版 | 6 STRICT_SELECTED、202 A/B根拠ありでURL待ち、4 Cのみ、278 A/B不足、20 分類例外（計510） | **数字はレポート記載値。個別の208行は引継げていない** |
| 今回リポへ保存 | 可視レポートに曲名が明記された候補を再録 | **68件、うち初期30・現在38、15系統**。全件 NEW_LEAD_UNVERIFIED |
| 正式採用・再生確認 | 改訂報告でも実再生0 | **今回の採用0・曲単位出典の追加実読確定0・実再生確認0** |

**重要な制約:** 一時生成された `electronic_music_genre_research_v0.2.zip` と `electronic_music_genre_research_v0.2_revised.zip`、およびそのCSV/JSONはこの会話・コンテナ・ユーザーの確認可能環境から取得できない。ローカルにある `electronic_music_genre_research.zip` は**旧2026-11-14資料**であり、v0.2ではない。従って以前の258未充足枠を列単位で再構成したり、208件すべての曲名を作ったりしていない。

## 研究上残された具体的課題

1. **引継ぎ断絶の回復:** v0.2改訂の208 A/B claimの実データは未取得。今後の作業では本リポ内に保存済みの候補・根拠台帳を開き、新しい根拠調査を**直接同じリポにcommit**しながら進める。元ファイルが得られた場合もファイル差分を検証したうえでPR importする。
2. **優先調査:** `track_leads.csv`の各行で実際に記事本文に曲名があるかを再調査してA/B/C判定、原曲/版と初出年・正規個別URLを照合する。最初の状態 `NEW_LEAD_UNVERIFIED` は格付け済みを意味しない。記事がジャンル史やアーティストについて語るだけなら曲別根拠として不採用。
3. **258枠問題:** 旧v0.2の258 UNFILLEDの正確なslot-ID対応は**不明**。次の調査は推測で258枠だけを変えず、既存の固定510枠に照らして実際にA/B根拠がある曲へ置換する。数値の差はエクスポートが取れてから検証する。
4. **分類例外:** #36 Axxcelerationist/Neo Rage、#50 Hyper Melodic Tearout等は独立ジャンル成立が弱い。架空の10曲で埋めず分類そのものを資料で検証。#04と#51のGlitch Hopも区別。
5. **根拠・人気:** Reddit支持・引用数・言及頻度等は実際のURL、発表日時、独立性と取得日が確認できるまで`null`。推定値の穴埋めは禁止。
6. **採用ゲート:** A/B曲別代表性の出典＋初出年・正確な録音版＋権利者の個別音源URL＋再生検証状態を個別に記録。出典確認、音源URL確認、実再生、正式採用は別状態。
7. **作業の保存単位:** 調査開始時にIssue #1へ範囲と前進位置を記録し、ジャンルまたは20〜50候補程度の検証単位で`data/v0.2/`の主台帳を更新、専用ブランチ→PR→mainの順に受入する。**次回にZIPの所在を質問する状態に戻さない。**

## 可視レポートからの主な出典・研究対象

- Complextro初期: [Pitchforkの歴史記事](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/)および[UnderOwl](https://underowl.net/en/genre/complextro)。Spitfire/Shave Itの曲名言及は先行研究で再監査済みだが今回の全候補を受け入れたものではない。
- UK Dubstep初期・現代: [DubstepGuide](https://dubstepguide.net/genres/uk-dubstep/)、[DJ Mag 2024 tracks](https://djmag.com/features/dj-mags-top-tracks-of-2024)、[UKFのSHOSH](https://ukf.com/read/catching-up-with-shosh/)。
- Drum & Bass: [SonAA](https://sonaa.ca/en/styles/breaks/drum-and-bass/)、[2024 scene overview](https://dropthebass.co/history/2024)。単なるシーン選曲がジャンル史上の代表性かは要確認。
- Future Bass: [EDM.com 2025 best tracks](https://edm.com/industry/best-edm-tracks-of-2025/)。**EDM全般のランキング記事はFuture Bassという曲別根拠にならない**。
- Modern Tearout: [Dubstep FBI](https://www.dubstepfbi.com/post/premiere-listen-to-the-rotten-new-yvm3-stvg-song-before-it-destroys-the-universe)、[EDM.com](https://edm.com/music-releases/svdden-death-yvm3-dissent/)。
- Trance初期: [Roland guide](https://articles.roland.com/listening-guide-essential-early-trance/)。
- Dariacore: [Pitchfork 2025](https://pitchfork.com/thepitch/remember-jane-removers-mashup-genre-dariacore-its-blowing-up-in-japan-now/)。
- Plugg: [Pitchfork MexikoDro](https://pitchfork.com/thepitch/an-interview-with-mexikodro/)、[The FADER Slime Dollaz](https://www.thefader.com/2025/03/19/slime-dollaz-dj-slimebxll-pesos-song-review)。
- Memphis Rap: [VPM/NPR](https://www.vpm.org/npr-news/npr-news/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)。
- LatinCore: [Mixmag CRRDR](https://mixmag.net/feature/the-mix-021-crrdr-dj-latin-hardcore-interview-colombia-berlin)、[PAPER CRRDR](https://www.papermag.com/crrdr-trant)、[CRRDR Bandcamp個別曲](https://crrdr.bandcamp.com/track/sorry-but-the-latincore)。
- Hardtekk/TikTokTekk: [Pitchfork 2026](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)。

**この引継ぎ資料は調査の現在位置を保存するもの。未取得の成果物が元から存在したと仮定した「解決済み」の演出ではない。**
