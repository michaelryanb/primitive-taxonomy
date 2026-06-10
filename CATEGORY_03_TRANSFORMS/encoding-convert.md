```yaml
primitive_name: "encoding-convert"
category: "CATEGORY_03_TRANSFORMS"
operation: "Convert a byte sequence from one character encoding scheme to another, producing an equivalent byte sequence in the target encoding"
signature_shape: "B encoding_convert(B, E, E)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["memory-read", "memory-write", "validate"]
depends_on: []
isolation: "none"
ownership: "caller"
```
