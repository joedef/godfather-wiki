# The Godfather Wiki

An open-source, wiki-style reference and critical analysis of **The Godfather** — Mario Puzo's 1969 novel, Francis Ford Coppola's film trilogy, the sequel and prequel novels, the screen spinoffs, the video games, and the people who made all of it.

**📖 Read it: <https://joedef.github.io/godfather-wiki/>**

> *"I believe in America."*
> — the first four words of the film

---

## What's in here

| Section | What it covers |
| --- | --- |
| **Films** | Full production histories, plot breakdowns, and reception for *The Godfather* (1972), *Part II* (1974), *Part III* (1990), and *Coda* (2020) — plus every recut, the restorations, the deleted scenes, *The Sicilian* (1987), *The Offer* (2022), and the Part IV that never happened |
| **Books** | Puzo's novel and *The Sicilian*, Mark Winegardner's two continuations, Ed Falco's prequel, and Coppola's legendary production notebook |
| **Characters** | 20+ character pages with arcs, on-screen fates, book/film differences, and real-world models |
| **People** | Cast and crew biographies — Coppola, Puzo, Brando, Pacino, Caan, Duvall, Keaton, Cazale, De Niro, García, Willis, Rota, Evans, Ruddy, and the department heads |
| **Analysis** | Themes, Michael's arc, the parallel-editing structure, the baptism sequence, cinematography, score, editing, design, Catholicism, the women, Sicily, visual motifs, book-vs-film, and a reassessment of *Part III* |
| **Data** | A 1901–1997 timeline, complete awards tables, box office figures, an annotated body count, a sourced quote index, and charts |
| **Reference** | Filming locations, a Sicilian/mob glossary, real-world Mafia parallels, legacy and influence, the EA games, and a full source list |

## Running it locally

```bash
pip install -r requirements.txt
mkdocs serve          # live-reload at http://127.0.0.1:8000
mkdocs build --strict # what CI runs
```

Deployment is automatic: pushing to `main` triggers `.github/workflows/deploy.yml`, which builds the site and publishes it to GitHub Pages.

## Contributing

Contributions are very welcome — corrections especially. Everything is plain Markdown in `docs/`; there's no build step to learn and no JavaScript to write. See **[CONTRIBUTING.md](CONTRIBUTING.md)** for the house style, the sourcing rules, and the one hard rule about copyrighted text.

Good first contributions:

- Fix a factual error and cite where the correct figure comes from
- Fill out a thin character page
- Add a filming location with its present-day status
- Add a documented critical reading to an analysis page

## Licensing

- **Prose, tables, and other content** — [CC BY-SA 4.0](LICENSE-CONTENT.md). Reuse it, remix it, keep the attribution, share alike.
- **Configuration, CSS, and workflow code** — [MIT](LICENSE).

Some factual material (dates, grosses, credits, award records) was verified against Wikipedia, which is itself CC BY-SA — see [Sources](docs/reference/sources.md) for the full list. All analytical prose here is original to this project.

## Disclaimer

This is an independent fan project. It is **not affiliated with, authorized by, or endorsed by** Paramount Pictures, the estate of Mario Puzo, Francis Ford Coppola, or any rights holder. *The Godfather* and related marks belong to their respective owners. No screenplay text, novel text, or copyrighted imagery is reproduced here beyond brief quotation for commentary and criticism. The site carries affiliate links and accepts contributions to cover costs — see [Support the Project](https://joedef.github.io/godfather-wiki/support/).
