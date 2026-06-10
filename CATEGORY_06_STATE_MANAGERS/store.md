```yaml
primitive_name: "store"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Persist a value associated with a key in a durable or in-memory store, overwriting any existing value for that key"
signature_shape: "void store(K, V)"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["file-operate", "memory-write"]
depends_on: []
isolation: "none"
ownership: "callee"
```
