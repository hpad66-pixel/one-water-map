# One Water - The Containment Map

The single page that shows how the entire One Water body of work is contained:
the shipyard (hardeep-soul, master of record), the reading edition (the-steersman-book),
the spine (one-water-knowledge-graph), the pictures with their one home and four
appearances, and the versioning loop that seals every change.

## Bring it up

- Open `index.html` in any browser, or
- Publish once, bookmark forever:

      gh repo create one-water-map --public --source=. --remote=origin --push
      gh api -X POST repos/hpad66-pixel/one-water-map/pages -f "source[branch]=main" -f "source[path]=/"

  Then it lives at: https://hpad66-pixel.github.io/one-water-map/

## Rule of the map

This page is authored in hardeep-soul/docs/one-water-containment-map.html and copied here.
When the structure changes (a new repo, a new edition), the shipyard copy is updated first,
then re-copied down and committed. This repo only ever receives copies.
