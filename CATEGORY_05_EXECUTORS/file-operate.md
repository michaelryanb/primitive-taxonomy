```yaml
primitive_name: file-operate
category: CATEGORY_05_EXECUTORS
operation: Perform content read or write operations on an entry in the filesystem addressed by path
signature_shape: R file_operate(S, O, B)
state_required: per-call
determinism: deterministic
platform: stdlib
decomposable: true
decomposes_to:
- memory-read
- memory-write
depends_on: []
isolation: none
ownership: caller
```
