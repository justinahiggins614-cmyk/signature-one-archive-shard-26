# signature-one-archive-shard-26

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c03268.jsonl.gz` … `specs-c03377.jsonl.gz`
  (JAH-SPEC-490051 … JAH-SPEC-506550 — 16500 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry (lazy-loaded on demand).
- FROZEN: never write new chunks here; new drip chunks always land in the main repo.
