# Context — cronologia/medjugorje

## What this repo is

A source-referenced chronology of the Marian apparitions **reported since
24–25 June 1981** at Medjugorje (parish of St. James, Diocese of Mostar-Duvno,
Herzegovina — then Yugoslavia, now Bosnia and Herzegovina) by six young
people, attributed by the seers to the Virgin Mary as "Queen of Peace"
(Kraljica Mira), together with every located Church act about them.

It is one of the Cronologia family of projects; it follows the shared sourcing
discipline in `.claude/skills/sourcing-rules/SKILL.md`. The apparitions are
recorded as **reported events**: the dataset documents who reported what and
when, and what Church authorities ruled and when, citing the ruling document.
It never asserts the supernatural claim as fact — and on this case neither
does the most favourable Church act, by its own text.

## Domain background an agent needs

- **The object discipline (ADR-0007) is the heart of this repo.** Three
  objects recur and are never merged: (1) the supernatural character of the
  reported apparitions and messages — never affirmed by any authority, and
  under the 2024 Norms art. 23 a supernaturality declaration is, as a rule,
  never issued; (2) worship, devotion and pilgrimage at Medjugorje — the
  object of the Hoser missions, the 2019 pilgrimage authorization and the 2024
  *nihil obstat*, all `adjacent` or favourable-about-the-devotion; (3) named
  persons — the Vlašić acts (2008/2009/2020) are about a man, and Church
  honours or judgments about persons never promote to findings about the
  events.
- **The "Herzegovina affair"** frames everything: Paul VI's decree *Romanis
  Pontificibus* (6 June 1975) ordered the Herzegovinian Franciscans to cede
  most Mostar-Duvno parishes to diocesan clergy; many refused. Medjugorje is a
  Franciscan-run parish, and the diocese-vs-province conflict is the lens
  through which Bishop Žanić and the critical literature read the phenomenon.
  Attribute that reading; do not adopt it.
- **The operative judgment 1991–2024** was the Zadar Declaration's *non
  constat de supernaturalitate* ("it can not be affirmed…"). The CDF's 1998
  Bertone letter confirmed it and classified Bishop Perić's harder *constat de
  non* as "his personal opinion" — while Perić (2017) presented the negative
  judgment as "the position of this Curia". Both are documented; the dataset
  records both and resolves nothing.
- **The Ruini commission** (2010–2014): constitution and delivery are
  documented (the 2010 communiqué names no members); the findings were never
  published. The 13–1–1 vote on the first seven days and the doubts about the
  later phase are **Tornielli's 2017 leak** — always labeled leak-reported,
  partially echoed only by Francis's non-magisterial in-flight remarks of
  13 May 2017.
- **Seer-reported structure**: ten secrets per seer; daily apparitions cease
  at the tenth (Mirjana 1982, Ivanka 1985, Jakov 1998; Vicka, Ivan and Marija
  continue daily). The message series (Thursday 1984, 25th-of-month 1987,
  Mirjana's 2nd-of-month 1987–2020) are the seers' reports published by the
  shrine; the 2024 Note requires "alleged messages" framing and gives the
  Apostolic Visitor approval authority over future publication.
- **Numbers are self-reported.** The only hard series is the shrine's own
  Communion/concelebration registers (47.4M Communions 1985–2024, quoted by
  the DDF in 2024). Yearly pilgrim estimates diverge (~1M web estimates vs
  ~3M per Hoser); "40+ million since 1981" has no counting authority.
- **Caritas of Birmingham** (Sterrett, Alabama; medjugorje.com) is a separate,
  contested US organization — not the shrine, not the Church, not Caritas
  Internationalis. It is both an organization entry and a disambiguation item;
  keep it that way.
- **Mart Bax's wartime-Medjugorje ethnography** was found "very likely"
  fabricated (VU Amsterdam, 2013). Never use it as a fact source; the fraud
  finding itself is citable (`retractionwatch-bax`).

## Known source-access quirks (net-access ladder)

- **md-tm.ba (Diocese of Mostar-Duvno) — connection reset** from this
  session's US datacenter egress; likely country/bot gating, INCONCLUSIVE not
  dead (CWR quotes it live in 2017). Its predecessor **cbismo.com is dead**:
  it 301-redirects to an unrelated squatter domain (observed 2026-08-11). All
  Perić diocesan texts and the diocese's publication of the Vlašić decree
  therefore rest on mirrors; an out-of-band capture of md-tm.ba should be
  requested per net-access rung 5.
- **Browser User-Agent required** (UA filter, not a block): vaticannews.va,
  ncregister.com, medjugorje.ws (403 to plain fetches);
  press.vatican.va bulletin pages and medjugorje.hr render minimal content
  without JavaScript — Wayback snapshots recommended for all of them.
- **Wayback availability API returned persistent 429** during the research
  session, so no snapshots could be confirmed; retry before the first
  archive-refs run.
- **No press bulletin exists** for the Ruini delivery (17–18 Jan 2014,
  checked) or the pilgrimage authorization (12 May 2019, checked) — the
  records are press-office statements to journalists carried by Vatican
  media/news agencies. Do not go hunting for bulletins that are known absent;
  the absence is recorded in the dataset.
- sanctepater.com (second mirror of Žanić 1990) returned 503 — transient,
  inconclusive; the blogspot mirror is the cited one.

## Standing uncertainties (kept honest in the dataset)

- Zovko's sentence (3 vs 3.5 years) and release (Feb 1983 vs ~18 months); the
  trial date rests on tertiary summaries. No primary court document reached.
- Ivanka's birth date: 21 June 1966 (Margry/WRSP) vs 21 July 1966
  (NC Register); devotional sites split the same way.
- The first commission's establishment (reported 11 Jan 1982) and the second's
  final vote day (reported 2 May 1986) — not verified against documents.
- Message-series start dates (1 Mar 1984; 25 Jan 1987) — devotional literature
  only.
- Seers' marriages and residences — devotional biographies and sympathetic
  press; no civil-record verification.
- Mirjana's 2020 ending coincided with COVID gathering bans — coincidence per
  devotional outlets, pointed per skeptics; both reported, neither asserted.
- Zovko's later canonical status (reported 1990s–2000s faculty restrictions) —
  conflicting accounts between devotional defenders and the Mostar chancery;
  flagged in his figure entry.
- Cavalli's appointment date (27 Nov 2021) — per the Holy See daily bulletin,
  not directly reached; flagged until cited to the bulletin.
- Žanić's 1981→1984 reversal — two competing explanations (police pressure vs
  the Ivica Vego affair and the taped interviews); perspectives, not facts.
- The Zadar vote (19–1) comes from secondary accounts, not the declaration
  text.

## Current state (2026-08, English bootstrap wave)

- 36 events, 13 figures, 6 organizations, 10 facts, 41 references, a
  7-item disambiguation block and a 12-rung `approvalLadder` (the ladder and
  the chronology are the two header chips).
- No `meta.threads` taxonomy yet: declaring lanes over a chronology this
  contested is an editorial act that deserves its own ticket, and none has
  decided it. No placesMap/tier map/lineage/branchTimeline/numbersChart.
- **es/pt caches are not yet authored** — `data/i18n/{es,pt}.json` are the
  template stubs, so the i18n-completeness tests fail by design until the
  translation wave. Everything else in the gate is green.
- Informal statements (Žanić 1981, Francis in-flight 2017) are chronology
  events but **not ladder rungs** — they are not acts of judgment, and the
  ladder note says so.

## Scope discipline

This repo stays on the reported apparitions, the Church's acts, and the
institutional history that frames them. The Bosnian war enters only as it
touches Medjugorje (one flagged event); Yugoslav/Bosnian political history,
the wider Herzegovinian Franciscan story, and the devotional message corpus
itself are context, cited only where a dated event requires them. Reported
healings and conversions are recorded, if at all, as reports with named
reporters — no cure or miracle at Medjugorje has been recognised by any
Church authority, and none is recorded here as having occurred.

## For agents

Read `AGENTS.md` first. Any change to `data/*.json` goes through the data-edit
gate: `node scripts/validate-data.js && node --test && node build.js`, then
read the rendered pages before committing. Data and regenerated `docs/` are
committed together.
