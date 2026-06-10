```yaml
primitive_name: "validate"
category: "CATEGORY_03_TRANSFORMS"
operation: "Check a data element against a set of structural rules or constraints, returning a pass or fail result with optional failure details"
signature_shape: "R validate(T, C)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["filter"]
depends_on: []
isolation: "none"
ownership: "caller"
```
