# Asma

Multilingual catalogs for names, meanings, and their relationships.

Asma is being developed to give catalog entries a stable identity across
languages, with localized names, labels, and aliases. The same relationships
can support multilingual application text and locale-aware discovery.

## Project status

Version `0.0.0` is an initial placeholder for an actively planned project. The
library has no public API or usable functionality yet and is not ready for
application use.

## Planned capabilities

- PostgreSQL-backed catalog preparation and validation.
- Localized labels, aliases, and semantic relationships.
- Versioned snapshots and exports for application builds and runtime readers.
- Bundled default languages and optional language packages loaded on demand.
- In-memory lookup without requiring every consumer to access the database.
- Background enrichment and optional semantic search support.

## License

MIT OR Apache-2.0, at your option.
