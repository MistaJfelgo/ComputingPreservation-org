# ComputingPreservation.org

Static HTML/CSS site for the Computing Preservation collection.

## Structure

- `index.html` — landing page
- `collection.html` — complete system catalog
- `ibm-clones.html` — PCs and compatibles (legacy filename retained)
- `portable-computers.html` — portable and luggable systems
- `commodore.html` — Commodore 8-bit collection
- `amiga.html` — Amiga collection
- `systems/` — individual machine records
- `style.css` — shared navy/orange visual system

The site has no JavaScript or external dependencies. All paths are relative, so it works at a domain root, in a subdirectory, or directly from a local filesystem.

## Adding a system

1. Copy an existing file from `systems/`.
2. Update the title, catalog fields, description, and preservation notes.
3. Add the system to `collection.html` and the appropriate category page.

The machine illustration is CSS-based and intentionally acts as a clean placeholder until collection photography is added.
