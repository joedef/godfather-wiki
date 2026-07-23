# Contributing

Thanks for helping. This is a hobby wiki about a 55-year-old novel and the films made from it — the bar for participation is low, but the bar for accuracy is high.

## The one hard rule

**Do not paste in copyrighted text.** No screenplay pages, no passages from Puzo or Winegardner or Falco, no wholesale copying of another wiki's or website's article. Quote briefly for commentary — a line of dialogue, a sentence from a review — and attribute it. Everything else must be written in your own words.

This protects the project and keeps the CC BY-SA license honest.

## How to make a change

1. Fork the repo and create a branch.
2. Edit the Markdown in `docs/`. Every page also has an ✏️ edit link at the top right of the live site that takes you straight to the right file on GitHub.
3. Run `mkdocs build --strict` if you can — it catches broken internal links, which are the most common breakage.
4. Open a pull request describing what you changed and, for facts, where the figure came from.

Typo fixes and one-line corrections don't need a local build. Just edit and open the PR.

## House style

**Voice.** Plain, specific, unhurried. Write like a well-read friend explaining something they love, not like an encyclopedia and not like a review. Avoid superlatives that do no work ("masterpiece," "iconic," "legendary") — show why instead.

**Facts vs. readings.** State facts flatly. Frame interpretation as interpretation: *"Coppola has said…"*, *"the most common reading is…"*, *"one way to take the final shot is…"*. Where critics disagree, say so and name them. Do not launder an opinion as a fact.

**Numbers.** Give the figure, the unit, and the source. Box office numbers in particular vary wildly between sources and between original-run and re-release totals — say which you mean. Prefer "$250–291 million across its original release and reissues" over a fake-precise single number.

**Dates.** Real-world dates get years (`March 14, 1972`). In-universe dates get the film's own framing (`the summer of 1945`). Never mix the two in one sentence without labeling which is which.

**Continuity labels.** When something is true in one version and not another, say which: *novel*, *1972 film*, *Part II*, *Coda*, *Winegardner*, *game*. The [Continuity](docs/continuity.md) page explains the tiers this wiki uses.

**Spoilers.** There are none. This is a reference work for a 1972 film; pages assume you've seen it or don't mind. Don't add spoiler warnings.

## Page conventions

**Infobox.** Film, book, character, and person pages open with a fact panel:

```html
<div class="infobox" markdown>
#### At a glance
Released
:   March 24, 1972

Runtime
:   175 min
</div>
```

**Epigraph.** Major pages may open with one quotation:

```html
<p class="epigraph">Never tell anybody outside the family what you're thinking again.
<cite>Vito Corleone — The Godfather (1972)</cite></p>
```

**Charts.** Bar charts are plain HTML/CSS — no libraries, no external requests. Copy the pattern in [`docs/data/charts.md`](docs/data/charts.md) and set the width percentage yourself.

**Links.** Use relative Markdown links between pages (`[Michael](../characters/michael-corleone.md)`). `--strict` will fail the build if one is broken, which is the point.

## Sourcing

Add anything you lean on to [`docs/reference/sources.md`](docs/reference/sources.md). Preferred sources, roughly in order:

1. Primary — the films themselves, the novels, Coppola's notebook, the DVD/Blu-ray commentaries, contemporaneous interviews
2. Documented secondary — Peter Cowie's *The Godfather Book*, Mark Seal's *Leave the Gun, Take the Cannoli*, Harlan Lebo's *The Godfather Legacy*, published critics
3. Reference aggregators — Wikipedia, Box Office Mojo, the Academy database, AFI

Anecdotes about this production are *unusually* unreliable — the mob-interference stories in particular have been retold, embellished, and contradicted by the participants for fifty years. When a story is disputed, write it as disputed and name who claims what.

## Scope

In scope: the novel, all four film versions, the sequel/prequel novels, the recuts and restorations, the deleted scenes, *The Sicilian*, *The Offer*, the video games, the real-world Mafia history the fiction draws on, and the cultural legacy.

Out of scope: unmarked speculation, fan fiction, real-organized-crime coverage that isn't tied to the fiction, and anything about living people that isn't documented and relevant.

## Code of conduct

Be decent. Disagree about the ending of *Part III* as much as you like; do it without being unpleasant to a person.
