# CATEGORY_04_MEASUREMENTS — Readme

This category contains measurement and computational primitives. Each primitive derives a property or metric from input data — hashing, timing, sizing, entropy estimation, ratio computation, and identifier generation.

These primitives produce scalar or digest outputs from arbitrary inputs. They are the leaf-level building blocks for any pipeline that needs to quantify, compare, or label data.

Every primitive in this category is defined using the schema in `../schema.json`. Each file is self-contained: a model receiving a single primitive file has all information needed to implement it without cross-referencing other primitives or categories.

## Primitives

| File | Summary |
|------|---------|
| `hash.md` | Fixed-size digest from arbitrary input |
| `time-delta.md` | Elapsed interval between temporal points |
| `size-delta.md` | Size difference between data states |
| `entropy.md` | Information density estimation |
| `ratio.md` | Proportional relationship between values |
| `identifier-generate.md` | Unique label generation |
