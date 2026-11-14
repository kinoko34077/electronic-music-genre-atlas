# 51-bin / 510-slot research re-audit — 2026-11-15

**Status: active candidate research; NOT a finished 510-recording atlas.** Owning [Issue #1](https://github.com/kinoko34077/electronic-music-genre-atlas/issues/1), contract [SPECIFICATION](SPECIFICATION.md), parent [devflow Control #1031](https://github.com/kinoko34077/devflow/issues/1031).

## Purpose and data boundaries

- **Canonical research slots** remain `data/track_slots_2026-11-14.csv`: 510 core slots + 1 extra; 16 historically populated, 495 core uncollected. The earlier `音源確認` and A/B flags are historical claims until individually audited. No direct audio stream playback or Japan/iPhone region tests have been demonstrated.
- **Unaltered chat-era archive**: `archive/legacy/2026-11-14-chat-export/` is retained as historical material, not accepted output.
- **Active candidate review queue**: `data/review_queue_2026-11-15.csv` maps the *exact 510 archived candidate rows* to stable original slot keys, keeps every artist/title/source/audio string intact, and marks **every row CANDIDATE_UNVERIFIED**. This makes all work visible without deceptively populating the canonical accepted slots.
- **New targeted source audit**: `data/track_source_reaudit_2026-11-15.json` records 20 track/version-focused claims (including supplemental leads and existing Colour Bass surplus); A/B/C indications are source-role classifications, not final adoption. All have `adopted=false` and `audio_playback_checked=false`.

## Mechanical validation (candidate queue)

| Check | Observed |
| --- | ---: |
| Archived rows / worklist rows | 510 / 510 |
| Fixed genre bins | 51 |
| Initial / current candidate slots | 255 / 255 |
| Distinct genre × period groups | 102, each exactly 5 |
| Missing **original-first-release** year in historical rows | 178 |
| Missing track-specific selection-source URL | 168 |
| Missing purported individual audio URL | 249 |
| Missing both source and audio URL | 69 |
| Legacy labels differing from canonical inventory | 1 of 51 bins: #51 (10 rows) |
| Rows carrying weak-source heuristic warning | 184 (heuristic only; not human A/B reclassification) |
| Approved/adopted new recordings from this import | **0** |

The one label discrepancy is preserved in `legacy_genre` and normalized only in `canonical_genre`: fixed #51 is **Glitch Hop (実験Hip Hop)**; archive had **Experimental Hip Hop（Glitch Hopとは別）**. Do not redefine the fixed category or conflate #51 with bass-scene Glitch Hop #04.

Each queue issue flag has a literal meaning; e.g. `SOURCE_TRACK_MENTION_NOT_REAUDITED` is **not** an assertion of actual source support, and `AUDIO_URL_VERSION_AND_RIGHTS_UNVERIFIED` is **not** a verified play URL. `TAG_PLAYLIST_OR_DISCOGRAPHY_INSUFFICIENT_FOR_AB` is a review heuristic; do not treat its absence as A/B validation.

## Source-specific progress

Targeted batch has **20** entries: A=4, B=7, C=9 (provisional editorial-role classification), **10** entries have independently rechecked named-song source statements plus identifiable song-page metadata; 0 actually listened/region-verified, and 0 newly adopted. Counts do not upgrade the historic 16.

### #03 Complextro

- [Pitchfork, 2021](https://pitchfork.com/features/lists-and-guides/microgenres-25th-anniversary/) explicitly dates the microgenre **2010–2012**, calls out **Porter Robinson — Spitfire** and **Zedd — Shave It** as crucial listening. [Official Porter upload of Spitfire](https://www.youtube.com/watch?v=rgT1qFIWHYc) and [Zedd original single](https://music.apple.com/us/song/972368109) match track/era; actual streaming not exercised.
- [DJ Mag's Porter history](https://djmag.com/content/10-moments-defined-porter-robinson) explicitly evaluates **Say My Name (2010)** as characteristic complextro. [Recording Arts Canada](https://recordingarts.com/record/evolution-of-house-music/complextro) names **Kill Everybody**, **The Devil's Den** and **Internet Friends** as examples. Track-specific recording metadata has been corroborated through individual Apple Music song pages.
- Contemporary works with elaborate bass editing, an artist tag or the word “complextro” in their title cannot automatically establish an independently continuous 2022–2026 Complextro scene. The five current slots **remain unadopted** until direct evidence is found or the non-independent-continuity exception is reasoned.

### #04 Glitch Hop, distinct from #51

- [Bandcamp Daily, 2018](https://daily.bandcamp.com/lists/bandcamp-glitch-hop-list) refers to **Tipper — Ton Of Brix** as a quintessential anthem. [Tipper's original 2005 *Tip Hop* listing](https://tipper.bandcamp.com/album/tip-hop) spells the title **Ton Of Bricks**; [2011 *Bubble Control*](https://tipper.bandcamp.com/track/ton-of-brix-vip-mix-2) is explicitly a *VIP Mix*. The editorial naming and the original/VIP edition are **not yet proven interchangeable**. Do not attach the VIP to the original recording's slot.
- Source names several other artists and examples, but a general artist overview cannot substantiate five formative songs or five 2022–2026 representative songs. Rights-holder Glitch Hop Community tags establish C-level association, not automatic A/B representative role.

### #10 Colour Bass

- [Chime's first-person history](https://www.chimetunes.net/blog) places name coinage around **2016** and broader recognition from **2020**; do not treat every melodic dubstep track as Colour Bass.
- [Insomniac Ace Aura profile](https://www.insomniac.com/music/artists/ace-aura/) discusses **Interdimensional** and **Coma** by name; [Monstercat Voidwalkers original](https://www.monstercat.com/release/MCS1067) identifies release 2020. The corresponding official track pages and 2019–2020 first years have been checked; the source-audit JSON records classification evidence.
- [Run The Trap, 2022](https://runthetrap.com/2022/02/28/chime-rainbow-rave-parade/) explicitly discusses **Rainbow Rave Parade** as Colour Bass and describes its musical construction; [original single](https://music.apple.com/us/song/1609186345) is dated 2022. Do not substitute the [2025 VIP version](https://music.apple.com/us/song/1826592513).
- **Au5 — Cryptochrome** is on [Colour Bass Vol. 3 (2022)](https://music.apple.com/us/song/1605849146). This demonstrates a curated genre-compilation association (C) but does not by itself support an independent representative-grade B assessment.
- **The Other Side (2023)**, **Liminal (2024)**, **Pyroclastic (2024)**: label song releases and first years are confirmed; independence as representative *Colour Bass* recordings remains unverified (C). The 2025 song **Between** is version/date verified, but [Chime describes an evolving UK dubstep direction from Sep 2025](https://www.chimetunes.net/music); don't classify by performer alone.
- The six original contemporary Colour Bass entries include one extra beyond the fixed five slots. Preserve the surplus without silently overwriting the canonical order.

## First unfinished work / exit criteria

1. Reconcile review queue candidates against existing 16 recorded canonical slots without duplicating them; grade each **track-specific** A/B editorial statement, first-release year and original/remix/VIP version.
2. For #03 / #04 / #10 then all other bins, locate official **individual** audio/video pages and verify artist/title/version/first year. Check playback and region on an actual supported player before marking streamed.
3. Distinguish editorial A/B evidence from label compilations/genre-tag C. Reject reviral older releases incorrectly presented as “current,” and don't turn *technical influence* into false independent genre continuation.
4. Promote to canonical adopted slots **only after** version-correct official track URL + track-specific A/B justification and playback/UI acceptance under the repo spec. Record reasoned non-independent-bin exceptions, never fill invented songs to make exactly 510.

### Verification performed

- Live GitHub Control, research Issue #1, repository spec, provenance notes and legacy ZIP inspected. Project Drive research-evidence and music-genre standards read.
- Archival candidate CSV parsed preserving embedded quotes and commas; slot uniqueness and 51×2×5 invariant checked, mismatched #51 alias flagged.
- Named editorial claims and recording metadata examined on linked source/official publisher pages; **actual audio playback, Japanese availability and iPhone hardware not verified**.
- No edits to original historical archive; no changes to canonical research slots or viewer in this tranche.
