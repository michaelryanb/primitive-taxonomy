```yaml
primitive_name: "purge"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Remove all key-value pairs from the store, resetting it to an empty state"
signature_shape: "void purge()"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["list", "delete"]
depends_on: ["list", "delete"]
isolation: "none"
ownership: "callee"
```
