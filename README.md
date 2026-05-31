# Destiny Voyager — Documentation Samples

Documentation I wrote for **Destiny Voyager**, my personal Destiny 2 optimizer and clan Discord assistant, published as work samples.

The toolkit core is open source (MIT) at [destiny-voyager](https://github.com/clarencestephen/destiny-voyager). This repo holds the writing — a block-diagram-altitude tour of the fuller system.

## What's in here

| Document | Length | What it is |
|---|---|---|
| `Destiny_Voyager_Architecture_Overview.docx` | ~5 pages, 1 diagram, 3 tables | Architecture overview of the full system: the install wizard and nine-sheet loadout workbook, Bungie ingestion and DIM interop, the retrieval-grounded Discord assistant running a local model, the web companion, and the operations layer. Covers the component boundaries, the four core pipelines, and the design decisions behind them — a local-first model, inventory grounding, and a state record that keeps the assistant honest against a game that changes every week. |
| `Darth_Bot_Model_Card.docx` | ~6 pages, 1 diagram, 4 tables | Model card for Darth Bot, the retrieval-grounded Discord assistant, following the Mitchell et al. (2019) framework: model details, intended and out-of-scope use, performance factors, the RAG pipeline, data sources, evaluation methodology, the anti-drift grounding mechanism, limitations, privacy, and a decision memo. Architecture and methodology are real; quantitative results are illustrative, disclosed in the document's reviewer note. |

## Provenance

- **Authored by me.** Destiny Voyager is my own project; the design, the code, and the writing are mine.
- **No PII.** No clan-member data, credentials, or live operational metrics appear in the document.
- **Altitude.** The service-layer internals, the data model, the assistant's prompt, and the scraped knowledge corpus are intentionally omitted.

## License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). You are free to share and adapt the material for non-commercial purposes with attribution. For commercial use, please reach out.

## Author

Clarence Stephen — [github.com/clarencestephen](https://github.com/clarencestephen)

> Destiny 2 is a trademark of Bungie, Inc. This project is not affiliated with or endorsed by Bungie.
