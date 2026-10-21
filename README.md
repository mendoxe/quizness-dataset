# Quizness datasets

Question sets for the Quizness app, built from official exam question banks. Each set's description names its
official source.

- `catalogue.json`: the sets of the newest release, each with its language, version, question count and its
  archive's address, size and SHA-256. `catalogue-revision.json` holds the catalogue's revision.
- Releases (`catalogue-<revision>`): one archive per set version, a gzipped tar of the set file and its media, plus
  the catalogue. The app reads the catalogue from the newest release.
