# Destiny Voyager — Documentation Samples

An architecture overview I wrote for **Destiny Voyager**, my personal Destiny 2 optimizer and clan Discord assistant, published as a work sample.

The toolkit core is open source (MIT) at [destiny-voyager](https://github.com/clarencestephen/destiny-voyager). This repo holds the writing — a block-diagram-altitude tour of the fuller system.

## What's in here

| Document | Length | What it is |
|---|---|---|
| `Destiny_Voyager_Architecture_Overview.docx` | ~5 pages, 1 diagram, 3 tables | Architecture overview of the full system: the install wizard and nine-sheet loadout workbook, Bungie ingestion and DIM interop, the retrieval-grounded Discord assistant running a local model, the web companion, and the operations layer. Covers the component boundaries, the four core pipelines, and the design decisions behind them — a local-first model, inventory grounding, and a state record that keeps the assistant honest against a game that changes every week. |

## Provenance

- **Authored by me.** Destiny Voyager is my own project; the design, the code, and the writing are mine.
- **No PII.** No clan-member data, credentials, or live operational metrics appear in the document.
- **Altitude.** The service-layer internals, the data model, the assistant's prompt, and the scraped knowledge corpus are intentionally omitted.

## License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt the material for non-commercial purposes with attribution. For commercial use, please reach out.

## Author

Clarence Stephen — [github.com/clarencestephen](https://github.com/clarencestephen)

> Destiny 2 is a trademark of Bungie, Inc. This project is not affiliated with or endorsed by Bungie.
