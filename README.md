# One Thumb Pirate — Illustration Hosting

Public image host for *The One Thumb Pirate* generated illustrations,
existing solely so Canva's `upload-asset-from-url` can pull them in
(`scottswoodcrafts/Books-Authored`, the main project repo, is private —
see that repo's `one-thumb-pirate/docs/ART_AUTOMATION_PLAN.md` for the
full context on why this repo exists).

## Contents

`pages/page-NN.png` — generated interior illustrations, one per story
page (5-30), produced by `Books-Authored`'s
`one-thumb-pirate/scripts/generate_batch.py` via the
`generate-illustration-batch.yml` workflow. Filenames match the page
numbers in `Books-Authored`'s `manuscript.md`.

## Usage

Raw URL for any page:

```
https://raw.githubusercontent.com/scottswoodcrafts/one-thumb-pirate-art/main/pages/page-05.png
```

Only commit approved images here — this repo is public, so anything
pushed is visible before the book launches.
