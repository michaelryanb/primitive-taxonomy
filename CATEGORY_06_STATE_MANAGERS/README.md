# CATEGORY_06_STATE_MANAGERS — Readme

This category contains state management primitives. Each primitive persists, retrieves, or removes keyed data — storing values, fetching by key, deleting entries, listing keys, purging all state, and expiring time-bound entries.

These primitives manage the lifecycle of named data. They are the leaf-level building blocks for any pipeline that needs to maintain state across calls, sessions, or processes.

Every primitive in this category is defined using the schema in `../schema.json`. Each file is self-contained: a model receiving a single primitive file has all information needed to implement it without cross-referencing other primitives or categories.

## Primitives

| File | Summary |
|------|---------|
| `store.md` | Persist a value by key |
| `retrieve.md` | Fetch a value by key |
| `delete.md` | Remove a key-value pair |
| `list.md` | Enumerate all stored keys |
| `purge.md` | Remove all entries |
| `expire.md` | Remove entries past a time threshold |
