# Brand

OneLineage shares the [OneOrigin suite](oneorigin/README.md) brand with the other four tools. Its text, rules and values live in one place, OnePhylogeny's [`docs/oneorigin/`](https://github.com/ExtantApe/OnePhylogeny/tree/main/docs/oneorigin), and this folder carries a locked copy:

- [oneorigin/brand.md](oneorigin/brand.md): colors, marks and app icons.
- [oneorigin/guidelines.md](oneorigin/guidelines.md): the suite guidelines, including how to use the marks.
- [oneorigin/marks/](oneorigin/marks/): OneLineage's mark is `onelineage-light.svg`, `onelineage-dark.svg` and `onelineage-small.svg`.

Don't edit `oneorigin/` here. Change it in OnePhylogeny, then copy it again with `node scripts/oneorigin.mjs lock --source <OnePhylogeny checkout> --copy`. `oneorigin.lock` records the source commit and a checksum of every file, and CI runs `node scripts/oneorigin.mjs check`, which fails on a hand edit.

OneLineage has no app icon yet.
