# 全51系統・510枠 再構成候補一覧（v0.2 / 2026-11-16）

**この表の510件は候補の再構成であり、510曲の正式採用・楽曲ジャンル分類・初出年・正規音源の検証完了ではない。** 親Issue #1と仕様正本を受入権限とする。

## 取得・判定の位置付け

全候補: 旧チャットZIPと対応する510件のreview queue、旧台帳16件、同研究JSON16件、補足5件、曲別再監査20件、v0.2復元68件、v0.2再調査174件を曲名・アーティスト・研究枠・期で正規化。**元のDeep Researchで出力されたが保存されていない510行は復元不可**。1曲が複数台帳にある場合は同一候補として統合し、出典を保持。

再構成ではA/Bを「報告上の候補級」とし、記事本文が該当曲を明示するかの追加実読を必須とする。Discogs/MusicBrainzは楽曲の存在・版・初出・クレジットの照合に活用するが、データベースのジャンルタグだけで代表性は証明できない。**今回MusicBrainzの個別レコード・Artist discographyを実読確認した候補のメタデータのみ**具体URLで付記。Discogs MasterリンクはMusicBrainzからの参照であり直接本文照合はしていない。

| 集計 | 数 |
| --- | ---: |
| 再構成した固定候補枠 | 510（初期255・現在255） |
| 重複統合後の候補プール | 673曲・研究枠・期間の組 |
| 従来候補を同じ位置に保持 | 370 |
| 従来候補の同一期内で再配置 | 0 |
| 従来候補を別候補へ差替 | 140 |
| 初出年が判定不能 | 125 |
| 初期／現在の年条件に疑義（候補を維持し明示） | 7 |
| 他分類と同じ楽曲が選定されたケース | 18 |
| 正式採用 | 0 |

**ファイル:** [510行CSV](../../../data/v0.2/reconstructed_510_2026-11-16.csv) ／ [全候補プールCSV](../../../data/v0.2/reconstruction_candidate_pool_2026-11-16.csv) ／ [510枠差分台帳](../../../data/v0.2/reconstruction_diff_2026-11-16.csv) ／ [機械可読監査・分類別内訳](../../../data/v0.2/reconstruction_audit_2026-11-16.json)。ZIPは作らずリポジトリへ直接格納する。

## Discogs／MusicBrainzなどの利用上の根拠

Discogs公式解説: [Release Page Guide](https://support.discogs.com/hc/en-us/articles/17114733929229-Release-Page-Guide)（版・クレジット・盤固有の日付を収録、参加者編集のデータベース）および[Master Release](https://support.discogs.com/hc/en-us/articles/360005055493-Database-Guidelines-16-Master-Release)（再発・別版を含むため初出確認には個別release比較が必要）。MusicBrainz: [schema](https://musicbrainz.org/doc/MusicBrainz_Database/Schema)、[リリース日ガイド](https://musicbrainz.readthedocs.io/en/latest/style_guides/release.html)（再発日と曲の最初の公開日を混同しない）。

- [Skream – Midnight Request Line / I (MusicBrainz)](https://musicbrainz.org/release/2a051f63-ac82-46fa-9756-1e34f064a04c): Tempa TEMPA014、2005-11-07、収録曲／クレジット。Discogs Master 15262の相互リンクも記載されているが**Discogs原本の直接照合は未実施**。
- [Porter Robinson – Spitfire (MusicBrainz)](https://musicbrainz.org/release/88ffbbe2-bcce-4bfd-912d-2d1998173e4a): OWSLA EP、2011-09-13。2015年以後の再配信日と区別する。
- [Kordhell – Murder in My Mind (MusicBrainz)](https://musicbrainz.org/release/2b79071c-ab6f-4eb3-92c7-95e1d66235bb): 2022-01-21。元音源とSlowed+Reverbは別録音版。
- [Sub Focus（MusicBrainz discography）](https://musicbrainz.org/artist/8cf49f40-b8fe-4a63-b4ea-f922d6145bb4): On & Onが2025年のシングル、Kanine Remixは別リリース。

## 分類別の再構成一覧

### 01. UK Dubstep

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Skream — Midnight Request Line | 2005 | [記事](https://www.musicradar.com/news/the-beginners-guide-to-dubstep) [曲目DB](https://musicbrainz.org/release/2a051f63-ac82-46fa-9756-1e34f064a04c) | KEEP |
| 初2 | Digital Mystikz — Anti War Dub | 2006 | [記事](https://www.musicradar.com/news/the-beginners-guide-to-dubstep)  | KEEP |
| 初3 | Benga & Coki — Night | 2007 | [記事](https://www.musicradar.com/news/the-beginners-guide-to-dubstep)  | KEEP |
| 初4 | Kode9 & Daddi Gee — Sine of the Dub | 未確認 | [記事](https://dubstepguide.net/genres/uk-dubstep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Burial — Archangel | 未確認 | —  | KEEP |
| 現1 | Cesco & Hamdi — Swing King | 2024 | [記事](https://www.beatportal.com/articles/781122-140-deep-dubstep-grime-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Caspa — Dundada | 2024 | [記事](https://sonaa.ca/en/styles/bass/dubstep/)  | KEEP |
| 現3 | Charli XCX — Von dutch remix with Skream and Benga | 2024 | [記事](https://mixmag.net/feature/the-best-tracks-of-the-year-2024-april)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Distinct Motive — Mellow Man | 2024 | [記事](https://edm.com/industry/best-songs-2024/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Skrillex, Hamdi, TAICHU & OFFAIAH — Push | 2024 | [記事](https://www.beatportal.com/articles/781122-140-deep-dubstep-grime-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |

### 02. Electro House

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Fedde Le Grand — Put Your Hands Up for Detroit | 2006 | [記事](https://dancingastronaut.com/2017/04/dancing-astronaut-presents-time-capsule-electro-house/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Benny Benassi — Satisfaction | 2002 | [記事](https://underowl.net/en/genre/electro-house)  | KEEP |
| 初3 | Justice — D.A.N.C.E. | 2007 | [記事](https://sonaa.ca/en/styles/house/electro-house/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | deadmau5 — Ghosts ’n’ Stuff | 2008 | [記事](https://underowl.net/en/genre/electro-house)  | KEEP |
| 初5 | Justice — Genesis | 2007 | [記事](https://sonaa.ca/en/styles/house/electro-house/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Justice — Generator | 2024 | [記事](https://sonaa.ca/en/styles/house/electro-house/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Ninajirachi — All I Am | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現3 | Ninajirachi — Fuck My Computer | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現4 | Tiffany Day — PRETTY4U | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現5 | Lady Gaga — Abracadabra | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |

### 03. Complextro

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Porter Robinson — Spitfire | 2011 | [記事](https://underowl.net/en/genre/complextro) [曲目DB](https://musicbrainz.org/release/88ffbbe2-bcce-4bfd-912d-2d1998173e4a) | KEEP |
| 初2 | Zedd — Shave It | 2011 | [記事](https://underowl.net/en/genre/complextro)  | KEEP |
| 初3 | Mord Fustang — Lick the Rainbow | 2011 | [記事](https://underowl.net/en/genre/complextro)  | KEEP |
| 初4 | Madeon — Icarus | 2012 | [記事](https://underowl.net/en/genre/complextro)  | KEEP |
| 初5 | Knife Party — Internet Friends | 2011 | [記事](https://recordingarts.com/record/evolution-of-house-music/complextro)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Ninajirachi — iPod Touch | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現2 | Ninajirachi — All I Am | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現3 | Kim Petras — Freak It | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現4 | Ninajirachi — Fuck My Computer | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/electro-house/)  | KEEP |
| 現5 | Porter Robinson, Ninajirachi & underscores — Perfect Pinterest Garden (Ninajirachi & underscores Remix) | 2026 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/all/complextro/)  | KEEP |

### 04. Glitch Hop

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | KOAN Sound — Sly Fox | 未確認 | —  | KEEP |
| 初2 | Tipper — Ton Of Brix | 2005 | [記事](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Pretty Lights — Finally Moving | 未確認 | —  | KEEP |
| 初4 | Opiuo — Quack Fat | 未確認 | —  | KEEP |
| 初5 | Tipper — Ton Of Brix (VIP Mix) | 2011 | [記事](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | CouchLocked — Possum Stew | 2025 | [記事](https://glitchhopcommunity.bandcamp.com/album/couchlocked-possum-stew)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Y3LLY — Breakdown | 2025 | [記事](https://glitchhopcommunity.bandcamp.com/album/y3lly-glitched-night-ep)  | KEEP |
| 現3 | Y3LLY — Ain't No Giving Up | 2025 | [記事](https://glitchhopcommunity.bandcamp.com/album/y3lly-glitched-night-ep)  | KEEP |
| 現4 | Opiuo & Mr. Bill — MR. BREAKS | 2025 | [記事](https://www.beatport.com/artist/opiuo/119263/tracks)  | KEEP |
| 現5 | Opiuo — SHARK BREATH | 2025 | [記事](https://www.beatport.com/artist/opiuo/119263/tracks)  | KEEP |

### 05. Brostep

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Skrillex — Scary Monsters and Nice Sprites | 2010 | [記事](https://dubstepguide.net/genres/brostep/)  | KEEP |
| 初2 | Doctor P — Sweet Shop | 2010 | [記事](https://dubstepguide.net/genres/brostep/)  | KEEP |
| 初3 | Excision — Robo Kitty | 2011 | [記事](https://sonaa.ca/en/styles/bass/brostep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | Flux Pavilion — Bass Cannon | 2011 | [記事](https://sonaa.ca/en/styles/bass/brostep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Rusko — Cockney Thug | 2008 | [記事](https://sonaa.ca/en/styles/bass/brostep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Skrillex & ISOxo — fuze | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/brostep/)  | KEEP |
| 現2 | Virtual Riot & Eliminate — Aura Farming | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/brostep/)  | KEEP |
| 現3 | Space Laces — This Way | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/brostep/)  | KEEP |
| 現4 | Virtual Riot & Viperactive — What U Got | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/brostep/)  | KEEP |
| 現5 | Zomboy — Royal Blood | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/brostep/)  | KEEP |

### 06. Riddim Dubstep

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Phiso — Jotaro | 2016 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | KEEP |
| 初2 | Bommer & Crowell — Loco | 2016 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Getter — Head Splitter | 2014 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | INFEKT — Raptor | 2017 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | SVDDEN DEATH — BEHEMOTH | 2019 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | INFEKT & SampliFire — ECHO | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現2 | INFEKT — BOOSTED | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現3 | SampliFire & INFEKT — True Trench Times | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現4 | roi* — Soundclouddotcomslashroidubs | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現5 | Subtronics — Scream Saver | 2022 | [記事](https://sonaa.ca/en/styles/bass/riddim/)  | REPLACE_WITH_POOL_CANDIDATE |

### 07. Melodic Dubstep

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Flight Facilities — Crave You (Adventure Club Remix) | 2011 | [記事](https://dubstepguide.net/genres/melodic-dubstep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Mt Eden — Sierra Leone | 2009 | [記事](https://dubstepguide.net/genres/melodic-dubstep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Au5 — Snowblind | 未確認 | —  | KEEP |
| 初4 | Seven Lions ft. Fiora — Days to Come | 2012 | [記事](https://dubstepguide.net/genres/melodic-dubstep/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | ILLENIUM — Fractures | 未確認 | —  | KEEP |
| 現1 | Seven Lions — So Far Away | 2025 | [記事](https://opheliarecords.com/music/)  | KEEP |
| 現2 | MitiS — Sky Is Falling | 2025 | [記事](https://opheliarecords.com/music/)  | KEEP |
| 現3 | Last Heroes & HYMNALS — Above The Stars | 2025 | [記事](https://opheliarecords.com/music/)  | KEEP |
| 現4 | Seven Lions & Andrew Bayer — Hurricane | 2026 | [記事](https://opheliarecords.com/music/)  | KEEP |
| 現5 | Seven Lions — Take Me To My Grave | 2025 | [記事](https://opheliarecords.com/music/)  | KEEP |

### 08. Future Bass

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Cashmere Cat — Mirror Maru | 2012 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Flume — Holdin On | 2012 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | ODESZA — Say My Name | 2014 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | Rustie — Slasherr | 2013 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Wave Racer — Streamers | 2013 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Kesha — Delusional | 2024 | [記事](https://sonaa.ca/en/styles/bass/future-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Dabin, NURKO & Skylar Grey — I See You | 2025 | [記事](https://edm.com/industry/best-edm-tracks-of-2025/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Dead Rose & RUNN — Satellite | 2025 | [記事](https://edm.com/industry/best-edm-tracks-of-2025/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | ILLENIUM & HAYLA — In My Arms | 2025 | [記事](https://edm.com/industry/best-edm-tracks-of-2025/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | MitiS (other credits to verify) — In the End | 2025 | [記事](https://edm.com/industry/best-edm-tracks-of-2025/)  | REPLACE_WITH_POOL_CANDIDATE |

### 09. Future Riddim

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Leotrix — Hive Bounce | 2019 | [記事](https://underowl.net/ja/genre/future-riddim)  | KEEP |
| 初2 | Ace Aura — Coma | 2019 | [記事](https://underowl.net/ja/genre/future-riddim)  | KEEP |
| 初3 | Leotrix — Emoboy303 (SIDE) | 未確認 | —  | KEEP |
| 初4 | Oolacile — Kandi | 2019 | [記事](https://underowl.net/en/genre/future-riddim)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Sharks — Shiver | 未確認 | —  | KEEP |
| 現1 | Chalbért & euphee — HYPERVOICE!! | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現2 | Neddie — life don't feel real | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現3 | Devath — DREAMSCAPER | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現4 | Sharks — Butterflies | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |
| 現5 | Paper Skies — What I Need | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/riddim/)  | KEEP |

### 10. Colour Bass

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Chime — From Fairies to Fire | 2016 | [記事](https://dubstepguide.net/genres/colour-bass/)  | KEEP |
| 初2 | Ace Aura — Coma | 2019 | [記事](https://dubstepguide.net/genres/colour-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Chime & Ace Aura — Interdimensional | 2019 | [記事](https://dubstepguide.net/genres/colour-bass/)  | KEEP |
| 初4 | Au5 & Chime — Voidwalkers | 2020 | [記事](https://dubstepguide.net/genres/colour-bass/)  | KEEP |
| 初5 | Chime — Whirlwind | 2018 | [記事](https://underowl.net/en/genre/colour-bass)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Au5 & Chime — The Other Side | 2023 | [記事](https://dubstepguide.net/genres/colour-bass/)  | KEEP |
| 現2 | Chime — Rainbow Rave Parade | 2022 | [記事](https://dubstepguide.net/genres/colour-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Au5 — Cryptochrome | 2022 | [記事](https://dubstepguide.net/genres/colour-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Chime — Between | 2025 | [記事](https://www.monstercat.com/release/742779557353)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Chime & Convexity — Liminal | 2024 | [記事](https://www.youtube.com/watch?v=0wFhQ35C44c)  | REPLACE_WITH_POOL_CANDIDATE |

### 11. Modern Tearout

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | MARAUDA — Casket | 2017 | [記事](https://dubstepguide.net/genres/tearout/)  | KEEP |
| 初2 | SVDDEN DEATH — Prismatic | 2017 | [記事](https://dubstepguide.net/genres/tearout/)  | KEEP |
| 初3 | Excision & Space Laces — Throwin’ Elbows | 2016 | [記事](https://dubstepguide.net/genres/tearout/)  | KEEP |
| 初4 | SVDDEN DEATH — Behemoth | 2019 | [記事](https://dubstepguide.net/genres/tearout/)  | KEEP |
| 初5 | MARAUDA — Blunder | 未確認 | —  | KEEP |
| 現1 | Excision, SVDDEN DEATH & yvm3 — INSANE! | 2025 | [記事](https://edm.com/music-releases/excision-svdden-death-yvm3-insane/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | MARA(U)DA / MUERTE (credits to verify) — UMBRA (MUERTE EDIT) | 2024 | [記事](https://relentlessbeats.com/2024/03/muerte-reworks-maraudas-magic)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | SVDDEN DEATH & yvm3 — Dissent | 2026 | [記事](https://edm.com/music-releases/svdden-death-yvm3-dissent/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | yvm3 & STVG — rot | 2024 | [記事](https://www.dubstepfbi.com/post/premiere-listen-to-the-rotten-new-yvm3-stvg-song-before-it-destroys-the-universe)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Kozmoz, Micah Martin & Talix — The Kill | 2025 | [記事](https://volt.fm/playlist/57540519/best-of-tearout)  | KEEP |

### 12. Trench / Modern Riddim

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | INFEKT — Orgalorg | 2016 | —  | KEEP |
| 初2 | INFEKT — Dance Off | 未確認 | —  | KEEP |
| 初3 | SampliFire — Mercia | 未確認 | —  | KEEP |
| 初4 | Automhate — Seleman | 未確認 | —  | KEEP |
| 初5 | INFEKT — Da Pit | 未確認 | —  | KEEP |
| 現1 | INFEKT — Relic | 2025 | [記事](https://iwantedm.com/trench-trailblazer-infekt-unleashes-his-latest-bass-anthem-relic-via-deadbeats-imprint/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | INFEKT & SampliFire — ECHO | 2025 | [記事](https://www.bandslate.com/band/infekt)  | KEEP |
| 現3 | INFEKT — BOOSTED | 2025 | [記事](https://www.bandslate.com/band/infekt)  | KEEP |
| 現4 | INFEKT — VEGGIE ANTHEM | 2025 | [記事](https://www.bandslate.com/band/infekt)  | KEEP |
| 現5 | INFEKT & MAD DUBZ — DROP IT | 2025 | [記事](https://www.bandslate.com/band/infekt)  | KEEP |

### 13. Experimental Bass

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | G Jones — In Your Head | 未確認 | —  | KEEP |
| 初2 | EPROM — Hope | 未確認 | —  | KEEP |
| 初3 | G Jones & EPROM — Hysteria | 未確認 | —  | KEEP |
| 初4 | Tipper — Dreamsters | 未確認 | —  | KEEP |
| 初5 | Ivy Lab — Orange | 未確認 | —  | KEEP |
| 現1 | G Jones & Eprom — Break of Dawn | 2026 | [記事](https://edm.com/music-releases/g-jones-eprom-break-of-dawn-ep/)  | KEEP |
| 現2 | Fake Two Piece & Lokal — Bad Mouth | 2024 | [記事](https://ukf.com/read/2024-the-tracks/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | G Jones & Eprom — Noontime Acid | 2025 | [記事](https://edm.com/music-releases/g-jones-eprom-disk-utility-ep/)  | KEEP |
| 現4 | G Jones & Eprom — 1000 Cuts | 2025 | [記事](https://edm.com/music-releases/g-jones-eprom-disk-utility-ep/)  | KEEP |
| 現5 | G Jones & Eprom — By Your Side | 2025 | [記事](https://edm.com/music-releases/g-jones-eprom-disk-utility-ep/)  | KEEP |

### 14. Drum & Bass

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Goldie — Inner City Life | 1994 | [記事](https://sonaa.ca/en/styles/breaks/drum-and-bass/)  | KEEP |
| 初2 | Adam F — Metropolis | 1997 | [記事](https://sonaa.ca/en/styles/breaks/drum-and-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Roni Size — Brown Paper Bag | 1997 | [記事](https://sonaa.ca/en/styles/breaks/drum-and-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | Andy C — Body Rock | 未確認 | [記事](https://sonaa.ca/en/styles/breaks/drum-and-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Calibre — Mystic | 未確認 | [記事](https://sonaa.ca/en/styles/breaks/drum-and-bass/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Sub Focus & bbyclose — On & On | 2025 | [記事](https://ukf.com/read/2025-the-tracks/) [曲目DB](https://musicbrainz.org/artist/8cf49f40-b8fe-4a63-b4ea-f922d6145bb4) | KEEP |
| 現2 | Chase & Status ft. Stormzy — BACKBONE | 2024 | [記事](https://www.beatportal.com/articles/780131-drum-bass-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | John Summit, Sub Focus & Julia Church — Go Back | 2024 | [記事](https://www.beatportal.com/articles/780131-drum-bass-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | ROVA — Eyes On Me | 2024 | [記事](https://www.beatportal.com/articles/780131-drum-bass-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Delta Heavy — Ecstasy | 2024 | [記事](https://www.beatportal.com/articles/780131-drum-bass-the-top-selling-tracks-artists-and-labels-of-2024)  | REPLACE_WITH_POOL_CANDIDATE |

### 15. Neurofunk

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Noisia — Stigma | 2007 | [記事](https://sonaa.ca/en/styles/breaks/neurofunk/)  | KEEP |
| 初2 | Black Sun Empire — Arrakis | 2004 | [記事](https://sonaa.ca/en/styles/breaks/neurofunk/)  | KEEP |
| 初3 | Noisia — Machine Gun | 2010 | [記事](https://sonaa.ca/en/styles/breaks/neurofunk/)  | KEEP |
| 初4 | Ed Rush & Optical — Funktion | 1997 | [記事](https://sonaa.ca/en/styles/breaks/neurofunk/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Mefjus — Suicide Bassline | 未確認 | —  | KEEP |
| 現1 | Protostar, Laminar & imallryt — Blood in the Water | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/neurofunk/)  | KEEP |
| 現2 | NUEQ & Culprate — Lilin | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/neurofunk/)  | KEEP |
| 現3 | Audeka — Blob Robber | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/neurofunk/)  | KEEP |
| 現4 | Teddy Killerz — Chemical Explosion | 2025 | [記事](https://www.beatportal.com/articles/1142665-teddy-killerz-make-their-long-awaited-crucast-debut-with-chemical-explosion-i-live)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | ShockOne, NCT & Scrufizzer — Rockstar Bass | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/neurofunk/)  | KEEP |

### 16. Trance

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Energy 52 — Café Del Mar | 1993 | [記事](https://www.armadamusic.com/news/trance-music)  | KEEP |
| 初2 | Paul van Dyk — For an Angel | 1994 | [記事](https://www.armadamusic.com/news/trance-music)  | KEEP |
| 初3 | Robert Miles — Children | 1995 | [記事](https://www.armadamusic.com/news/trance-music)  | KEEP |
| 初4 | BT — Godspeed | 未確認 | [記事](https://articles.roland.com/listening-guide-essential-early-trance/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Cygnus X — Superstring | 未確認 | [記事](https://articles.roland.com/listening-guide-essential-early-trance/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Above & Beyond — Quicksand (Don’t Go) | 2025 | [記事](https://www.youtube.com/watch?v=VpP0rxlnTEM)  | KEEP |
| 現2 | KI/KI & Marlon Hoffstadt — Losing Control | 2025 | [記事](https://www.beatportal.com/articles/1217928-trance-the-top-selling-tracks-artists-and-labels-of-2025)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Armin van Buuren, Ben Hemsley & Lucy Pullin — Is It Beautiful? | 2025 | [記事](https://www.youtube.com/watch?v=VpP0rxlnTEM)  | KEEP |
| 現4 | Bryan Kearney & Plumb — God Help Me | 2025 | [記事](https://www.youtube.com/watch?v=VpP0rxlnTEM)  | KEEP |
| 現5 | Factor B — Ghosts | 2025 | [記事](https://www.youtube.com/watch?v=VpP0rxlnTEM)  | KEEP |

### 17. Nightcore / Sped-up Edit

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Nightcore — Dam Dadi Doo | 2006 | [記事](https://knowyourmeme.com/memes/cultures/nightcore)  | KEEP |
| 初2 | Nightcore — Angel with a Shotgun | 未確認 | —  | KEEP |
| 初3 | Nightcore — Everytime We Touch | 未確認 | —  | KEEP |
| 初4 | Getter Jaani — Rockefeller Street (Nightcore) | 未確認 | —  | KEEP |
| 初5 | Caramella Girls — Caramelldansen | 未確認 | —  | KEEP |
| 現1 | Lil Uzi Vert, ARIZONATEARS & sped up nightcore — Watch This (ARIZONATEARS Pluggnb Remix) | 2023 | [記事](https://kworb.net/spotify/artist/0M2CO5ijP35MDhNwvpgxTV_songs.html)  | KEEP |
| 現2 | Melanie Martinez & sped up nightcore — VOID (Sped Up Version) | 2023 | [記事](https://kworb.net/spotify/artist/0M2CO5ijP35MDhNwvpgxTV_songs.html)  | KEEP |
| 現3 | ThxSoMch & sped up nightcore — SPIT IN MY FACE! (Sped Up Version) | 2023 | [記事](https://kworb.net/spotify/artist/0M2CO5ijP35MDhNwvpgxTV_songs.html)  | KEEP |
| 現4 | Steve Lacy — Bad Habit — Sped Up | 2022 | [記事](https://cassidygeorge.com/a-history-of-nightcore-the-sped-up-songs-all-over-tiktok/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | sped up nightcore — Drowning (Sped Up Version) | 2022 | [記事](https://kworb.net/spotify/artist/0M2CO5ijP35MDhNwvpgxTV_songs.html)  | KEEP |

### 18. Hyperpop

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | SOPHIE — Immaterial | 2018 | [記事](https://musictech.com/guides/essential-guide/best-hyperpop-songs/)  | KEEP |
| 初2 | 100 gecs — money machine | 2019 | [記事](https://musictech.com/guides/essential-guide/best-hyperpop-songs/)  | KEEP |
| 初3 | Charli xcx — Vroom Vroom | 2016 | [記事](https://musictech.com/guides/essential-guide/best-hyperpop-songs/)  | KEEP |
| 初4 | A. G. Cook — Beautiful | 2014 | [記事](https://musictech.com/guides/essential-guide/best-hyperpop-songs/)  | KEEP |
| 初5 | SOPHIE — Bipp | 2013 | [記事](https://musictech.com/guides/essential-guide/best-hyperpop-songs/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Jane Remover — Dancing with your eyes closed | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/hyperpop/)  | KEEP |
| 現2 | ovine hall & kurtains — uk bitches | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/hyperpop/)  | KEEP |
| 現3 | Vylet Pony — My Love is a Quickscope | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/hyperpop/)  | KEEP |
| 現4 | GFOTY — GRWM (eww) | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/hyperpop/)  | KEEP |
| 現5 | Camila Cabello ft. Playboi Carti — I LUV IT | 2024 | [記事](https://pitchfork.com/features/lists-and-guides/best-songs-2024/)  | REPLACE_WITH_POOL_CANDIDATE |

### 19. HexD

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Fax Gang — Breathe2 (In/Out) | 未確認 | [記事](https://www.albumoftheyear.org/release/30828-fax-gang-fxg3000.php)  | KEEP |
| 初2 | Fax Gang — Jeopardy | 未確認 | [記事](https://www.albumoftheyear.org/release/30828-fax-gang-fxg3000.php)  | KEEP |
| 初3 | blackwinterwells — glitter | 未確認 | —  | KEEP |
| 初4 | kaystrueno — maple | 未確認 | —  | KEEP |
| 初5 | Rat Jesu — Emo Girl Ex Machina | 未確認 | —  | KEEP |
| 現1 | femtanyl — ATTACKING VERTICAL | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/all/hexd/)  | KEEP |
| 現2 | 4evrx — stranger in the mirror | 2025 | [記事](https://record.club/genres/hexd/releases)  | KEEP |
| 現3 | lostrushi — syxx anthem (it can't be helped) | 2022 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/all/hexd/)  | KEEP |
| 現4 | lostrushi — dissociation of sisters // wipe your tears | 2022 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/all/hexd/)  | KEEP |
| 現5 | femtanyl — ITS TIME | 2024 | [記事](https://arktide.com/artist/femtanyl)  | KEEP |

### 20. Sigilkore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Luci4 — Kurxxed Emeraldz | 2021 | [記事](https://www.edgepedia.org/sigilkore)  | KEEP |
| 初2 | siouxxie sixxsta — masquerade | 2021 | [記事](https://www.edgepedia.org/sigilkore)  | KEEP |
| 初3 | Luci4 — BodyPartz | 2021 | [記事](https://www.edgepedia.org/sigilkore)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | lostrushi — yasu club | 未確認 | —  | KEEP |
| 初5 | kaystrueno — iSSUE | 未確認 | —  | KEEP |
| 現1 | Kempachii — Kill the Internet | 2023 | [記事](https://koramusic.app/genre/sigilkore)  | KEEP |
| 現2 | gazecloud — WHY R PPL SO MEAN? | 2024 | [記事](https://koramusic.app/genre/sigilkore)  | KEEP |
| 現3 | lil fasty x Mek-9 — DISGUSTING | 2025 | [記事](https://koramusic.app/genre/sigilkore)  | KEEP |
| 現4 | Luci4 — in da rain / / 4 da pain | 2025 | [記事](https://www.albumoftheyear.org/artist/74701-luci4/?type=single)  | KEEP |
| 現5 | Luci4 & 9lives — out da dirt | 2024 | [記事](https://www.albumoftheyear.org/artist/74701-luci4/?type=single)  | KEEP |

### 21. Jersey Club

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | DJ Sliink — Vibrate | 2013 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | KEEP |
| 初2 | Cookiee Kawaii — Vibe (If I Back It Up) | 2019 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | KEEP |
| 初3 | Cookiee Kawaii — Vibe | 2019 | [記事](https://soundcloud.com/stories/post/jersey-club/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | UNIIQU3 — Microdosing | 2018 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | DJ Sliink — Arch in Ya Back | 2009 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | PinkPantheress & Ice Spice — Boy's a liar Pt. 2 | 2023 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | KEEP |
| 現2 | Ice Spice & Central Cee — Did It First | 2024 | [記事](https://sonaa.ca/en/styles/bass/jersey-club/)  | KEEP |
| 現3 | Marina Satti — EPANO STO TRAPEZI | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/jersey-club/)  | KEEP |
| 現4 | Lil Uzi Vert — Just Wanna Rock | 2022 | [記事](https://soundcloud.com/stories/post/jersey-club/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Amaarae — Girlie-Pop! | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/jersey-club/)  | KEEP |

### 22. Krushclub

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Luci4 — Kurxxed Emeraldz | 2021 | [記事](https://pitchfork.com/thepitch/luci4-unleashed-a-generation-of-glitchy-underground-rap/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Odetari — GOOD LOYAL THOTS | 2023 | [記事](https://volt.fm/genre/7425/krushclub)  | KEEP / 年代要修正 |
| 初3 | 6arelyhuman — Hands Up! | 2023 | [記事](https://volt.fm/genre/7425/krushclub)  | KEEP / 年代要修正 |
| 初4 | Odetari — LOOK DON’T TOUCH | 2023 | [記事](https://volt.fm/genre/7425/krushclub)  | KEEP / 年代要修正 |
| 初5 | asteria & kets4eki — MOLLY | 未確認 | —  | KEEP |
| 現1 | lexycat — ♛ #cherryCrush ✮°｡⋆ | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/all/hexd/)  | KEEP |
| 現2 | Lumi Athena & Cade Clair — Let Me See Ya Move! | 2023 | [記事](https://tsnvwrld.com/what-is-krushclub-music/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Odetari — Narcissistic Personality Disorder | 2023 | [記事](https://tsnvwrld.com/what-is-krushclub-music/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Lumi Athena ft. jnhygs — Smoke It Off! | 2022 | [記事](https://tsnvwrld.com/what-is-krushclub-music/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | kets4eki & asteria — TAX ON IT | 2025 | [記事](https://www.albumoftheyear.org/artist/163315-asteria/?type=single)  | KEEP |

### 23. Plunderphonics

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | John Oswald — Dab | 未確認 | —  | KEEP |
| 初2 | John Oswald — Plexure | 未確認 | —  | KEEP |
| 初3 | Negativland — U2 | 未確認 | —  | KEEP |
| 初4 | The Avalanches — Frontier Psychiatrist | 未確認 | —  | KEEP |
| 初5 | The Avalanches — Since I Left You | 未確認 | —  | KEEP |
| 現1 | Neil Cicierega — Porcelain | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plunderphonics/)  | KEEP |
| 現2 | Nickster — frontier psychiatrist by the avalanches but it uses newer samples | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plunderphonics/)  | KEEP |
| 現3 | Sylus64 — damn | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plunderphonics/)  | KEEP |
| 現4 | DragonBread — Sonic Cauldron Type Beat 2 | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plunderphonics/)  | KEEP |
| 現5 | Yung Schmoobin — YouTube Halation | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plunderphonics/)  | KEEP |

### 24. Mashup

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Freelance Hellraiser — A Stroke of Genie-us | 2001 | [記事](https://journals.sagepub.com/doi/10.1177/1354856520983758)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Girl Talk — Oh No | 未確認 | —  | KEEP |
| 初3 | DJ Earworm — United State of Pop 2009 | 未確認 | —  | KEEP |
| 初4 | 2manydjs — Push It Like a Dog | 未確認 | —  | KEEP |
| 初5 | The Hood Internet — Two Weeks of Hip Hop | 未確認 | —  | KEEP |
| 現1 | DJ Earworm — Summermash ’24 | 2024 | [記事](https://musicbrainz.org/artist/e407802a-bfc3-4979-a5e1-3196ccf9c8d9)  | KEEP |
| 現2 | DJ Earworm — United State of Pop 2023 (Cut the Flowers) | 2023 | [記事](https://musicbrainz.org/artist/e407802a-bfc3-4979-a5e1-3196ccf9c8d9)  | KEEP |
| 現3 | DJ Earworm — United State of Pop 2022 (I Want Music) | 2022 | [記事](https://musicbrainz.org/artist/e407802a-bfc3-4979-a5e1-3196ccf9c8d9)  | KEEP |
| 現4 | DJ Earworm — United State of Pop 2024 (Blame It on the Whiskey) | 2024 | [記事](https://stereogum.com/2290441/dj-earworm-shares-annual-hits-mashup-united-state-of-pop-2024/music)  | KEEP |
| 現5 | DJ Earworm — United State of Pop 2025 (Talk to Me) | 2025 | [記事](https://www.popelera.net/dj-earworm-mashup-2025/)  | KEEP |

### 25. Mashcore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Venetian Snares — Twelve | 未確認 | —  | KEEP |
| 初2 | Sickboy — Bohemian Crapsody | 未確認 | —  | KEEP |
| 初3 | Graz — Total Request Mashup | 未確認 | —  | KEEP |
| 初4 | Shitmat — Jackson$ Babylon | 未確認 | —  | KEEP |
| 初5 | Shitmat — There's No Business Like Propa' Rungleclotted Mashup Bizznizz | 2004 | [記事](https://eweb.learningtodj.com/g/breakcore)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Shoebill — kiss me (irritating notification mix) | 2026 | [記事](https://othermanrecords.bandcamp.com/album/otmn103-lost-in-translation)  | KEEP |
| 現2 | Shoebill — o'er the otley runners | 2026 | [記事](https://othermanrecords.bandcamp.com/album/otmn103-lost-in-translation)  | KEEP |
| 現3 | Shoebill — mashup princess | 2026 | [記事](https://othermanrecords.bandcamp.com/album/otmn103-lost-in-translation)  | KEEP |
| 現4 | Shoebill — pumped the f up | 2026 | [記事](https://othermanrecords.bandcamp.com/album/otmn103-lost-in-translation)  | KEEP |
| 現5 | Shoebill — emoticomplex (aka the longest shoebill track everrr) | 2026 | [記事](https://othermanrecords.bandcamp.com/album/otmn103-lost-in-translation)  | KEEP |

### 26. Breakcore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Venetian Snares — Hajnal | 2005 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 初2 | Bong-Ra — Killergram | 2003 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 初3 | Venetian Snares — Szamar Madar | 2005 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 初4 | Atari Teenage Riot — Deutschland (Has Gotta Die!) | 1996 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Igorrr — Tout Petit Moineau | 未確認 | —  | KEEP |
| 現1 | Femtanyl — Chaser | 2023 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 現2 | Femtanyl — Lovesick, Cannibal! | 2023 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 現3 | Femtanyl — Dogmatica | 2023 | [記事](https://sonaa.ca/en/styles/breaks/breakcore/)  | KEEP |
| 現4 | bagel fanclub — mutant hell fishing | 2025 | [記事](https://bagelfanclub.bandcamp.com/album/its-nothing-new)  | KEEP |
| 現5 | Hakita — (At Least) Three Cheers for Cause and Effect | 2025 | [記事](https://volt.fm/album/217885261/tennis-everyone-a-tribute-to-the-late-great-james-o-incandenza-by-hakita)  | KEEP |

### 27. Dariacore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | leroy — go white enby go | 2021 | [記事](https://assistwithmusic.com/encyclopedia/dariacore)  | KEEP |
| 初2 | leroy — will work for food | 2021 | [記事](https://assistwithmusic.com/encyclopedia/dariacore)  | KEEP |
| 初3 | leroy — bluuuueeeee | 2021 | [記事](https://assistwithmusic.com/encyclopedia/dariacore)  | KEEP |
| 初4 | leroy — die in my dream | 2021 | [記事](https://assistwithmusic.com/encyclopedia/dariacore)  | KEEP |
| 初5 | xaev — i started the UTSC to dariacore pipeline | 未確認 | —  | KEEP |
| 現1 | curren — Accelerate | 2025 | [記事](https://pitchfork.com/thepitch/remember-jane-removers-mashup-genre-dariacore-its-blowing-up-in-japan-now/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | leroy — XO TOUR LLIF3 | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/dariacore/)  | KEEP |
| 現3 | curren — INTERNET_IRIS | 2025 | [記事](https://pitchfork.com/thepitch/remember-jane-removers-mashup-genre-dariacore-its-blowing-up-in-japan-now/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | leroy — ...LIKE WATCHING A ZOMBIE TURN | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/dariacore/)  | KEEP |
| 現5 | leroy — I DID THIS FOR US | 2025 | [記事](https://ototoy.jp/news/124379)  | REPLACE_WITH_POOL_CANDIDATE |

### 28. Hyperflip

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | gum.mp3 & Dazegxd — Mania | 未確認 | —  | KEEP |
| 初2 | carbine — insane | 未確認 | —  | KEEP |
| 初3 | leroy — go white enby go | 未確認 | —  | KEEP |
| 初4 | xaev — i started the UTSC to dariacore pipeline | 未確認 | —  | KEEP |
| 初5 | PAS TASTA — sunameri smoke | 未確認 | —  | KEEP |
| 現1 | valkyrie — next__level #BLISTERS | 2026 | [記事](https://lostfrog.bandcamp.com/album/exceed-gear)  | KEEP |
| 現2 | ST31NER — complextro is not my forte | 2026 | [記事](https://lostfrog.bandcamp.com/album/gate)  | KEEP |
| 現3 | KisamaIs666 — baby eye | 2026 | [記事](https://lostfrog.bandcamp.com/album/hyperflip-tree-friends-3)  | KEEP |
| 現4 | bloblobber — cannot miss (watch me) | 2026 | [記事](https://lostfrog.bandcamp.com/album/complete-bloblobber-guide)  | KEEP |
| 現5 | Syuenn — wayak' ascension | 2026 | [記事](https://lostfrog.bandcamp.com/album/nikkecore-vol-2-second-take)  | KEEP |

### 29. Trap (Rap)

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Jeezy — Standing Ovation | 2005 | [記事](https://musictech.com/guides/essential-guide/best-trap-tracks-songs/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Gucci Mane — Lemonade | 未確認 | —  | KEEP |
| 初3 | Migos — Versace | 未確認 | —  | KEEP |
| 初4 | Future — Mask Off | 未確認 | —  | KEEP |
| 初5 | T.I. — Dope Boyz | 2001 | [記事](https://musictech.com/guides/essential-guide/best-trap-tracks-songs/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Future, Metro Boomin & Kendrick Lamar — Like That | 2024 | [記事](https://pitchfork.com/reviews/tracks/future-metro-boomin-like-that-kendrick-lamar/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Yeat — Breathe | 2024 | [記事](https://www.complex.com/music/a/j-rose/best-songs-of-2024-so-far)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | 21 Savage — redrum | 2024 | [記事](https://musictech.com/guides/essential-guide/best-trap-tracks-songs/)  | KEEP |
| 現4 | Gunna — fukumean | 2023 | [記事](https://musictech.com/guides/essential-guide/best-trap-tracks-songs/)  | KEEP |
| 現5 | Playboi Carti — EVIL J0RDAN | 2025 | [記事](https://musictech.com/guides/essential-guide/best-trap-tracks-songs/)  | KEEP |

### 30. EDM Trap

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Baauer — Harlem Shake | 2012 | [記事](https://sonaa.ca/en/styles/bass/trap/)  | KEEP |
| 初2 | TNGHT — Higher Ground | 2012 | [記事](https://sonaa.ca/en/styles/bass/trap/)  | KEEP |
| 初3 | RL Grime — Core | 2014 | [記事](https://sonaa.ca/en/styles/bass/trap/)  | KEEP |
| 初4 | Hudson Mohawke — Thunder Bay | 2011 | [記事](https://sonaa.ca/en/styles/bass/trap/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | What So Not — Jaguar | 未確認 | —  | KEEP |
| 現1 | Saka & Of The Trees — Ghoul | 2024 | [記事](https://edm.com/features/best-songs-2024/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Knock2 — crank the bass, play the muzik | 2025 | [記事](https://www.thenocturnaltimes.com/the-nocturnal-times-top-electronic-dance-songs-of-2025/)  | KEEP |
| 現3 | ISOxo, Knock2 & RL Grime — SMACK TALK | 2024 | [記事](https://edm.com/music-releases/isoxo-knock2-rl-grime-smack-talk/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | RL Grime, ISOxo & Knock2 — Smack Talk | 2024 | [記事](https://djpoolrecords.com/beatport-top-streamed-tracks-2025-trap-future-bass/)  | KEEP |
| 現5 | ISOxo — how2fly | 2023 | [記事](https://sonaa.ca/en/styles/bass/trap/)  | KEEP |

### 31. Cloud Rap

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Clams Casino — I’m God | 2011 | [記事](https://dropo.org/genre/cloud-rap)  | KEEP |
| 初2 | A$AP Rocky — Wassup | 2011 | [記事](https://splice.com/blog/what-is-cloud-rap/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Yung Lean — Ginseng Strip 2002 | 2013 | [記事](https://dropo.org/genre/cloud-rap)  | KEEP |
| 初4 | Lil B — I'm God | 2009 | [記事](https://splice.com/blog/what-is-cloud-rap/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Main Attrakionz — Perfect Skies | 2011 | [記事](https://splice.com/blog/what-is-cloud-rap/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Sickboyrari — Hydrocodone | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/cloud-rap/)  | KEEP |
| 現2 | fakemink, Ecco2k & Mechatok — MAKKA | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/cloud-rap/)  | KEEP |
| 現3 | Nino Paid — Black Ball | 2024 | [記事](https://pitchfork.com/thepitch/nino-paid-black-ball-new-song-listen/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | lucy bedroque — yes, you may | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/cloud-rap/)  | KEEP |
| 現5 | smokedope2016 & Hackle — Buff | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/cloud-rap/)  | KEEP |

### 32. Plugg

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Playboi Carti — Broke Boi | 未確認 | [記事](https://pitchfork.com/thepitch/an-interview-with-mexikodro/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Famous Dex — Drip From My Walk | 未確認 | —  | KEEP |
| 初3 | D Savage — I Know | 未確認 | —  | KEEP |
| 初4 | MexikoDro — Plug! | 未確認 | —  | KEEP |
| 初5 | Summrs — Swing Ya Pole | 未確認 | —  | KEEP |
| 現1 | Serane — Ig | 2024 | [記事](https://www.thefader.com/2024/02/08/serane-paris-rapper-plugg/feed)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Slime Dollaz & DJ Slimebxll — pesos | 2025 | [記事](https://www.thefader.com/2025/03/19/slime-dollaz-dj-slimebxll-pesos-song-review)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | FLEE & StoopidXool — LITA | 2025 | [記事](https://www.thefader.com/2025/07/04/rap-blog-flee-stoopidxool-lita)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Edward Skeletrix — Seatbelt Off | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plugg/)  | KEEP |
| 現5 | kumosai & Lucy Bedroque — 10 shots | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plugg/)  | KEEP |

### 33. PluggnB

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | FLEE & StoopidXool ft. Brent Faiyaz — SWISH/USE 2 | 2019 | [記事](https://www.midiaresearch.com/blog/sounds-of-2025-midia-and-splice-name-pluggnb-musics-fastest-growing-genre)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Autumn! — One Way | 未確認 | —  | KEEP |
| 初3 | Summrs — Swing Ya Pole | 未確認 | —  | KEEP |
| 初4 | Kankan — Wokeup | 未確認 | —  | KEEP |
| 初5 | Tony Shhnow — Vet | 未確認 | —  | KEEP |
| 現1 | Lil Shine — Sex Talk | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/pluggnb/)  | KEEP |
| 現2 | Blizzi Boi — 42 Song | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/pluggnb/)  | KEEP |
| 現3 | WoochieWobbler & Baby Osama — dog bich remix | 2025 | [記事](https://www.thefader.com/2025/02/11/woochie-wobbler-baby-osama-walk-em-down-on-dog-bich)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | DANNI SNOW & Blizzi Boi — YUNC 4167 | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/pluggnb/)  | KEEP |
| 現5 | shteppi — missed calls. | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/pluggnb/)  | KEEP |

### 34. Rage Rap

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Playboi Carti — Stop Breathing | 2020 | [記事](https://pitchfork.com/reviews/albums/playboi-carti-whole-lotta-red/)  | KEEP |
| 初2 | Trippie Redd & Playboi Carti — Miss the Rage | 2021 | [記事](https://fnmnl.tv/2021/09/15/135130?amp=1)  | KEEP |
| 初3 | Playboi Carti — Rockstar Made | 2020 | [記事](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time)  | KEEP |
| 初4 | SoFaygo — Off the Map | 2020 | [記事](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Trippie Redd ft. Playboi Carti — Miss the Rage | 2021 | [記事](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | OsamaSon — Lil O The Impaler | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP |
| 現2 | bleood — alucard | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP |
| 現3 | KD! — flex a band | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP |
| 現4 | Che — Green Day | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP |
| 現5 | OsamaSon — Ik What You Did Last Summer | 2024 | [記事](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time)  | REPLACE_WITH_POOL_CANDIDATE |

### 35. New Jerk / Jerk Revival

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | xaviersobased — Patchmade | 2022 | [記事](https://www.thefader.com/2026/02/03/xaviersobased-fader-cover-story-intervew-album-dj-rennessy)  | KEEP / 年代要修正 |
| 初2 | phreshboyswag — Inspire | 未確認 | —  | KEEP |
| 初3 | Nettspend — Shine n Peace | 未確認 | —  | KEEP |
| 初4 | Duwap Kaine — DuwapSoBased | 未確認 | —  | KEEP |
| 初5 | xaviersobased — 40 | 未確認 | —  | KEEP |
| 現1 | Nettspend — Shine N Peace | 2023 | [記事](https://www.thefader.com/2026/02/03/xaviersobased-fader-cover-story-intervew-album-dj-rennessy)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | matt proxy — catfish | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/jerk/)  | KEEP |
| 現3 | fakemink — Fidelio | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/jerk/)  | KEEP |
| 現4 | Nettspend ft. xaviersobased — impact | 2025 | [記事](https://ourgenerationmusic.com/new-music-spotlight/nettspend-impact-xaviersobased-rolling-loud/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | phreshboyswag — i'm honestly so lost and music doesnt help anymore | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/jerk/)  | KEEP |

### 36. Axxcelerationist / Neo Rage

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | OsamaSon — Troops | 未確認 | —  | KEEP / 分類例外 |
| 初2 | OsamaSon — CTS-V | 未確認 | —  | KEEP / 分類例外 |
| 初3 | OsamaSon — Uno | 未確認 | —  | KEEP / 分類例外 |
| 初4 | Che — Miley Cyrus | 未確認 | —  | KEEP / 分類例外 |
| 初5 | OsamaSon — ik what you did last summer | 未確認 | —  | KEEP / 分類例外 |
| 現1 | 2slimey — reef | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plugg/)  | KEEP / 分類例外 |
| 現2 | OsamaSon — Break Da News | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP / 分類例外 |
| 現3 | OsamaSon — Made Sum Plans | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP / 分類例外 |
| 現4 | Che — SAYSO | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP / 分類例外 |
| 現5 | Che — Agenda | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/rage/)  | KEEP / 分類例外 |

### 37. Terror Plugg

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | yuke — ian goin | 未確認 | —  | KEEP |
| 初2 | matt proxy — natural selection | 未確認 | —  | KEEP |
| 初3 | Jshxwty — Running Off | 未確認 | —  | KEEP |
| 初4 | xaviersobased — ghost town | 未確認 | —  | KEEP |
| 初5 | Lazer Dim 700 — Asian Rock | 未確認 | —  | KEEP |
| 現1 | 2slimey — reef | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plugg/)  | KEEP |
| 現2 | yuke — ian goin | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2024/terror-plugg/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | xaviersobased — ghost town | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2024/terror-plugg/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | osamason — horses | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/plugg/)  | KEEP |
| 現5 | Percatric — Real Tears | 2026 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2026/dark-plugg/)  | KEEP |

### 38. Memphis Rap

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Three 6 Mafia — Tear da Club Up ’97 | 1997 | [記事](https://www.kosu.org/music/music/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)  | KEEP |
| 初2 | Gangsta Boo — Where Dem Dollas At | 1998 | [記事](https://www.kosu.org/music/music/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)  | KEEP |
| 初3 | 8Ball & MJG — Mr. Big | 1993 | [記事](https://www.upr.org/npr-news/npr-news/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | Gangsta Pat — Deadly Verses | 1995 | [記事](https://www.upr.org/npr-news/npr-news/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Playa Fly — Nobody | 未確認 | [記事](https://www.vpm.org/npr-news/npr-news/2023-07-21/how-memphis-rap-charted-a-passage-from-delta-blues)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | GloRilla — Yeah Glo! | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2024/memphis-rap/?r=100)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Denzel Curry — Him | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/memphis-rap/)  | KEEP |
| 現3 | $uicideboy$ — Now and at the Hour of Our Death | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/memphis-rap/)  | KEEP |
| 現4 | GloRilla & Sexyy Red — WHATCHU KNO ABOUT ME | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2024/memphis-rap/?r=100)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Moneybagg Yo & GloRilla — On Wat U On | 2023 | [記事](https://pitchfork.com/reviews/albums/glorilla-glorious/)  | REPLACE_WITH_POOL_CANDIDATE |

### 39. Phonk (Original / Memphis系)

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | SpaceGhostPurrp — Been Fweago | 2012 | [記事](https://thecatrave.com/phonk-guide)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | SpaceGhostPurrp — Bringin' tha Phonk | 2010 | [記事](https://thecatrave.com/phonk-guide)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | DJ Smokey — Codeine Demonz | 未確認 | —  | KEEP |
| 初4 | Soudiere & DJ Smokey — Land of Da Phonk | 未確認 | —  | KEEP |
| 初5 | SpaceGhostPurrp — Pheel tha Phonk | 2010 | [記事](https://thecatrave.com/phonk-guide)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | SOUDIERE feat. ROLAND JONES — DIE 2 WIN | 2024 | [記事](https://www.youtube.com/watch?v=-JnobgqEctc)  | KEEP |
| 現2 | Lazaru$ & SPACED — TOO LATE TO TALK | 2024 | [記事](https://www.youtube.com/watch?v=-JnobgqEctc)  | KEEP |
| 現3 | BERRYMANE, ROLAND JONES & VON STORM — CHASIN Ms | 2024 | [記事](https://www.youtube.com/watch?v=-JnobgqEctc)  | KEEP |
| 現4 | kloudbug — NoOnePossessesYou | 2024 | [記事](https://www.youtube.com/watch?v=-JnobgqEctc)  | KEEP |
| 現5 | ROLAND JONES — GOTTA KILL YOU | 2024 | [記事](https://www.youtube.com/watch?v=-JnobgqEctc)  | KEEP |

### 40. Drift Phonk

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Kaito Shoma — Scary Garry | 2016 | [記事](https://freqbuilder.com/lineage/drift-phonk)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | DVRST — Close Eyes | 2021 | [記事](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/)  | KEEP |
| 初3 | INTERWORLD — METAMORPHOSIS | 2021 | [記事](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/)  | KEEP |
| 初4 | Pharmacist — North Memphis | 2019 | [記事](https://freqbuilder.com/lineage/drift-phonk)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Ghostface Playa — Why Not | 未確認 | —  | KEEP |
| 現1 | Global Publisher — sleep phonk | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2025/drift-phonk/)  | KEEP |
| 現2 | RAIZHELL — Faster | 2025 | [記事](https://zolotube.com/watch?v=UdDyHCXxcuI)  | KEEP |
| 現3 | Towa & Token — Most Wanted | 2024 | [記事](https://volt.fm/playlist/91060821/drift-phonk-and-midnight-racing-2026)  | KEEP |
| 現4 | Kordhell — Murder in My Mind | 2022 | [記事](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/) [曲目DB](https://musicbrainz.org/release/2b79071c-ab6f-4eb3-92c7-95e1d66235bb) | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Blackoyé — GRAVE GLITCH | 2025 | [記事](https://volt.fm/playlist/91060821/drift-phonk-and-midnight-racing-2026)  | KEEP |

### 41. Baile Funk / Brazilian Funk

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Cidinho & Doca — Rap da Felicidade | 未確認 | —  | KEEP |
| 初2 | Bonde do Tigrão — Cerol na Mão | 未確認 | [記事](https://ra.co/features/3967)  | KEEP |
| 初3 | MC Fioti — Bum Bum Tam Tam | 未確認 | —  | KEEP |
| 初4 | MC Kevinho — Olha a Explosão | 未確認 | —  | KEEP |
| 初5 | Anitta — Vai Malandra | 未確認 | —  | KEEP |
| 現1 | DJ Arana — Montagem Phonk Brasileiro | 2024 | [記事](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo)  | KEEP |
| 現2 | Adame DJ — Acid Baile 2 | 2024 | [記事](https://webflow-vc.martech.soundcloud.com/stories/post/baile-funk-evolution-playlist/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Cybass & SPEEDTEST — Terror da Capeira | 2024 | [記事](https://webflow-vc.martech.soundcloud.com/stories/post/baile-funk-evolution-playlist/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Deekapz — Ritmado Mágico no Sumarézinho | 2024 | [記事](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo)  | KEEP |
| 現5 | Adame DJ — Agressiva no Voltmix 2 | 2024 | [記事](https://webflow-vc.martech.soundcloud.com/stories/post/baile-funk-evolution-playlist/)  | REPLACE_WITH_POOL_CANDIDATE |

### 42. Funk Automotivo

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | DJ Arana — Montagem Phonk Brasileiro | 未確認 | [記事](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo)  | KEEP |
| 初2 | DJ P7 & MC PR — Automotivo Destruidor, P7 Vai Te Destruir | 未確認 | [記事](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo)  | KEEP |
| 初3 | DJ Blakes & MC GW — Beat das Galáxias | 未確認 | [記事](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo)  | KEEP |
| 初4 | DJ NK3 — PLANETA DESCONHECIDO | 未確認 | —  | KEEP |
| 初5 | DJ RICK 013 & MC GW — THE AUTOTREM 1.0 | 未確認 | —  | KEEP |
| 現1 | MC GW, DJ Patrick Muniz, MC Pânico & DJ LP Malvadão — Automotivo Toma Botada | 2025 | [記事](https://djpoolrecords.com/tag/beatport-top-streamed-tracks-2025-brazilian-funk/)  | KEEP |
| 現2 | MC Madan, MC Menor MT & DJ Ery — Beat Automotivo 6 (O Caveirão Chegou) | 2025 | [記事](https://djpoolrecords.com/tag/beatport-top-streamed-tracks-2025-brazilian-funk/)  | KEEP |
| 現3 | Bibi Babydoll, DJ Brunin XM & KZA Produções — Automotivo Bibi Fogosa | 2023 | [記事](https://billboard.com.br/dia-do-funk-25-funks-mais-importantes-brasil/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | DJ Patrick Muniz, MC LyC4N & MC Kitinho — Automotivo Magnético (feat. JC no beat) | 2025 | [記事](https://music.apple.com/jp/album/automotivo-magn%C3%A9tico-feat-jc-no-beat-single/1808789697)  | KEEP |
| 現5 | DJ Cyberz & MC RD — Automotivo Tic Tac | 2025 | [記事](https://music.apple.com/us/album/automotivo-tic-tac-single/1802696603)  | KEEP |

### 43. Brazilian Phonk

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | 6YNTHMANE & RXDXVIL — BRAZILIAN DANÇA PHONK | 2023 | [記事](https://www.youtube.com/watch?v=XuiL1Le0-34)  | KEEP / 年代要修正 |
| 初2 | Slowboy, lucaf. & Crazy Mano — Brazilian Phonk Mano | 2023 | [記事](https://www.youtube.com/watch?v=XuiL1Le0-34)  | KEEP / 年代要修正 |
| 初3 | Slowboy, NUEKI & Crazy Mano — Life in Rio | 2023 | [記事](https://www.youtube.com/watch?v=XuiL1Le0-34)  | KEEP / 年代要修正 |
| 初4 | S3BZS & MC GW — MONTAGEM - PR FUNK | 未確認 | —  | KEEP |
| 初5 | TRASHXRL — Orquestra Maldita | 未確認 | —  | KEEP |
| 現1 | NCTS — MADRUGADA | 2025 | [記事](https://www.youtube.com/watch?v=GGuwo1lkljc)  | KEEP |
| 現2 | S3BZS, MC GW & MC Menor da Alvorada — Montagem – PR Funk | 2023 | [記事](https://billboard.com.br/brazilian-phonk-conheca-a-variacao-gringa-do-funk-que-e-viral-no-tik-tok/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | ATLXS — PASSO BEM SOLTO | 2024 | [記事](https://www.youtube.com/watch?v=GGuwo1lkljc)  | KEEP |
| 現4 | MXZI — Montagem Ritmo Brutal | 2025 | [記事](https://www.youtube.com/watch?v=GGuwo1lkljc)  | KEEP |
| 現5 | TRXSHBXY & Sayfalse — CALA BOCA | 2025 | [記事](https://www.youtube.com/watch?v=GGuwo1lkljc)  | KEEP |

### 44. Post-Baile-Funk / LatinCore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | DJ Arana — Montagem Phonk Brasileiro | 未確認 | —  | KEEP |
| 初2 | Mu540 & MC GW — A Culpa Eh da Cachaça | 未確認 | —  | KEEP |
| 初3 | DJ Dayeh & MC Bibi Drak — As Mais Top | 未確認 | —  | KEEP |
| 初4 | DJ P7 & MC PR — Automotivo Destruidor, P7 Vai Te Destruir | 未確認 | —  | KEEP |
| 初5 | Deekapz — Ritmado Mágico no Sumarézinho | 未確認 | —  | KEEP |
| 現1 | Dj Ramon Sucesso, Mc Gw, MC DUCASA, Mc Morena & DJ K — Vai Tomando | 2026 | [記事](https://music.apple.com/us/album/distortion-vol-i/6825034416)  | KEEP |
| 現2 | CRRDR — SORRY BUT THE LATINCORE | 2025 | [記事](https://pitchfork.com/thepitch/the-5-most-exciting-musical-rabbit-holes-of-2025-so-far/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Dj Ramon Sucesso feat. Clementaum — Pique das Arábia | 2026 | [記事](https://music.apple.com/us/album/distortion-vol-i/6825034416)  | KEEP |
| 現4 | CRRDR — TRAAA | 未確認 | [記事](https://mixmag.net/feature/the-mix-021-crrdr-dj-latin-hardcore-interview-colombia-berlin)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Dj Ramon Sucesso & A-Trak — Pulse Bubble | 2026 | [記事](https://music.apple.com/us/album/distortion-vol-i/6825034416)  | KEEP |

### 45. Hardstyle

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Showtek — FTS | 2007 | [記事](https://www.q-dance.com/en/news/dediqated-or-this-is-the-hardstyle-top-25-of-all-time)  | KEEP |
| 初2 | Headhunterz — Psychedelic | 2007 | [記事](https://sonaa.ca/en/styles/hardcore/hardstyle/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Noisecontrollers — Attack Again | 2009 | [記事](https://sonaa.ca/en/styles/hardcore/hardstyle/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初4 | Wildstylez — Year of Summer | 未確認 | [記事](https://wololosound.com/articulos/top-100-hardstyle-all-time/)  | KEEP |
| 初5 | Brennan Heart — Imaginary | 未確認 | [記事](https://www.q-dance.com/en/news/dediqated-or-this-is-the-hardstyle-top-25-of-all-time)  | KEEP |
| 現1 | Aversion — Activation | 2023 | [記事](https://hardnews.nl/en/these-are-the-winners-of-the-hardstyle-awards-2023/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Brennan Heart, Ran-D & Floor Jansen — Heart Of A Dragon | 2026 | [記事](https://www.hdrr.info/hardstyle-top-100)  | KEEP |
| 現3 | D-Block & S-te-Fan — Embers | 2026 | [記事](https://www.hdrr.info/hardstyle-top-100)  | KEEP |
| 現4 | Phuture Noize & B-Front — Wide Awake | 2024 | [記事](https://loudcave.es/loud-cave-top-100-hardstyle-2024/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | Sub Zero Project ft. Teddy Bee — Won't Let Me Down | 2025 | [記事](https://djmag.com/top100djs/2025/64/sub-zero-project)  | REPLACE_WITH_POOL_CANDIDATE |

### 46. Jumpstyle

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Jeckyll & Hyde — Frozen Flame | 2006 | [記事](https://underowl.net/en/genre/jumpstyle)  | KEEP |
| 初2 | Jeckyll & Hyde — Freefall | 2007 | [記事](https://underowl.net/en/genre/jumpstyle)  | KEEP |
| 初3 | Patrick Jumpen — Holiday | 2007 | [記事](https://underowl.net/en/genre/jumpstyle)  | KEEP |
| 初4 | Da Boy Tommy — Candyman | 2000 | [記事](https://underowl.net/en/genre/jumpstyle)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Scooter — Jumping All Over the World | 2007 | [記事](https://underowl.net/en/genre/jumpstyle)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | Coone — 4 BY 4 BEATS (I Don't Care) | 2025 | [記事](https://volt.fm/genre/4001/jumpstyle)  | KEEP |
| 現2 | Jeckyll & Hyde — Outside World | 2024 | [記事](https://volt.fm/genre/4001/jumpstyle)  | KEEP |
| 現3 | Coone & Robert Falcon — All Of The Lights | 2023 | [記事](https://volt.fm/genre/4001/jumpstyle)  | KEEP |
| 現4 | Coone, LOVIXX & STOSLIV — Don't tell your dreams (hard version) | 2026 | [記事](https://volt.fm/genre/4001/jumpstyle)  | KEEP |
| 現5 | Mark With a K — Oasis (The Dark Horror Remix) | 2023 | [記事](https://volt.fm/genre/4001/jumpstyle)  | KEEP |

### 47. Hardtekk / TikTokTekk

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | DJ CHANSEY & SLAVYAN13 — Meow Boss Tekk | 未確認 | —  | KEEP |
| 初2 | Riversmelt — Tornado Warning Hardtekk | 未確認 | —  | KEEP |
| 初3 | HELLBLADE & MATORO — Acidtekk | 未確認 | —  | KEEP |
| 初4 | LOKIMITDERMASKE & DJ TÖRKE — HAKKEN | 未確認 | —  | KEEP |
| 初5 | LOKIMITDERMASKE, DJ TÖRKE & Lil Texas — HYPA HYPA | 未確認 | —  | KEEP |
| 現1 | YXMI — SLAYER | 2026 | [記事](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)  | KEEP |
| 現2 | YXMI — INTERVENTION | 2026 | [記事](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)  | KEEP |
| 現3 | HELLBLADE — Tank Triad | 2026 | [記事](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)  | KEEP |
| 現4 | V1AL — TRIADTEKK | 2026 | [記事](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)  | KEEP |
| 現5 | XEOE — SERAPH | 2026 | [記事](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)  | KEEP |

### 48. Digicore

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | glaive — astrid | 未確認 | —  | KEEP |
| 初2 | ericdoa — fantasize | 未確認 | —  | KEEP |
| 初3 | d0llywood1 — ihonestlymightjustgiveup | 未確認 | —  | KEEP |
| 初4 | Kite & blackwinterwells — feeling | 2020 | [記事](https://www.thefader.com/2024/06/06/d0llywood1-digicore-hyperpop-soundcloud-interview)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | quinn — i dont want that many friends in the first place | 未確認 | —  | KEEP |
| 現1 | 2hollis — nerve | 2025 | [記事](https://soundcloud.com/stories/post/new-era-digicore-playlist)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | ericdoa — song for when the bar closes | 2024 | [記事](https://soundcloud.com/stories/post/new-era-digicore-playlist)  | REPLACE_WITH_POOL_CANDIDATE |
| 現3 | Jane Remover — Flash in the Pan | 2025 | [記事](https://soundcloud.com/stories/post/new-era-digicore-playlist)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | midwxst — waste time | 2025 | [記事](https://soundcloud.com/stories/post/new-era-digicore-playlist)  | REPLACE_WITH_POOL_CANDIDATE |
| 現5 | xaviersobased — Party At My Place | 2026 | [記事](https://soundcloud.com/stories/post/new-era-digicore-playlist)  | REPLACE_WITH_POOL_CANDIDATE |

### 49. Cinematic Bass

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Danny Olson — Delineate | 2019 | [記事](https://edm.com/music-releases/danny-olson-delineate-lowly/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初2 | Seven Lions — Worlds Apart | 未確認 | —  | KEEP |
| 初3 | ILLENIUM — Crawl Outta Love | 未確認 | —  | KEEP |
| 初4 | Nero — Promises | 未確認 | —  | KEEP |
| 初5 | Apashe — Majesty | 未確認 | —  | KEEP |
| 現1 | Danny Olson & David Frank — Back For You | 2025 | [記事](https://dannyolson.bandcamp.com/album/back-for-you)  | REPLACE_WITH_POOL_CANDIDATE |
| 現2 | Apashe — Human | 2023 | [記事](https://edm.com/music-releases/apashe-malaa-no-escape/)  | KEEP |
| 現3 | Danny Olson ft. KnownAsNat — Another Life | 2025 | [記事](https://routenote.com/radar/listen-to-danny-olsons-another-life-a-powerful-fusion-of-cinematic-bass-and-emotion/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現4 | Seven Lions & Above & Beyond — Over Now | 2023 | [記事](https://edm.com/music-releases/apashe-malaa-no-escape/)  | KEEP |
| 現5 | ILLENIUM & Skylar Grey — From the Ashes | 2022 | [記事](https://edm.com/music-releases/apashe-malaa-no-escape/)  | KEEP |

### 50. Hyper Melodic Tearout

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | PhaseOne & Koven — Lost | 未確認 | —  | KEEP / 分類例外 |
| 初2 | Sullivan King — Someone Else | 未確認 | —  | KEEP / 分類例外 |
| 初3 | Kai Wachi — Better Off Alone | 未確認 | —  | KEEP / 分類例外 |
| 初4 | Excision & Illenium — Gold (Stupid Love) | 未確認 | —  | KEEP / 分類例外 |
| 初5 | Seven Lions & Kill The Noise — The Blood | 未確認 | —  | KEEP / 分類例外 |
| 現1 | PhaseOne, Intervals & Micah Martin — DIVIDE | 2025 | [記事](https://www.albumoftheyear.org/label/25443-sounds-of-mayhem/singles/)  | KEEP / 分類例外 |
| 現2 | PhaseOne & Banks Arcade — PULSE | 2025 | [記事](https://www.albumoftheyear.org/label/25443-sounds-of-mayhem/singles/)  | KEEP / 分類例外 |
| 現3 | PhaseOne & Make Them Suffer — SOS | 2025 | [記事](https://www.albumoftheyear.org/label/25443-sounds-of-mayhem/singles/)  | KEEP / 分類例外 |
| 現4 | Kompany & PhaseOne — DISAPPEAR | 2026 | [記事](https://www.albumoftheyear.org/label/25443-sounds-of-mayhem/singles/)  | KEEP / 分類例外 |
| 現5 | PhaseOne & SISTO — CHOKEPOINT | 2026 | [記事](https://www.albumoftheyear.org/label/25443-sounds-of-mayhem/singles/)  | KEEP / 分類例外 |

### 51. Glitch Hop (実験Hip Hop)

| 枠 | アーティスト — 楽曲 | 年（候補値） | 出典候補 | 旧枠比／警告 |
|---|---|---|---|---|
| 初1 | Flying Lotus — Zodiac Shit | 2010 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/2025/experimental/)  | KEEP |
| 初2 | Dabrye — So Scientific | 2001 | [記事](https://blog.iso50.com/date/2009/page/7/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初3 | Death Grips — Get Got | 2012 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/2025/experimental/)  | KEEP |
| 初4 | Prefuse 73 — Nuno | 2001 | [記事](https://blog.iso50.com/date/2009/page/7/)  | REPLACE_WITH_POOL_CANDIDATE |
| 初5 | Push Button Objects — 360 Degrees (Prefuse 73 Remix) | 2003 | [記事](https://www.factmag.com/2013/07/05/the-essential-prefuse-73/)  | REPLACE_WITH_POOL_CANDIDATE |
| 現1 | heavensouls — shipping times and quiet streets | 2026 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/single/2026/experimental/)  | KEEP |
| 現2 | heavensouls x stickerbush aka the sidepeices — darkskin niggas with lightskin problems | 2025 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/2025/experimental/)  | KEEP |
| 現3 | JPEGMAFIA — either on or off the drugs | 2024 | [記事](https://www.albumoftheyear.org/artist/90855-jpegmafia/)  | KEEP |
| 現4 | JPEGMAFIA — PROTECT THE CROSS | 2025 | [記事](https://www.albumoftheyear.org/2025/releases/?type=single)  | KEEP |
| 現5 | JPEGMAFIA — SIN MIEDO | 2024 | [記事](https://www.albumoftheyear.org/ratings/user-highest-rated/2025/experimental/)  | KEEP |

## 例外・未達・次の確認対象

1. **本表は歴史的510候補を基盤に、v0.2全候補で入替・再配置した再構成案**。欠損の旧Deep Research出力208件をあるものとして使用していない。
2. A/Bとされる候補でも、代表性の記事本文・見出し・文脈を各曲再実読する前に正式採用しない。曲の存在・レーベル・リリース年・アーティストはDiscogs／MusicBrainz等の盤別資料と照合し、公式音源の正確な版は権利者サイトで再確認する。
3. 2022–2026の現在曲で発売年が不明・範囲記載・年条件不一致なら旗を残す。情報がないことと不適合確定は別。適合年が確認できなければ翌作業で曲を差し替える。
4. #36 Axxcelerationist / Neo Rage と #50 Hyper Melodic Tearoutは研究用固定ラベルとして仮置きし、**10曲をジャンルの存在証明や代表曲採用と扱わない**。#04と#51は別枠。
5. 同名楽曲の版違い、複数ジャンル横断候補、1人のアーティスト偏重は追加監査対象。全体集計の詳細・重複個別行はaudit JSONへ。
6. 年/版/音源リンクを実際に追加確認できた曲だけ次のコミットで`SOURCE_CONFIRMED`等へ移し、正式採用と混同しない。各件の修正・変更理由はIssue #1で追う。
