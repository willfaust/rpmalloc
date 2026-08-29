# Licensing of Madeira's modifications to rpmalloc

This repository is a fork of [rpmalloc](https://github.com/FEX-Emu/rpmalloc),
itself a fork of Mattias Jansson's rpmalloc. **The upstream licence is
unchanged and continues to apply to all upstream code.** See `LICENSE` (0BSD /
public-domain-equivalent).

## What is licensed how

| Code | Licence |
|---|---|
| Original rpmalloc, and all upstream FEX-Emu changes | as in `LICENSE` (0BSD) — unchanged |
| Commits authored by **Ryan Houdek** on the `ios-mythic` branch | as in `LICENSE` (0BSD) — **not** relicensed |
| Commits authored by **Will Faust** from 2026 onward, on `ios-mythic` and later branches | **GPL-3.0-or-later** |

`git log --format='%an'` distinguishes them. Where a single file contains both,
the file as a whole may only be distributed under terms compatible with
GPL-3.0-or-later, because the GPL-covered contributions cannot be separated
from it. The underlying upstream code remains available under 0BSD **from
upstream**, and nothing here withdraws that.

## Why

The intent is that derivatives of this work which are *distributed* remain open
source. A permissive licence allows a proprietary derivative; the GPL does not.

Two limits are worth stating honestly rather than leaving implied:

- The GPL constrains **distribution**, not private modification or use.
- Changes published earlier under a permissive licence were granted under it,
  and that grant cannot be revoked. Only the contributions covered above are
  GPL-only.

## Contributing

Contributions are accepted under **GPL-3.0-or-later**. See `CONTRIBUTING.md`.
