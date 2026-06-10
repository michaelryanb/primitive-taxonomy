```yaml
primitive_name: "delete"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Remove a key and its associated value from the store, silently succeeding if the key does not exist"
signature_shape: "void delete(K)"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["file-operate"]
depends_on: []
isolation: "none"
ownership: "callee"
```
