# cyc.terpedia.com

Terpedia's independently deployed, source-linked biochemical encyclopedia. Its index and entry pages are read directly from the Terpedia knowledge graph.

## Architecture

`GET /v1/cyc` on the Terpedia knowledge service returns the entity index used for search and cross-link parsing. `GET /v1/cyc/:keyword` resolves an entry and returns its verified relationships and provenance.

The static site in `docs/` is deployed to GitHub Pages at `https://cyc.terpedia.com`.
