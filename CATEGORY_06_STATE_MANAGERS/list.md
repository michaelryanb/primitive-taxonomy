```yaml
primitive_name: "list"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Enumerate all keys currently present in the store, returning them as an iterable collection"
signature_shape: "C list()"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["file-operate"]
depends_on: []
isolation: "none"
ownership: "callee"
```
