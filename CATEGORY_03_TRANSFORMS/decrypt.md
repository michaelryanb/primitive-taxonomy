```yaml
primitive_name: "decrypt"
category: "CATEGORY_03_TRANSFORMS"
operation: "Transform a ciphertext byte sequence back into its original plaintext form using the corresponding key and cipher"
signature_shape: "B decrypt(B, K, A)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: false
depends_on: []
isolation: "none"
ownership: "caller"
```
