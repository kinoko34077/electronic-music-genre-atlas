# v0.2 楽曲選定検証 — 2026-11-24

対象: [510枠の再構成案](../../../data/v0.2/reconstructed_510_2026-11-16.csv)（旧版・v0.2全候補の統合）。正本契約: [仕様書](../../SPECIFICATION.md)。今回の検証は個別楽曲の代表性・録音版・初出・正規個別ページに限る。全510件を調査済みとしない。

- 曲別選定確定: **11枠**（A/Bの曲名を明示した根拠、初出年・版、正規個別ページを確認）。
- 出典確認済み・音源ページ保留: **6枠**（検索インデックスだけではページ検証としない）。
- 保留: **7枠**。版違いによる差戻し: **1枠**。
- 個別調査未着手: **485枠**。
- 実音声再生、日本地域、閲覧UIの受入テストは未実施。最終atlas採用済みは0件。SELECTION_CONFIRMEDは曲別の選定確定であり、全体の受入完了とは別。

## 選定確定

| 枠 | 楽曲 | 初出年 | 根拠 | 正規個別ページ |
|---|---|---:|---|---|
| G01-E-01 | Skream — Midnight Request Line | 2005 | [A](https://mixmag.net/feature/the-13-best-mid-2000s-dubstep-tracks) | [Original recording (Tempa)](https://skreamizm.bandcamp.com/track/midnight-request-line) |
| G01-E-02 | Digital Mystikz — Anti War Dub | 2006 | [A](https://djmag.com/news/mala-reissue-full-back-catalogue-digitally-relaunched-ii-label) | [Original 2006 recording; 2021 digital remaster, not original vinyl master](https://mala-music.bandcamp.com/track/anti-war-dub) |
| G01-E-03 | Benga & Coki — Night | 2007 | [A](https://www.musicradar.com/news/the-beginners-guide-to-dubstep) | [Original recording, later album issue](https://tempa.bandcamp.com/track/night) |
| G01-E-05 | Burial — Archangel | 2007 | [B](https://pitchfork.com/features/grime-dubstep/6702-grime-dubstep/) | [Original Untrue album recording; later digital issue](https://burial.bandcamp.com/track/archangel) |
| G01-N-01 | Cesco & Hamdi — Swing King | 2023 | [B](https://edm.com/music-releases/cesco-hamdi-swing-king/) | [Original single / EP recording](https://cescomusicuk.bandcamp.com/track/swing-king-w-hamdi) |
| G03-E-01 | Porter Robinson — Spitfire | 2011 | [A](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/) | [Original Spitfire, not Kill the Noise remix](https://www.youtube.com/watch?v=F5HLHjyey_I) |
| G04-E-05 | Tipper — Ton Of Brix (VIP Mix) | 2011 | [A](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list) | [VIP Mix, Bubble Control EP (2011); later 2012 compilation](https://tipper.bandcamp.com/track/ton-of-brix-vip-mix-2) |
| G10-N-01 | Au5 & Chime — The Other Side | 2023 | [B](https://www.ravejungle.com/2023/01/26/chime-au5-the-other-side/) | [Original single](https://music.monstercat.com/track/the-other-side) |
| G10-N-02 | Chime — Rainbow Rave Parade | 2022 | [B](https://runthetrap.com/2022/02/28/chime-rainbow-rave-parade/) | [Original Rainbow Rave Parade, not 2025 VIP](https://monstercatmedia.bandcamp.com/track/rainbow-rave-parade) |
| G40-E-02 | DVRST — Close Eyes | 2021 | [A](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/) | [Original single, not slowed + reverb](https://music.apple.com/us/song/close-eyes/1573608260) |
| G40-N-04 | Kordhell — Murder in My Mind | 2022 | [A](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/) | [Original single](https://kordhell.bandcamp.com/track/murder-in-my-mind) |

## 保留・差戻し

| 枠 | 元候補 | 判定 | 理由・次に必要な証拠 |
|---|---|---|---|
| G01-E-04 | Kode9 & Daddi Gee — Sine of the Dub | HOLD | 2004 artist/catalog evidence conflicts with label product's 2005 date; later digital page is 2012. Hold pending earliest edition evidence. |
| G01-N-04 | Distinct Motive — Mellow Man | HOLD | Do not treat Canadian artist's nationality or bass release alone as genre disqualification or confirmation. |
| G03-E-02 | Zedd — Shave It | SOURCE_CONFIRMED_AUDIO_PENDING | Label release dated 2011-10-04; Apple track indexed, official OWSLA YouTube candidate also located, but direct pages not retrieved. |
| G03-E-03 | Mord Fustang — Lick the Rainbow | HOLD | Official Plasmapool credits 2011-10-01. Pool alternatives Say My Name and Kill Everybody have named-track evidence in Recording Arts Canada, but direct audio fetches not yet confirmed; do not discard this candidate solely because a page is inaccessible. |
| G03-E-04 | Madeon — Icarus | HOLD | Prefer evaluating pool alternative Porter Robinson — Say My Name: named in Recording Arts Canada https://recordingarts.com/record/evolution-of-house-music/complextro; original 2010 release indexed, direct audio pending. |
| G03-E-05 | Knife Party — Internet Friends | SOURCE_CONFIRMED_AUDIO_PENDING | 2011-12-12 EP edition indexed; Apple direct fetch failed, Beatport access denied. Do not claim verified playable link. |
| G04-E-01 | KOAN Sound — Sly Fox | SOURCE_CONFIRMED_AUDIO_PENDING | Official artist discography lists 2012-09-04 original and separate Opiuo remix. OWSLA official track indexed; direct fetch failed. |
| G04-E-02 | Tipper — Ton Of Brix | REJECTED_VERSION_MISMATCH | Original proposal's link is the VIP Mix already in G04-E-05. Remove this mismatched evidence/link and seek distinct replacement. No claim original 2005 date verified. |
| G04-E-04 | Opiuo — Quack Fat | HOLD | Official track release 2014-03-21. Need track-specific genre and formative role evidence; label date alone insufficient. |
| G05-E-01 | Skrillex — Scary Monsters and Nice Sprites | SOURCE_CONFIRMED_AUDIO_PENDING | Apple listing identifies 2010-10-22; individual direct page fetch failed. |
| G05-E-04 | Flux Pavilion — Bass Cannon | SOURCE_CONFIRMED_AUDIO_PENDING | Circus Records official 2011 upload indexed; direct retrieval failed. Avoid later 2025 recording. |
| G12-N-01 | INFEKT — Relic | HOLD | Need independent named-song Trench evidence and official individual page. |
| G12-N-02 | INFEKT & SampliFire — ECHO | HOLD | Need source body and individual official recording verification. |
| G45-N-01 | Aversion — Activation | SOURCE_CONFIRMED_AUDIO_PENDING | Official artist channel listing and Apple single date indexed, direct fetch failed. Need direct audio-page verification. |

全510枠の現在判定・出典記事名・URL・言及内容・ディスコグラフィー・音源ページ検証状態は [track_decisions.csv](../../../data/v0.2/track_decisions.csv) に保存。旧候補、未選定候補、過去の根拠主張を削除せず、この判定台帳を更新して続行する。次は SOURCE_CONFIRMED_AUDIO_PENDING を公式配信サービスから再照合、HOLD/REJECTED を673候補プールの代替曲から再選定、その後 NOT_REVIEWED をジャンル別に検証。Discogsのページを直接取得できない場合、MusicBrainzの版情報・権利者の公式発売資料・同時代記事の役割を分離して記録する。
