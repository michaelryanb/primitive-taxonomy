# CATEGORY_03_TRANSFORMS — Readme

This category contains data transformation primitives. Each primitive converts data between representations — encoding, compression, encryption, validation, and filtering.

These primitives accept data as input and produce transformed data as output. They are the leaf-level building blocks for any pipeline that reshapes, validates, or protects information in transit or at rest.

Every primitive in this category is defined using the schema in `../schema.json`. Each file is self-contained: a model receiving a single primitive file has all information needed to implement it without cross-referencing other primitives or categories.

## Primitives

| File | Summary |
|------|---------|
| `encoding-convert.md` | Convert between character encodings |
| `compress.md` | Reduce data size via compression |
| `decompress.md` | Restore compressed data |
| `encrypt.md` | Plaintext to ciphertext transformation |
| `decrypt.md` | Ciphertext to plaintext transformation |
| `validate.md` | Schema and constraint validation |
| `filter.md` | Predicate-based element selection |
