```yaml
primitive_name: "size-delta"
category: "CATEGORY_04_MEASUREMENTS"
operation: "Compute the difference in size between two byte sequences, expressed as an absolute count and an optional proportional ratio"
signature_shape: "N size_delta(B, B)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["ratio"]
depends_on: []
isolation: "none"
ownership: "caller"
```
