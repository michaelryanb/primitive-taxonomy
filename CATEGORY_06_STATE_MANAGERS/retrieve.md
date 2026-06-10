```yaml
primitive_name: "retrieve"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Fetch the value associated with a given key from the store, returning a null or error sentinel if the key is absent"
signature_shape: "V retrieve(K)"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["file-operate", "memory-read"]
depends_on: []
isolation: "none"
ownership: "callee"
```
