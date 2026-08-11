# medjugorje — the reported apparitions at Medjugorje, a chronology

An open, source-referenced chronology of the **reported Marian apparitions at
Medjugorje** (parish of St. James, Diocese of Mostar-Duvno, Bosnia and
Herzegovina) from June 1981 to the present, and of the Catholic Church's acts
about them — from the diocesan commissions and the 1991 Zadar Declaration to
the 2024 *nihil obstat* "The Queen of Peace". Part of the
[cronologia](https://github.com/cronologia) family.

Published site: <https://cronologia.github.io/medjugorje/> (en / es / pt).

## Posture

The apparitions are recorded as **reported** events: the dataset documents who
reported what and when, and what Church authorities ruled and when — it never
asserts the supernatural claim as fact. On this subject that posture is also
the Church's own, and the ladder of Church acts is the spine of the repo:

- **1982–1986:** Bishop Pavao Žanić's diocesan commissions investigated; the
  final vote (11 nothing-supernatural, 2 authentic, 1 *in nucleo*,
  1 abstention) is known only through the bishop's own 1990 published account —
  the report was never published.
- **10 April 1991:** the Zadar Declaration of the Yugoslav bishops — "it can
  not be affirmed that one is dealing with supernatural apparitions and
  revelations" (*non constat de supernaturalitate*) — remained the operative
  judgment, cited by the CDF itself (Bertone letter, 1998), for 33 years.
- **2010–2014:** the Ruini commission delivered findings that were **never
  published**; every vote figure in circulation is a 2017 press leak
  (Tornielli), and the dataset labels it leak-reported wherever it appears.
- **2017–2019:** the Hoser missions and the 2019 pilgrimage authorization are
  **pastoral acts by their own texts** ("an exclusively pastoral character";
  "not… an authentication") — they carry `adjacent` status on the ladder, not
  approval.
- **19 September 2024:** the DDF Note "The Queen of Peace" grants a *nihil
  obstat* to the devotion — and states in the same paragraph that this "does
  not imply a declaration of the supernatural character of the phenomenon."
  Under the 2024 Norms (art. 23), such a declaration is, as a rule, never
  issued by anyone.
- **Person-acts are kept apart from the case.** The three Roman acts about
  Tomislav Vlašić (2008 CDF decree, 2009 laicization at his own request, 2020
  declaration of excommunication) judge a man's doctrine and conduct, not the
  apparitions, and get their own rung.

Key pre-1998 Church texts (Zadar, Bertone, the Žanić statements, the 1987
communiqué) have **no primary institutional hosting online** and are cited to
labeled document mirrors; the Diocese of Mostar-Duvno's own site was
unreachable from the authoring environment. The seers' biographical details
rest on devotional literature. Single-source and devotional-only dates are
flagged (`dateVerified: false`, rendered with a `?`), with a `dateNote` naming
the problem.

## How it works

`data/chronology.json` is the source of truth. A zero-dependency Node script
compiles it into static HTML (`docs/`, served by GitHub Pages) in English
(authoritative), Spanish and Portuguese; the es/pt strings live in
`data/i18n/` as committed dictionaries.

```
node scripts/validate-data.js   # schema + citation check
node build.js                   # regenerate docs/
node --test                     # invariants, i18n completeness, renderers
```

Every data change must pass all three and commit the regenerated `docs/`
together with the data. See `AGENTS.md` and `context.md` before editing.

## License and corrections

Content compiled from public sources, each cited in the site's References
section. Corrections against primary sources are welcome — open an issue.
