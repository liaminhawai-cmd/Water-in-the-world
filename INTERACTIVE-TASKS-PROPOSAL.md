# Water in the World — Interactive Tasks Proposal

A menu of decision-and-consequence simulations in the spirit of the Coasts, Deserts and
Mountains interactives, purpose-built for the Year 7 *Water in the World* unit. Each one is
a single self-contained HTML file (same warm-paper suite look, works offline on iPads),
each maps to specific lessons, curriculum content descriptors (VC2HG8K01–K05) and the
Term-3 CAT, and each ends with a printable report so it can be a graded task or a lesson
activity.

I've grouped them by priority. My recommendation: build **#1 (Share the River)** first —
it's the strongest fit for the CAT and the unit's headline idea (competing values +
scarcity), and it reuses the most vocabulary the new Vocab Hub teaches.

---

## The shared design pattern (what makes these work)

Every one of your existing interactives has the same bones, and these follow them:

1. **A place with a name and a map.** A hand-drawn SVG map with toggleable data layers
   (rainfall, population, land use…). Students *read* the map before they act — that's the
   PQE / BOLTSS skill from lessons 1.1–2.2.
2. **A brief, a role, and a budget.** You are the water manager / the council / the
   catchment authority. You have limited money, water or political capital.
3. **Stakeholders with faces and conflicting wants.** Consultable characters whose mood and
   trust bars move as you decide — this is the "competing values" of lesson 2.3 made
   tangible.
4. **Costed choices with visible trade-offs.** Every decision spends something and moves the
   indicators; nothing is free. The Deserts mine-planner and Mountains trek-planner both
   live or die on this.
5. **A resolution + reflection + report.** A scored outcome, an explanation of *why*, and a
   name/ID PDF export with a verification code — identical to the Vocab Hub's report so you
   grade them the same way.

Reusing this pattern keeps build cost down and gives students a consistent "grammar" of
interaction across the whole unit.

---

## 1. "Share the River" — a Murray–Darling allocation simulator  ★ recommended first

**Maps to:** Lesson 2.1 (water uses), 2.3 (values of water, First Nations custodianship),
3.2 (drought), and the **CAT** (Murray–Darling water theft / competing values). Content:
VC2HG8K02, K03, K04.

**The premise.** You are the catchment authority for a stretch of the Murray–Darling in a
year the Bureau has just declared **El Niño**. There is less water in the system than there
are claims on it. Over four seasons you decide who gets how much.

**The map.** A schematic river with, upstream to downstream: irrigated cotton and fruit
farms, a regional town (domestic + industry), a Ramsar wetland, and a First Nations
community with cultural flows and a sacred waterhole (billabong). Toggle layers: **allocation
(ML)**, **river health**, **rainfall/inflow**.

**The mechanic.** Each season you have an inflow (shrinking as the drought bites) and a set
of **allocation sliders** — irrigation, town supply, environmental flow, cultural flow. They
must sum to no more than the water available. Each choice moves indicators:

| Indicator | Rises when… | Falls when… |
|---|---|---|
| Farm economy ($) | irrigators get water | you cut their allocation |
| Town wellbeing | domestic supply is met | taps run low |
| River health | environmental flows kept up | over-extraction, algal-bloom risk (biological hazard!) |
| Cultural/spiritual value | cultural flows honoured, waterhole kept alive | the billabong dries |

**Stakeholders** (consultable cards, à la Coasts): an irrigator, the town mayor, an
ecologist, and a Traditional Owner / custodian. Each argues their value; their trust bar
moves with your calls. Deliberately, **you cannot fully satisfy everyone** — that's the
learning.

**Twist events** drawn each season: a heatwave spikes town demand; an upstream irrigator is
caught taking more than their licence (the CAT's "water theft"); a wet pulse arrives. These
force re-planning and echo lesson 3.2.

**Resolution.** After four seasons, a scored report on all four values plus a written
"defend your hardest trade-off" box → PDF. Vocabulary surfaced live: *scarcity, allocation,
irrigation, environmental/cultural/spiritual value, custodian, sustainable, drought,
El Niño*.

**Why first:** it's the CAT rehearsed as a game, it's the unit's thesis (water has many
competing values and not enough to go round), and it needs only one map + slider engine.

**Build estimate:** ~1.5–2 files' worth of effort; the slider/indicator engine is the new
piece, the rest reuses your character-card and map patterns.

---

## 2. "Day Zero" — a city water-security planner

**Maps to:** Lesson 2.2 (the world's water, accessibility, scarcity, reservoirs,
desalination, groundwater) and the CAT's **Cape Town** case study. Content: VC2HG8K04.

**The premise.** You run a coastal city's water supply through a drought year with a falling
dam. The countdown to "Day Zero" (the day the taps are switched off) is the clock.

**The map / dashboard.** A dam-level gauge, a 12-month rainfall forecast band (variable, and
you don't get to see it all at once), and a demand meter. Layers: current storage, projected
storage under your plan.

**The mechanic.** Each month you choose from **costed supply- and demand-side options**, each
with a $ cost, a lead time and a yield:
- **Demand:** restriction levels (L1–L6), leak-fix programs, public campaigns.
- **Supply:** commission a **desalination** plant (expensive, slow to build, drought-proof),
  sink **groundwater** bores (fast, but the aquifer can deplete), buy tankered water, recycle
  water.

Push restrictions too hard and public support falls; build desal too late and you hit Day
Zero; lean on groundwater and you drain the aquifer (a consequence that bites next year).

**Stakeholders:** the mayor (re-election, hates restrictions), an engineer (build now!), a
farmer on the city fringe, an environmental scientist (watch that aquifer).

**Resolution.** Did you avoid Day Zero, at what cost, and how sustainably? Report compares
your path to the real Cape Town timeline. Vocabulary: *scarcity, finite, accessible,
reservoir, desalination, aquifer, groundwater, consumption, variability, mitigation*.

**Build estimate:** ~1 file; closest in shape to your existing planners (gauge + costed
options + countdown), so the cheapest high-value build.

---

## 3. "Flood Watch" — a hazard-response and evacuation simulator

**Maps to:** Lesson 3.1 (hazard vs disaster, the four hazard families) and 3.2 (floods,
inundation, evacuation, mitigation). Content: VC2HG8K05.

**The premise.** A hydrological hazard is developing over your town's catchment. You move a
community through **prepare → respond → recover**, and the core lesson is baked into the
mechanic: *a hazard only becomes a disaster if you're unprepared.*

**The map.** A town on a floodplain with an **inundation layer** that rises with the river
gauge; low-lying streets, a hospital, a caravan park, a levee. Toggle: flood extent at 1-in-
10 / 1-in-50 / 1-in-100 year levels.

**The mechanic, in three phases:**
- **Prepare (before):** spend a mitigation budget — raise the levee, buy sandbags, build a
  warning system, run community drills, zone the caravan park out of the floodplain.
- **Respond (during):** the river rises over hours; decide **when** to issue the evacuation
  order (too early = cost + cry-wolf; too late = lives at risk) and which zones to clear.
- **Recover (after):** allocate recovery funds; a debrief scores how much harm your earlier
  *mitigation* prevented.

**Consequence model:** every dollar of preparation visibly reduces the disaster's damage —
students see the hazard/disaster distinction as cause and effect, not a definition to
memorise.

**Resolution.** A "harm prevented vs harm suffered" score + timeline replay → report.
Vocabulary: *hazard, disaster, hydrological, atmospheric, inundation, evacuation, mitigation,
flood, torrential*.

**Build estimate:** ~1.5 files; the rising-inundation animation and the timed evacuation
decision are the novel bits.

---

## 4. "Follow the Drop" — a water-cycle & catchment journey (support-tier / lower-stakes)

**Maps to:** Lesson 1.1 (water cycle) and 1.4 (how water changes places). Content:
VC2HG8K01. Aimed at the **foundation/support** end — concrete, forgiving, great as a Base-
camp companion.

**The premise.** You *are* a water molecule. Guide yourself through the cycle and down a
catchment, making small choices, watching the processes happen.

**The mechanic.** At each stage pick your next move and see the labelled process fire:
sea → **evaporation** → **condensation** into a cloud → **precipitation** → then either
**transpiration** back up (via a tree), **infiltration** to **groundwater**, or run off into
a river where you experience **erosion** on the outer bank, **deposition** on the inner, and
watch a **meander** and eventually an **oxbow/billabong** form. Each transition is a small
animated SVG with the morpheme breakdown shown (ties straight back to the Vocab Hub).

**Lower stakes on purpose:** no failing, no budget — it's an explorable diagram with a
collect-the-processes checklist and a short end quiz. This is the on-ramp for students who
find the decision-heavy sims overwhelming, and it directly reinforces the two most
diagram-friendly lessons.

**Build estimate:** ~1 file; mostly the SVG process animations you already have seeds for in
the Vocab Hub (evaporation, river-bend and oxbow SVGs are done).

---

## How these fit together

- **Sequence with the unit:** #4 during Topic 1, #1 and #2 during Topic 2, #3 during Topic 3
  — each lands the week its vocabulary is taught, and the Vocab Hub preteaches the words
  first.
- **Differentiation is built in:** #4 is the support ramp; #1 is the richest extension. The
  same student can meet the same content (competing water values) at very different depths.
- **One report format across all of them + the Vocab Hub**, so assessment and the
  verification-code workflow stay identical.
- **Shared code:** a small reusable "planner kit" (map + layers, character cards, costed-
  choice engine, indicator bars, report/PDF) would cut the build time of #2 and #3
  substantially once #1 exists.

**Suggested first build:** *Share the River* (#1) — highest curriculum and CAT payoff — or
*Day Zero* (#2) if you'd rather start with the cheapest, most planner-like one. Tell me which
and I'll build it end to end, the same way as the Vocab Hub (authored + adversarially fact-
checked + smoke-tested).
