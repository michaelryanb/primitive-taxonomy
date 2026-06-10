```yaml
primitive_name: "encrypt"
category: "CATEGORY_03_TRANSFORMS"
operation: "Transform a plaintext byte sequence into a ciphertext byte sequence using a symmetric or asymmetric key and a specified cipher"
signature_shape: "B encrypt(B, K, A)"
state_required: "per-call"
determinism: "entropy-dependent"
platform: "stdlib"
decomposable: false
depends_on: []
isolation: "none"
ownership: "caller"
```
