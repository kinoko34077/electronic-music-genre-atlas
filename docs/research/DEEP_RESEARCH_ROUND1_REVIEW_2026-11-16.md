# 電子音楽51系統 Deep Research 第1回成果 — 原典確認・暫定資料化レビュー

- 原調査実施: **2026-11-15**（Deep Research可視報告に基づく）
- 本レビュー: **2026-11-16**（GitHub現行仕様・Issueおよび指定原典の再照合）
- ステータス: **REFERENCE_ONLY / PROVISIONAL / NOT_ADOPTED**
- 所有: [研究Issue #1](https://github.com/kinoko34077/electronic-music-genre-atlas/issues/1)、[Control devflow #1031](https://github.com/kinoko34077/devflow/issues/1031)
- 固定基準: [docs/SPECIFICATION.md](../SPECIFICATION.md)
- 参照先: [既存監査](../RESEARCH_REAUDIT_2026-11-15.md)、[510件レビュー台帳](../../data/review_queue_2026-11-15.csv)

> **文書の性質:** Deep Researchの**可視の最終報告書**を元に、分類結果と代表的な出典主張を再編したレビュー資料。**Deep Researchが生成した原本レポートやZIPの完全な複製ではない**。原調査の成果物ZIP・`track_database_510_slots.csv/json`・`genre_findings_51.json`・`source_database.csv`・`catalog.html`・`audit_summary.json`をこの作業環境で取得できなかったため、**それらの行レベル検査・ファイル内容比較・インポートは実施していない**。別途存在する2026-11-14の旧ZIPを今回のDeep Research成果物と誤認しないこと。

## 1. 受入判定と数量

| 対象 | 第1回報告の状態 | 本レビューの判定 |
|---|---|---|
| 固定ジャンル／研究枠 | 51系統の分類・境界を再探索 | 調査結果として保存可能。全51件の原典実読による完了証明ではない |
| 楽曲枠 | 51×（初期5＋現在5）＝**510枠** | **曲名・候補枠 ≠ 有効な代表曲510曲** |
| 曲別資料言及まで再照合 | **14行**（原報告値） | 下表の報告対象。全部がA/B採用確定ではない |
| 今回新たに正規個別音源URLを再特定 | **6行**（原報告値） | 詳細のCSV・プレーヤー動作は未検証。下表に従来から存在するURLもあり同一数とは限らない |
| 正規音源の実再生、国内制限、実機UI | **0件の受入確認** | 未検証 |
| 代表曲の最終採用 | **0曲** | 現行正式台帳は変更不可 |
| Reddit/X/動画等の独立支持件数 | 510曲についての個別確定集計なし | 支持を数値で検証済みと扱わない |

過去の510候補レビューでは選定資料URLがないもの168件、年がないもの178件、音源URLがないもの249件。今回報告からはこの問題の全件解消は確認できない。**第1回Deep Researchは分類・歴史の整理と一部重要曲の根拠確認が主な到達点**であり、ユーザーの「独立言及数・賛同／異論の集計を伴う510曲の完成DB」は未達である。

## 2. 外部原典の抜粋再確認（このレビューで再読したもの）

- **#03 Complextro**: [Pitchfork, 2021](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/)は2010–2012年を中心期とし、`Spitfire`・`Shave It`を直接重要作として挙げる。**現代Complextroの5曲の存在を証明する資料ではない**。
- **#04 Glitch Hop**: [Bandcamp Daily, 2018](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list)はTipper等のBass系Glitch Hopを説明し、`Ton Of Brix`を代表アンセムとして挙げる。[本人Bandcamp](https://tipper.bandcamp.com/track/ton-of-brix-vip-mix)は`Ton Of Brix (VIP Mix)`と明記。2005年`Ton Of Bricks`と混同しない。
- **#12 Trench**: [INFEKT本人の解説](https://infektdubstep.com/trench/)で2014年Getterの先行使用と2022年の改称提案を確認。音響史・名称史・シーン実態を一律同一視しない。
- **#10 Colour Bass**: [Chime本人FAQ](https://www.chimetunes.net/faq)で2016年頃の用語提唱と2020年以降の普及を確認。**このFAQには`From Fairies to Fire`の曲名は掲載されていない**。原報告の当該曲「B」はFAQ単独では裏付かず、曲別B根拠を追加するまで**HOLD**。
- **#34 Rage Rap**: [Complex 2025](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time)が`Fighting My Demons`・`Stop Breathing`を曲名付きで評価している。
- **#49 Cinematic Bass**: [EDM.com 2019](https://edm.com/music-releases/danny-olson-delineate-lowly/)でDanny Olson本人の自称スタイルとしての由来を確認。独立ジャンルとしての定着までの証明ではない。
- **#47 Hardtekk/TikTokTekk**: [Pitchfork 2026](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing/)は`YXMI — SLAYER`を曲名付きで言及。単なるアーティスト紹介ではないが、「同シーンを代表する5曲」の立証や音源版照合は別。
- **#13 Experimental Bass**: [EDM Identity 2025](https://edmidentity.com/2025/11/21/g-jones-eprom-disk-utility/)には`Noontime Acid`への具体的言及があり、EPをExperimental Bassの文脈で解説。**EP全体へのジャンル評価と曲単体の代表性は分離**。
- [Q-dance Hardstyle Top 25](https://www.q-dance.com/en/news/dediqated-or-this-is-the-hardstyle-top-25-of-all-time)の参照URLは発見されたが、今回の再読経路では本文を取得できず、個々の曲の掲載を検証済みとはしない。

## 3. 51固定系統の分類・境界（原報告を要約）

**表の「報告による判定」はDeep Researchの分析内容の要約であり、全51系統をこのレビューで独立実証したことを意味しない。** 参照リンクも原報告が挙げた探索先を中心に付したもので、上記「外部原典の抜粋再確認」とは検証範囲を区別する。

| ID | 固定系統 | 報告による位置付け | 初期／現在・境界上の要点 | 参考資料 |
|---:|---|---|---|---|
| 01 | UK Dubstep | 確立ジャンル | Croydon/Big Apple周辺の形成史と深い低域・140系の継続。現在のDubstep全体と同一視しない。 | [参照](https://www.redbull.com/gb-en/history-of-dubstep-music) |
| 02 | Electro House | 確立サブジャンル | 2000年代のElectro Houseと2020年代の再興を分離。 | [参照](https://sonaa.ca/en/styles/house/electro-house/) |
| 03 | Complextro | 歴史的マイクロジャンル | 2010〜2012年が中心。後年の音色編集技法の継承と継続シーンを区別。 | [参照](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/) |
| 04 | Glitch Hop | Bass系サブジャンル | Tipper・edIT・Opiuo等のブレイク／低域系。#51の実験Hip Hopとは区別。 | [参照](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list) |
| 05 | Brostep | 確立サブジャンル | Rusko/Caspa以降の中高域ベース変化、2010年代USブームと後年の名称変化。 | [参照](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/) |
| 06 | Riddim Dubstep | 確立サブジャンル | Subfiltronik等のミニマルDubstepとTrench再呼称の境界。 | [参照](https://ukf.com/read/infekts-guide-to-riddim/) |
| 07 | Melodic Dubstep | 確立サブジャンル | Seven Lions・Xilent等の成立史。広義Melodic Bassと区別。 | [参照](https://dubstepguide.net/genres/melodic-dubstep/) |
| 08 | Future Bass | 確立サブジャンル | Rustie/Hudson Mohawke/Flume等の系譜、現行例は曲名ごとの検査が必要。 | [参照](https://edm.com/features/best-future-bass-of-the-decade/) |
| 09 | Future Riddim | 新興マイクロジャンル | Oolacile周辺の名称・流れ。形成期と現在の時代差は短い。 | [参照](https://relentlessbeats.com/2021/10/rb-exclusive-interview-ace-auras-arizona-debut/) |
| 10 | Colour Bass | 音響設計系マイクロジャンル | Chimeが2016年前後に呼称提唱、2020以降浸透。個々の曲の典型性は別検証。 | [参照](https://www.chimetunes.net/faq) |
| 11 | Modern Tearout | 現代Bassスタイル | MARAUD(A)等の強いTearoutを現在の文脈で把握。旧Tearoutと区別。 | [参照](https://splice.com/sounds/packs/dropgun-samples/tearout-dubstep/story) |
| 12 | Trench / Modern Riddim | シーンの再呼称 | Getterによる2014年TrenchとINFEKTによる2022年以降の名称提案を区別。 | [参照](https://infektdubstep.com/trench/) |
| 13 | Experimental Bass | 広義Umbrella | G Jones・EPROM等の実験的Bassを包含、単一の狭い音響条件へ固定しない。 | [参照](https://edmidentity.com/2025/11/21/g-jones-eprom-disk-utility/) |
| 14 | Drum & Bass | 確立ジャンル | Goldie、LTJ Bukem、Roni Size等の1990年代成立史と現代の継続。 | [参照](https://www.beatportal.com/articles/4445-beatports-definitive-history-of-drum-bass) |
| 15 | Neurofunk | DnB下位ジャンル | Ed Rush & Optical、Noisia、Mefjus等の硬質な音響系譜。 | [参照](https://amajunglist.com/genres/neurofunk/story) |
| 16 | Trance | 確立ジャンル | Age of Love、Café del Mar、For an Angel等の成立期と現代の継続。 | [参照](https://djmag.com/features/how-paul-van-dyks-angel-changed-trance-forever) |
| 17 | Nightcore / Sped-up Edit | 編集文化 | Nightcore誕生と2020年代の公式Sped-up版を区別。権利処理が歴史的代表作のURL要件と衝突。 | [参照](https://www.academia.edu/34536062/Nightcore_and_the_Virtues_of_Virtuality) |
| 18 | Hyperpop | ネット発マイクロジャンル／媒体名 | PC Music/SOPHIE等の系譜。後年の用語の拡散・希薄化に注意。 | [参照](https://pitchfork.com/features/article/the-lost-promises-of-hyperpoptimism/) |
| 19 | HexD | ネットマイクロジャンル | bitcrushingと歪みの用例はあるが現在の代表5曲の独立資料が薄い。 | [参照](https://www.melodigging.com/genre/hexd) |
| 20 | Sigilkore | ネットシーン／マイクロジャンル | Luci4/Jewelxxet等の形成とTikTok以降の名称拡散を分ける。 | [参照](https://nobells.blog/the-life-and-death-of-sigilkore/) |
| 21 | Jersey Club | 地域クラブジャンル | Newark/Jerseyの地域史と近年ポップ・ラップへの波及を区別。 | [参照](https://djmag.com/features/endless-evolution-jersey-club) |
| 22 | Krushclub | 2020年代の新興マイクロジャンル | Luci4/Lumi Athena等の系譜。形成期と現在の差が短い。 | [参照](https://www.edmprod.com/krushclub/) |
| 23 | Plunderphonics | 制作思想・ジャンル概念 | John Oswaldを核とする録音再構成。著作権・公式音源制約あり。 | [参照](https://www.bloomsbury.com/us/plunderphonics-9798765119495/) |
| 24 | Mashup | 制作実践・ネット文化 | 既存楽曲の結合技法。独立した学術的定義はあるが正規音源が限られる。 | [参照](https://mtosmt.org/issues/mto.13.19.3/mto.13.19.3.boone.html) |
| 25 | Mashcore | Breakcore系マイクロジャンル | Venetian Snares・Sickboy・Shitmatなど。現代候補がShoebillに集中しがち。 | [参照](https://ghz.tokyo/breakcore_pt4/) |
| 26 | Breakcore | 確立ジャンル | 既存Breakcoreと2020年代のAmen/ネットタグの用法を区別。 | [参照](https://www.nts.live/shows/the-nts-guide-to/episodes/the-nts-guide-to-breakcore-20th-august-2025) |
| 27 | Dariacore | ネットマイクロジャンル | leroy/Jane Removerの2021年作品と2025〜26年日本等の再興。 | [参照](https://pitchfork.com/thepitch/remember-jane-removers-mashup-genre-dariacore-its-blowing-up-in-japan-now/) |
| 28 | Hyperflip | スタイル／シーン運動 | xaev、Lost Frogなど。単一音響ジャンルより多ジャンル・サンプル文化の側面。 | [参照](https://realsound.jp/tech/2026/07/post-2447757.html) |
| 29 | Trap (Rap) | 確立Hip Hopサブジャンル | Atlanta/Southern Trapの起源、EDM Trapと区別。 | [参照](https://online.berklee.edu/takenote/trap-music-where-it-came-from-and-where-its-going/) |
| 30 | EDM Trap | 確立EDMサブジャンル | TNGHT/Baauer/RL GrimeからISOxo・Knock2の再興。 | [参照](https://edm.com/music-releases/isoxo-knock2-rl-grime-smack-talk/) |
| 31 | Cloud Rap | ネットHip Hopスタイル | Lil B/Clams Casino等の系譜。2020年代の再評価と再興。 | [参照](https://www.musicradar.com/news/the-beginners-guide-to-cloud-rap) |
| 32 | Plugg | ネットRapマイクロジャンル | BeatPluggz/MexikoDro周辺の形成史、現在の用例を区別。 | [参照](https://www.mixcloud.com/blog/2026/02/23/a-guide-to-plug-with-redkoffee/) |
| 33 | PluggnB | Plugg派生マイクロジャンル | SlayWorld等の形成とR&B旋律・コード系を伴う現行音楽。 | [参照](https://splice.com/blog/what-is-pluggnb/) |
| 34 | Rage Rap | 現代Rapマイクロジャンル | Whole Lotta Redを転換点とする説と曲別の代表評価。 | [参照](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time) |
| 35 | New Jerk / Jerk Revival | ネットRap再興運動 | 旧Jerkとxaviersobased等の現代Nu-Jerkの関係。 | [参照](https://www.powmag.net/p/nu-jerk-2025-nettspend-yhapojj-xaviersobased) |
| 36 | Axxcelerationist / Neo Rage | 未検証の固定研究ラベル | 高BPM・強歪みの現代Rage現象はあるが、Axxcelerationist/Neo Rage名自体の独立用例不足。 | [参照](https://www.dazeddigital.com/music/article/68951/1/rage-star-osamason-psykotic-album-interview-2025-rage-rap) |
| 37 | Terror Plugg | 新興Rapマイクロジャンル | Yuke「ian goin」等の専門記事用例あり、代表5曲の総意は未確認。 | [参照](https://pitchfork.com/features/lists-and-guides/2024-song-of-the-summer/) |
| 38 | Memphis Rap | 確立地域Hip Hop | Three 6 Mafia等の地域史・カセット文化とサンプリング。 | [参照](https://www.tandfonline.com/doi/abs/10.1080/03007766.2023.2282883) |
| 39 | Phonk (Original / Memphis系) | Memphis派生ネットスタイル | SpaceGhostPurrp等の原型と後年のDrift Phonkを分ける。 | [参照](https://pitchfork.com/thepitch/how-phonk-became-the-most-lucrative-yet-lifeless-genre-of-the-2020s/) |
| 40 | Drift Phonk | ネットDanceマイクロジャンル | 東欧・ロシア圏ネットシーン、cowbell/drift映像との関係。 | [参照](https://www.unisc.edu.au/about/unisc-news/news-archive/2024/april/how-a-global-crisis-drift-racing-and-memphis-hip-hop-gave-us-phonk-the-music-of-the-tiktok-generation) |
| 41 | Baile Funk / Brazilian Funk | 確立ブラジル地域ジャンル | Rio、Miami Bass受容から現在への地域文化史。 | [参照](https://www.scielo.br/j/vb/a/QnVRPGWKdVp4Zs9cKVgPJQP/) |
| 42 | Funk Automotivo | ブラジルFunk内様式 | カーサウンドシステム・低域・反復等の文脈。 | [参照](https://www.thefader.com/2024/02/01/nts-announces-new-baile-funk-compilation-funkbr-sao-paulo) |
| 43 | Brazilian Phonk | 複合・市場タグ | Brazilian Funkと世界的Phonk呼称の複合、原型Phonkと別に説明。 | [参照](https://billboard.com.br/brazilian-phonk-conheca-a-variacao-gringa-do-funk-que-e-viral-no-tik-tok/) |
| 44 | Post-Baile-Funk / LatinCore | 比較研究枠 | Post-Baile-FunkとCRRDR等のLatincoreを無条件に同義にしない。 | [参照](https://ra.co/features/4370) |
| 45 | Hardstyle | 確立Hard Danceジャンル | Q-dance歴代アンセム等のシーン内実績。原文ページの読取は今回未確認。 | [参照](https://www.q-dance.com/en/news/dediqated-or-this-is-the-hardstyle-top-25-of-all-time) |
| 46 | Jumpstyle | 確立Hard Danceジャンル／ダンス文化 | Da Rick/Da Boy Tommy等からTikTok期の再興まで。 | [参照](https://sonaa.ca/en/styles/hardcore/jumpstyle/) |
| 47 | Hardtekk / TikTokTekk | 地域Hard Danceシーン＋SNS上の編集文化 | 旧東ドイツHardtekk史と2026年TikTokTekkは別時相。 | [参照](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing) |
| 48 | Digicore | ネットRapシーン | SoundCloud/Discord周辺でHyperpopと重なりながら独自の文脈。 | [参照](https://www.thefader.com/2024/06/06/d0llywood1-digicore-hyperpop-soundcloud-interview) |
| 49 | Cinematic Bass | アーティスト起点のスタイル名称 | Danny Olsonの自称Cinematic BassとApashe等への拡大。単一ジャンルの独立性未確認。 | [参照](https://edm.com/music-releases/danny-olson-delineate-lowly/) |
| 50 | Hyper Melodic Tearout | 未検証の固定研究ラベル | Redditにmelodic tearout推薦はあるが、Hyper Melodic Tearoutの独立ジャンル性は未確認。 | [参照](https://www.reddit.com/r/dubstep/comments/1tec4xu/melodic_tearout/) |
| 51 | Glitch Hop (実験Hip Hop) | 実験Hip Hop側の研究枠 | J Dilla/Madlib/Flying Lotus/Prefuse 73等の実験的な制作系譜。#04と同一視しない。 | [参照](https://www.arpjournal.com/asarpwp/lateral-dynamics-processing-in-experimental-hip-hop-flying-lotus-madlib-oh-no-j-dilla-and-prefuse-73/) |

分類ID・名称は現行`SPECIFICATION.md`の51件と一致。分類上の評価は現行固定名称の変更・統合を承認するものではない。

## 4. 原報告の「14行」曲別根拠リード（採用確定ではない）

| ID | 期 | 曲・版 | 原報告の暫定級 | 何を確認した／保留したか | 参照URL | 現レビュー状況 |
|---:|---|---|---|---|---|---|
| 03 | 初期 | Porter Robinson — Spitfire | A | Pitchforkがcrucial listeningと明示 | [資料](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/)・[楽曲](https://music.apple.com/au/song/974822173) | 記事・曲名 |
| 03 | 初期 | Zedd — Shave It | A | Pitchforkがcrucial listeningと明示 | [資料](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/)・[楽曲](https://music.apple.com/us/song/972368109) | 記事・曲名 |
| 03 | 初期 | Porter Robinson — Say My Name (Original Mix) | A/B | DJ Magが2010年のComplextro作品として説明 | [資料](https://djmag.com/content/10-moments-defined-porter-robinson)・[楽曲](https://music.apple.com/us/song/396864327) | 資料・曲名 |
| 04 | 初期 | Tipper — Ton Of Brix (VIP Mix) | A | Bandcamp Dailyが代表アンセムとして言及。2005年のTon Of Bricksとは別版。 | [資料](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list)・[楽曲](https://tipper.bandcamp.com/track/ton-of-brix-vip-mix) | 記事・版名 |
| 10 | 初期 | Chime — From Fairies to Fire | B（要修正） | Chime FAQはColour Bassの2016年命名を記載するが、この曲名は記載していない。元報告のB評価は曲別根拠不足。 | [資料](https://www.chimetunes.net/faq)・[楽曲](https://music.apple.com/us/song/1105043608) | 要追加資料 |
| 10 | 初期 | Chime & Ace Aura — Interdimensional | B候補 | Insomniacが共作を曲名で言及。代表性は追加評価。 | [資料](https://www.insomniac.com/music/artists/ace-aura/)・[楽曲](https://music.apple.com/gb/song/1472083683) | 曲名・版 |
| 10 | 初期 | Au5 & Chime — Voidwalkers | B候補 | Monstercat公式とChimeによる制作解説は曲に対応するが、代表性はなお検証。 | [資料](https://www.monstercat.com/release/MCS1067)・[楽曲](https://music.apple.com/us/song/1501758046) | 曲名・版 |
| 34 | 現在 | Ken Carson — Fighting My Demons (2023) | A | ComplexがRage Rapの代表曲として明示評価。 | [資料](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time) | 記事・年代 |
| 34 | 初期 | Playboi Carti — Stop Breathing (2020) | A | ComplexがRage Rapの歴史的作品として列挙。 | [資料](https://www.complex.com/music/a/antonio-johri/best-rage-rap-songs-of-all-time) | 記事・年代 |
| 37 | 現在候補 | Yuke — ian goin | A候補 | PitchforkがTerror Pluggの文脈で言及したと報告。今回該当原典本文の独立再確認は未実施。 | [資料](https://pitchfork.com/features/lists-and-guides/2024-song-of-the-summer/) | 未再照合 |
| 30 | 現在 | RL Grime, ISOxo & Knock2 — smack talk | A候補 | EDM.comがTrapの世代横断・シーン文脈で扱ったと報告。 | [資料](https://edm.com/music-releases/isoxo-knock2-rl-grime-smack-talk/) | 未再照合 |
| 13 | 現在 | G Jones & EPROM — Noontime Acid | B候補 | EDM Identityは実際に曲名を挙げ、EP全体をExperimental Bassと説明。曲単体の代表性評価とは区別。 | [資料](https://edmidentity.com/2025/11/21/g-jones-eprom-disk-utility/)・[楽曲](https://eprom.bandcamp.com/track/noontime-acid) | 記事で曲名確認 |
| 43 | 現在候補 | S3BZS & MC GW — MONTAGEM - PR FUNK | A/B候補 | Billboard BrasilによるBrazilian Phonkの文脈での言及と報告。個別正規音源未再確認。 | [資料](https://billboard.com.br/brazilian-phonk-conheca-a-variacao-gringa-do-funk-que-e-viral-no-tik-tok/) | 未再照合 |
| 47 | 現在 | YXMI — SLAYER | B候補 | Pitchforkが曲名を直接挙げてTikTokTekkの例として言及。音源版・URLは別検証。 | [資料](https://pitchfork.com/thepitch/how-hardtekk-became-the-cursed-soundtrack-of-looksmaxxing) | 曲名 |

- 上表の**14行**は、第1回Deep Researchが個別根拠を集中的に再確認したと記載した曲の範囲を反映する。各行のリンク先がすべて最新の権利者・版・日本地域の再生を満たすと断定しない。
- **代表性への昇格禁止**: `From Fairies to Fire`の例のように、ジャンルの名称・シーン史を説明するアーティスト資料と、楽曲を重要作と明示評価する曲別資料を区別する。
- **初期と現在の版を区別**: `Stop Breathing`は2020年で現在（原則2022–26新作）ではなく初期側の候補とする。2020年代形成ジャンルでは初期・現在の歴史差を個別説明する。
- `Ton Of Brix (VIP Mix)` は後年の別版を現在新作として数えない。2011年/2012年表記は初出・EP・再収録の区別に注意。
- A/B/Cは原報告における**引用文脈の暫定判断**であり、この表から正式データの採用ステータスを更新しない。

## 5. 未完了事項・方法上の警戒点

1. **原本データ不可視**: 今回のDeep Research成果物ZIP・CSV/JSON/HTML本体を取得できなかったため、行数やIDの唯一性、初期・現在255ずつ、原稿とDBの主張一致、引用指標、出典参照切れ、URLスキーマ・重複のテストは未実施。
2. **510採用の根拠不足**: 現在まで曲別出典14行の確認という報告であり、510曲の「独立資料での言及数」「コミュニティ支持」「原録音年・版」「公式直接音源・再生」が一体で成立したわけではない。
3. **ジャンル分類の不確定性**: #36, #49, #50は名称の独立性未確認、#44は2つの名称の比較枠、#51は実験Hip Hop側。#03の現代枠、#22, #27, #28, #37等の新興枠は時代差・シーン継続を逐一説明する。
4. **サンプル／編集音楽の権利構造**: #17 Nightcore、#23 Plunderphonics、#24 Mashupは歴史的代表性がある作品でも権利者公式個別ページが存在しない場合がある。正式データへは「代表性の証拠はある／正規URLは未確認」を分離して残す。
5. **オンライン合意の扱い**: Reddit upvote、Xいいね、YouTubeコメントの数値は現報告からは有効な個別観測値を復元できない。実測・投稿日・取得日・独立性・賛否を確認するまでカウント不能とし、ゼロ件（無反応）と未確認を区別する。
6. **資料への格納位置**: ここは`docs/research/`配下の**未受入・履歴資料**であり、`data/track_slots_2026-11-14.csv`、`data/research_2026-11-14.json`、既存Viewerや正式仕様の代替ではない。元のDeep Researchファイルを入手した時は、別途バイト単位の検査・出典監査を経て追加する。

## 6. 結論

第1回Deep Researchは**51系統の分類・歴史・境界について幅広い比較のたたき台**として利用可能で、Complextro・Glitch Hop・Trench・Colour Bass・Rage Rap等には原典確認できる個別成果がある。**510曲の代表曲選定／ソーシャル合意数の監査／正規音源の動作検証は未達**。本資料の登録は完成・公開・採用の承認を意味しない。以後は [研究Issue #1](https://github.com/kinoko34077/electronic-music-genre-atlas/issues/1) の現行受入条件で継続する。
