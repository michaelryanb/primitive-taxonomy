```yaml
primitive_name: "expire"
category: "CATEGORY_06_STATE_MANAGERS"
operation: "Remove entries from the store whose time-to-live marker exceeds a specified age threshold, using a timestamp comparison"
signature_shape: "void expire(N)"
state_required: "persistent"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["list", "delete", "time-delta"]
depends_on: ["list", "delete", "time-delta"]
isolation: "none"
ownership: "callee"
```