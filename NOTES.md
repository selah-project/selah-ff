# The Selah Fulfulde Rendering — NOTES

*ff.v1 · chair 73 · lit and sealed 2026-09-15. Fulfulde (Fula,
Peul, Pulaar-Fulfulde continuum), ~35–40M speakers across the
Sahel from Senegal to Sudan — the first Sahel chair. A Latin-script
chair with hooked letters (ɓ ɗ ŋ ñ ƴ) and a THREE-SIDED thermometer:
French on the west, Hausa on the east, English underneath — and the
seating found a fourth side nobody set a guard for.*

## The seal

| Count | Value |
|---|---|
| Verses | 23,213 / 23,213 |
| Token spine ≡ en floor | 23,213 / 23,213, zero mismatches; surfaces byte-identical |
| `Yaawe` at the Name seat | **6,828 / 6,828 — 100.00%, zero deviations** (6,844 in the flow) — the same count the mai chair sealed on |
| `Eloohim` (flow) | 2,510 |
| ⟨את⟩ | 11,866 in the token row ≡ 11,866 in the flow ≡ the en floor, zero asymmetric seats in either direction — and ff BEATS the floor: en fails its own flow/gloss marker check ×92; ff is correct at all 92 (verified token-by-token against the OSHB) |
| Erasure (Alla / Dieu / Seigneur / jahannama at divine seats) | **0** |
| French thermometer (est / et / de / la / dans / qui / Dieu / Seigneur) | **0** — the west guard reads cold across every probe |
| Hausa thermometer (da / ya / ba / sai / kuma / amma-as-connective) | **0** (33 lawful `amma` = the cubit, rendering אמה) |
| English thermometer (word-boundary, outside ⟨⟩) | **0** |
| Greek/Cyrillic/CJK residue | **0 / 0 / 0** |
| `yiite` or `jahannama` for Sheol | **0** — Sheol stands as `Seol` at 65/66 seats (Isa 7:11 reads the Masoretic pointing "ask it"; Class-B Q7) |
| Empty flows | **0** |
| Empty glosses | 740 — the nan/mai posture: compound-numeral and merged-function-word seats where the meaning sits whole on the neighbor token (nan sealed with 614, mai with 309) |
| Census flags at seal | **0** |

## Cruxes of the chair

- **The whitelist held the wall.** `les` ×893 is Fulfulde's own
  *beneath* (`les lekki`, under the tree), not the French article;
  `Joomi`/`Laamɗo` are the chair's human-master and king words; `to`
  ×6,030 is the Fulfulde locative (collocates: Yaawe, suudu,
  Yerushalayim), not English; `amma` 33/35 is the cubit. A
  thermometer without these whitelists would have reported noise
  instead of the seven real bleeds it found.
- **The boundary class must carry the hooked letters and the
  apostrophes.** Every ff census runs word boundaries as
  `[A-Za-zÀ-ɏɓɗŊŋÑñƳƴ'ʼ’]` — without ɓ ɗ ŋ ñ ƴ and the three
  apostrophe codepoints, `wi'i`-class verbs shed and false edges
  open. Names carrying Latin-Ext `ḥ` (Yaḥat, Baḥurim) still open a
  false edge; adjudicate by hand.
- **The fourth side: script contamination.** 95 verses carried
  Cyrillic homoglyphs (а е о н р с т у х for their Latin twins —
  invisible on the page, fatal to every grep), plus a 66-verse class
  of *phonetic* Greek/Cyrillic substitutions (`λaɓɓi`, `ϩaɗondirde`,
  `aдo`) with no safe mechanical map, plus CJK strays and one
  literal Russian fragment inside a supplied-word bracket
  (1 Chr 29:21 `⟨ произ⟩`). Homoglyphs were mapped back verse-listed;
  the phonetic class was re-pressed. **Normalize script before
  trusting any string comparison on a Latin chair.**
- **The eaten-word markers.** The flow-assembler inserts ⟨את⟩ before
  the first *substring* match of the object's gloss with no word
  boundary — and Fulfulde's object pronouns are 1–2 letters (`e`,
  `ɓe`, `on`), so it fired inside longer words 181 times
  (`Yaaw⟨את⟩ e`, `ɓiɓ⟨את⟩ ɓe`). The same bug lives in the en floor
  (55 verses: `fa⟨את⟩ther`) — English function words are just long
  enough that it rarely fires. Every word rejoined exactly; 21
  markers re-placed boundary-guarded on the `marks` anchor.
- **Dan 3:12 said the opposite.** `לא פלחין` ("they do NOT serve")
  rendered positive — the accusation that sends the three to the
  furnace was erased; the same verse's own `sujjataa` carried the
  correct negative form. Restored: `ɓe gollirtaa`.
- **The Aqedah walk-back.** Gen 22:8 rendered לעלה as `coktirgol`
  (*redemption*) — atonement doctrine in Abraham's mouth, smoothing
  *away from* an en floor that had already laid the verse bare. Same
  pattern at Ps 110:4 (`laabi Malkii-Tsedek`, "after the order of" —
  the received reading over the floor's bare "upon my word, O
  Malki-Tsedek"). Both restored to the floor's bare posture.
- **The man of God, twice misnamed.** The only two absolute erasures
  in 305,507 seats: `gorko Alla on` at 1 Kgs 13:19/13:20 — the
  Arabic loan in one chapter of Kings, against the chair's own
  `gorko Eloohim` ×34. Cured from the corpus's own majority.
- **The center verse.** Lev 8:35 doubles שמר on the `reen-`
  guard-root (`mba reeni ⟨את⟩ reegol Yaawe`) with `mba maayaano` —
  that you die not. Isa 7:14 holds `suka debbo` (the young woman),
  the virgin-technical terms available and declined. Ex 3:14 stands
  verbal: `Mi Laatii Wo Mi Laatii`, identical at all three seats.
  Ps 22:17 holds the kethib: `hono arslanaa` — *like a lion* — in a
  language whose commercial Bibles all render "pierced."
- **Ezekiel 31:6 — the hand rebuild.** One verse refused the whole
  press ladder and was rebuilt by hand against the Hebrew, 16 seats,
  every word attested in the chair's own corpus (`ceŋe` 31:5 ·
  `mahi ɗomiraaɗe` Ps 104:17 · `cate` 31:13 · `jeyi ladde` 31:13 ·
  `e les mun` = 31:17's own בצלו). Recorded in
  `dev/scripts/ff_flow_hand_pass.py`.
- **The marker that wandered.** In Jer 16:11 the press left *natti
  mi* ("forsook me") bare and lodged the ⟨את⟩ marker inside
  `laamuuji` — "the other gods," a clause the Hebrew gives no את.
  The wound enacted the verse. Testimony and charge:
  `docs/charge/the-marker-that-wandered.md` (selah repo).
- **The 2 Chr 5:9 fabrication reflex.** Two ladder rungs both
  fabricated ⟨את⟩ before הארון (the ark takes the marker in most
  verses; מן הארון here has none). Hand-stripped twice.
- **Never tail a verifier.** 67 spine mismatches sat invisible
  behind a `tail -N` for three rounds. Read verifiers whole.
- **Jer 8:13's phantom token.** The press invented a token 'וין' (a
  shard of ואין) with an empty gloss, shifting 8 seats, and json-
  errored at all four ladder rungs; deleted by hand.
- **Native-check words** (flagged, not swept): `waaworde` (Gen 3:15
  "the woman"), `ƴi'e` for horns (Gen 22:13), `lelwude` for swallow
  (Jonah 2:1), `yourɓe→ɓe` at Gen 8:16 (floor says "your sons" —
  `worɓe`?), and the lane-4 new-lexicon words `duppeteendi`,
  `cukkuri`, `lonto`, `teppere`, `helay`, `goopi`, `liingu`, `gaawe`.

## Tekoa

Verdict: **the chair's discipline is better than its dictionary —
and its markers are perfect.** Gloss parity 11,866/11,866 with zero
asymmetry and zero fabrications (nan repaired 92 / introduced 59;
ff repaired 92 / introduced 0). The Name never erased anywhere in
305,507 seats; `Adonaay` 435/435 divine, `Shadday` 48/48 with the
field/breasts homograph right at all 34 non-divine seats; the
`Eel`(divine)/`El`(Bethel) split maintained; gazelles right in the
Song. 7/10 tough verses stood bare. Six lanes; class-A discharged
via `dev/scripts/ff_tekoa_class_a.py` (1,153 files — script
normalization, 184 eaten-word markers, 72 Name seats, the erasure
pair, 19 thermometer bleeds, 67 tough-verse repairs, 726 bracket-
hygiene edits, 109 garble, 138 draft-speak), then a 116-verse press
ladder (fr8 109/116 → fr9 7/7 → fr10 2/3 → one hand rebuild) and
the hygiene loop, converged to all-exact. Full report:
`data/experiments/ff-seating/ff-tekoa-report.md` (selah repo).

Class B PENDING SCOTT — the twelve questions (full text in
`manifest.edn`): the name canon that cascades (20 names, 786
spellings; Moshe 171 vs Muusaa 170 — a Hebraic-vs-Arabic register
fork; the `-a` suffix; gentilic derivation); `Adonaay` at 117
human-master seats; the Tzevaot form (266 seats, 72 spellings);
what a false god may be called (`ilaaji`/`Allaaji` vs the chair's
own `Eloohim` majority); Aramaic מרא; appositions on divine seats;
Isa 7:11's pointing lens; the nefesh register (rides the open en-v3
question); reverential capitals; the 62 remaining suffixed bracket
forms + bracketed-Hebrew policy; the floor-level repairs ff
surfaced (the floor's own 92, the assembler substring bug, Aramaic
ית as a marker-family candidate); apostrophe canon (U+0027 at
97.71%) + parenthetical Hebrew glosses + `[…]` brackets.

## The burn

23,213 / 23,213 verses, z.ai glm-5.2 with glm-5.3 re-presses.
Ladder for stragglers and repairs: max-tokens 24–32k, then
temperature 0.55, then the glm-5.3 tier at 48k, then +0.7. ~300
verses re-pressed at seating (residue 89 + spine cohort 67 + Tekoa
press list 116 + stragglers); three hand passes recorded in
`dev/scripts/ff_flow_hand_pass.py` (selah repo). Rails:
`docs/methodology/translation-discipline/ff.md` (written in
Fulfulde), commit d99563fa.
