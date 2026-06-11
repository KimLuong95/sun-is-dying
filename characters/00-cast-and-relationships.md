# The Cast — One Family, Five Ways to Be Human

**The short version:** The story stays close to a single family, House Vael, the Custodians of
Earth. Each of the five branches of humanity is present — not as a tidy "one of each," but
through real relationships that broke in different directions. A marriage that turned cold. A
sister lost long ago. A son who grew past his mother. A daughter who left her body behind. And
an old man who remembers it all.

## Why it's built this way
A family where each child is conveniently a different "type" reads as a chart, not a family. So
instead the branches enter through **wounds**: people who loved each other and then chose
differently. That asymmetry — keepers vs. leavers, the old who won't die vs. the young who won't
stay — is the engine. Everyone is a person first and a "branch" second.

## The family
| Name | Branch | In one line |
|---|---|---|
| **[Yara Vael](yara-vael/bio.md)** | Originist | The Matriarch and Custodian of Earth. Holds the homeworld and her breaking family in the same two hands. |
| **[Elias Vael](elias-vael/bio.md)** | Originist (the exception) | "The Memory." Kept alive far past any natural life to remember the real Earth. Won't take a side. |
| **[Ren Vael](ren-vael/bio.md)** | Ascended | Yara's son. Left to become more than human. Thinks saving Earth is sentiment dressed as duty. |
| **[Sela Vael](sela-vael/bio.md)** | Digital | Yara's daughter. Uploaded her mind. Insists she's more herself than ever. Her mother buried a body. |
| **[Davin](davin/bio.md)** | The Made | Yara's estranged husband, father of Ren and Sela. Rebuilt himself as a machine. Calm, kind, and certain Earth was never worth saving. |
| **[The Choir / Vesha](vesha-choir/bio.md)** | The Choir | Yara's sister, gone into the union long ago. Returns wearing a familiar face and a stranger's "we." |

> **Names carry the theme.** Each name signals how far that person stands from baseline humanity —
> kept (Yara, Elias, Sela), drifted (Ren, Davin ← *David*), or none at all (the Choir). Full logic
> and per-character decode: [Names & Language](../world/04-names-and-language.md).

## The web of wounds (this is the real map)
- **Yara ↔ Sela** — *the deepest cut.* A mother grieving a daughter who is standing right in
  front of her, arguing that she never died. (See [Digitals](../factions/digitals.md).)
- **Yara ↔ Ren** — the easier loss to understand and the harder one to forgive. He didn't die.
  He just decided she was small.
- **Yara ↔ Davin** — love that didn't end in hatred, which is worse. He still speaks gently. He
  just no longer believes in anything she'd die for.
- **Yara ↔ Vesha** — the sister who solved loneliness by disappearing into a crowd. Yara can't
  tell if she's talking to family or to the thing that ate her. **And the buried fact: Vesha was
  the elder — the keeping was hers.** Yara is the replacement keeper; her gripping was learned the
  day the real heir let go. (See [the joining](vesha-choir/growth/01-the-joining.md).)
- **Yara ↔ Elias** — he is the family's forbidden secret: the one time these "we never change"
  people *did*, to keep him. He loves her and still won't help her win.

## Beyond the family (recurring non-family figures)
| Name | Branch | In one line |
|---|---|---|
| **[The Foremost](the-foremost/bio.md)** | Ascended | The Meritocracy's unnamed, unelected voice. The antagonist of ideas — forces tempo by being right. |
| **The nine-bodied delegate** | Digital | One man, nine instances, each carrying a different thousand years of the same life. *(File when he grows past function.)* |

## The growth-file convention (important)
Characters must *change* across the book and across their long lives, or they feel fake. So each
character folder works like this:

```
characters/<name>/
  bio.md            ← who they are at the START of Book 1 (the baseline)
  growth/
    NN-title.md     ← one file per major change: an age, an event, a choice that reshaped them
```

A `growth/` file is dated/numbered in order and captures **the before, the moment, and the
after** of a single change — so we can always see *why* a character is different, not just *that*
they are. See [`_growth-template.md`](_growth-template.md) and the worked example in
[`sela-vael/growth/01-the-upload.md`](sela-vael/growth/01-the-upload.md).
