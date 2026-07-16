# Water in the World — Vocab Hub

A single-file vocabulary preteaching and revision tool for the Year 7 Humanities (Geography)
unit **Water in the World** (Term 3). Open `water-vocab-hub.html` in any browser — no
install, no internet needed after loading, works on school laptops and iPads.

## What it does

**One lesson = one short set of key words (5–7).** Students pick the lesson the class is
learning and work through three steps:

1. **Meet the words** — each word with its meaning and the morphemes that build it
   (with an optional home-language toggle for key terms: Mandarin, Cantonese, Vietnamese,
   Arabic, Farsi, Urdu, Amharic, Malayalam).
2. **Build the words** — assemble each word from morpheme tiles (prefix → root → suffix)
   drawn from a bank that includes plausible decoys. Completing a word unlocks its
   definition and word-history. Borrowed/opaque words (billabong, hazard, El Niño…) are
   handled as honest word-origin questions instead of invented parts.
3. **Use the words** — apply tasks (cloze, scenario, description, diagram) **sampled from
   a bank**, so neighbouring students rarely see the same items.

**Quick review** (home screen): a weighted shuffle of ~6 words from earlier lessons —
words a student has missed come back more often, every run is a different mix, and each
session is logged. Designed as a 5-minute do-now at the start of a lesson.

**Adaptive tiers**, per lesson:
- **⛺ Base camp** (support): the same morphemes inside everyday primary-school words
  (`transport`, `unbreakable`, `settlement`…). Offered automatically after a rough lesson,
  self-selectable any time, low-stigma framing.
- **⛰ Stretch** (extension): heavier unit words built from now-known parts
  (`desalination`, `aquifer`, `tributary`, `hydrometeorological`…) plus "word alchemy"
  transfer questions. Unlocks after finishing the lesson's apply tasks.

**Reports**: every task records the **first attempt**; wrong answers loop until mastered.
The report shows per-lesson scores, base camp/stretch results, full review history, an
aggregated "words needing another go" list, and a verification code (hash of name + ID +
scores). Students print to PDF and submit.

## Lesson coverage

| Lesson | Words |
|---|---|
| 1.1 The Water Cycle | evaporation, condensation, precipitation, transpiration, convectional, distribution |
| 1.2 Sustainable Use of Water | resource, natural, renewable, non-renewable, recyclable, sustainable |
| 1.3 Australia's Natural Resources | mineral, deposit, export, hydroelectric, bauxite, basin |
| 1.4 How Does Water Change Places? | erosion, deposition, sediment, meander, oxbow, billabong |
| 2.1 Water Uses | irrigation, domestic, consumption, navigation, recreation, industrial |
| 2.2 The World's Water | scarcity, accessible, groundwater, glacier, finite, reservoir |
| 2.3 The Significance of Water | significance, economic, cultural, spiritual, aesthetic, custodian |
| 3.1 Hazards & Disasters | hazard, disaster, atmospheric, hydrological, geological, biological |
| 3.2 Droughts & Floods | drought, flood, El Niño, oscillation, evacuation, inundation |

Morphemes deliberately spiral: *spir* (transpiration → spiritual → perspire), *posit*
(deposit → deposition), *hydro* (hydroelectric → hydrological → hydrometeorological),
*tribut* (distribution → tributary), *und* (inundation → abundant), *cult*
(aquaculture → cultural → agriculture).

## Deploying

- **Share the file**: post `water-vocab-hub.html` on Compass/Teams — students double-click.
- **GitHub Pages**: Settings → Pages → deploy from branch; the tool then lives at a URL.

Progress is stored in the browser (localStorage) per device. "Start over" on the home
screen wipes it.

## Notes for teachers

- Scores are first attempts, but everything is eventually mastered via the retry loop —
  a rough first-try score with everything cleared is honest, finished work.
- Apply items are sampled and options shuffled per student; review sets are weighted
  random draws. Screens next to each other won't match.
- The tool never needs a server: no data leaves the device except the printed report.
