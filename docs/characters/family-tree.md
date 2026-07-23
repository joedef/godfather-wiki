---
description: "The Corleone family tree across four generations, plus the organizational chart and the Five Families of New York."
---

# The Family Tree

The Corleone family across four generations, plus the organization that surrounds it.

---

## The bloodline

```mermaid
graph TD
    ANDOLINI["Antonio Andolini<br/><i>d. 1901, Corleone</i>"] --> VITO
    ANDOLINI --> PAOLO["Paolo Andolini<br/><i>d. 1901</i>"]
    SIGNORA["Signora Andolini<br/><i>d. 1901</i>"] --- ANDOLINI

    VITO["<b>Vito Corleone</b><br/>b. Vito Andolini, 1891<br/><i>d. 1955</i>"] --- CARMELA["Carmela Corleone<br/><i>d. 1959</i>"]

    VITO --> SONNY["<b>Sonny</b><br/>1917–1948"]
    VITO --> FREDO["<b>Fredo</b><br/>1919–1959"]
    VITO --> MICHAEL["<b>Michael</b><br/>1920–1997"]
    VITO --> CONNIE["<b>Connie</b><br/>b. 1927"]
    VITO -.adopted.-> TOM["<b>Tom Hagen</b><br/>d. before 1979"]

    SONNY --- SANDRA["Sandra Corleone"]
    SONNY -.affair.- LUCY["Lucy Mancini"]
    SANDRA --> FRANCESCA["Francesca &<br/>Kathryn (twins)"]
    SANDRA --> SONNYJR["Santino Jr.<br/>+ 1 more"]
    LUCY --> VINCENT["<b>Vincent Mancini</b><br/>b. 1948"]

    MICHAEL --- APOLLONIA["Apollonia Vitelli<br/><i>m. 1949, d. 1949</i>"]
    MICHAEL --- KAY["<b>Kay Adams</b><br/><i>m. 1951, div. 1959</i>"]
    KAY --> ANTHONY["Anthony<br/>b. 1955"]
    KAY --> MARY["<b>Mary</b><br/>1958–1980"]

    CONNIE --- CARLO["Carlo Rizzi<br/><i>d. 1955</i>"]
    CARLO --> MICHAELJR["Michael Francis Rizzi<br/><i>baptized 1955</i>"]
    CARLO --> VICTOR["Victor Rizzi"]

    VINCENT -.affair.- MARY

    style VITO fill:#c8992e,stroke:#7d1d1d,color:#1a1714
    style MICHAEL fill:#c8992e,stroke:#7d1d1d,color:#1a1714
    style FREDO fill:#e8e0d2,stroke:#7d1d1d,color:#1a1714
    style SONNY fill:#e8e0d2,stroke:#7d1d1d,color:#1a1714
    style MARY fill:#e8e0d2,stroke:#7d1d1d,color:#1a1714
```

*Dates are approximate and reconstructed from the films; the novel and the continuation novels sometimes disagree. See [Timeline](../data/timeline.md).*

---

## Reading it

**The solid lines** are blood or marriage. **The dotted line to Tom Hagen** is the whole point of Tom Hagen: he is raised as a son, functions as the most trusted man in the organization, and is never once considered for the succession, because he isn't Sicilian.

**The dotted line between Vincent and Mary** is *Part III*'s most uncomfortable thread — first cousins, and the affair Michael ends as the price of handing over the family.

**Vito's own line ends at nine years old.** Everything above him on the tree was killed in the space of a week in 1901, and the surname he carries is a clerical error made at Ellis Island by a man writing down the name of a town.

---

## The succession

| Don | Period | How it ended |
| --- | --- | --- |
| [Vito Corleone](vito-corleone.md) | 1920s–1945 | Shot; survived; semi-retired |
| [Sonny Corleone](sonny-corleone.md) | 1945–1948 *(acting)* | Murdered at a tollbooth |
| Vito Corleone | 1948–1955 | Retired to the garden; died there |
| [Michael Corleone](michael-corleone.md) | 1955–1980 | Abdicated after Mary's death |
| [Vincent Corleone](vincent-mancini.md) | 1980– | *(Unrecorded — no fourth film)* |

Note what the table hides: Michael is Don for twenty-five years, and the films show us four of them.

---

## The organization

```mermaid
graph TD
    DON["<b>The Don</b><br/>Vito → Sonny → Vito → Michael → Vincent"]
    CONS["<b>Consigliere</b><br/>Genco Abbandando → Tom Hagen<br/><i>(Part III: Connie, informally)</i>"]
    UNDER["<b>Underboss</b><br/>Sonny → Fredo → Al Neri"]

    DON --- CONS
    DON --> UNDER

    UNDER --> CAP1["<b>Clemenza</b><br/>Bronx / Long Island<br/><i>→ Frank Pentangeli</i>"]
    UNDER --> CAP2["<b>Tessio</b><br/>Brooklyn<br/><i>d. 1955</i>"]
    UNDER --> CAP3["<b>Rocco Lampone</b><br/>Nevada<br/><i>d. 1959</i>"]

    CAP1 --> S1["Paulie Gatto †<br/>Willi Cicci<br/>Rosato brothers"]
    CAP2 --> S2["Brooklyn crew"]
    CAP3 --> S3["Al Neri<br/>Nevada crew"]

    DON -.enforcer.-> LUCA["<b>Luca Brasi</b><br/><i>d. 1945</i>"]

    style DON fill:#c8992e,stroke:#7d1d1d,color:#1a1714
```

**Consigliere** is the counselor — not in the chain of command, reports only to the Don. **Underboss** is second in command. **Caporegime** ("capo") runs a crew of soldiers in a territory. Terms are defined on the [Glossary](../reference/glossary.md).

---

## The Five Families of New York

| Family | Boss | Territory / business | Fate |
| --- | --- | --- | --- |
| **Corleone** | Vito → Michael | Olive oil, gambling, unions, politicians | Moves to Nevada, 1955 |
| **Tattaglia** | Philip Tattaglia | Prostitution, narcotics | Boss killed 1955 |
| **Barzini** | [Emilio Barzini](barzini-and-the-five-families.md) | The most powerful; backed Sollozzo | Boss killed 1955 |
| **Cuneo** | Carmine Cuneo | Milk / trucking, upstate | Boss killed 1955 |
| **Stracci** | Victor Stracci | New Jersey, gambling | Boss killed 1955 |

Plus the out-of-town powers: **Hyman Roth** (Miami/Havana), **Moe Greene** (Las Vegas), the **Rosato brothers** (Bronx, under Roth), and in *Part III* **Joey Zasa** and **Don Altobello**.

Full detail: [Barzini & the Five Families](barzini-and-the-five-families.md).

---

## The continuation novels

Winegardner and Falco add relatives the films don't:

- **Francesca Corleone** — Sonny's daughter, a major viewpoint character in [*The Godfather Returns*](../books/the-godfather-returns-2004.md)
- **Sandra Corleone** — Sonny's widow, given far more presence
- **Nick Geraci** — not family, but the most consequential invented character in the sequence
- A child of Fredo's, revealed in the last pages of [*The Godfather's Revenge*](../books/the-godfathers-revenge-2006.md)

None of these appear in any film. See [Continuity](../continuity.md#tier-4-the-continuation-novels).

---

## See also

- [Character index](index.md) · [Timeline](../data/timeline.md) · [Body Count](../data/body-count.md)
- [Glossary](../reference/glossary.md) — what a consigliere actually does
