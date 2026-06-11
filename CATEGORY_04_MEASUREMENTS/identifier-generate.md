```yaml
primitive_name: identifier-generate
category: CATEGORY_04_MEASUREMENTS
operation: Produce a unique label by combining an entropy source with a namespace context, yielding a string suitable as an
  identifier
signature_shape: S identifier_generate(S, B)
state_required: per-call
determinism: entropy-dependent
platform: stdlib
decomposable: true
decomposes_to:
- hash
- random-read
depends_on:
- hash
- random-read
isolation: none
ownership: caller
```
