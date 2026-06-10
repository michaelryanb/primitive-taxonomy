```yaml
primitive_name: "library-load"
category: "CATEGORY_05_EXECUTORS"
operation: "Load a shared library from a filesystem path into the calling process address space and resolve its exported symbols"
signature_shape: "H library_load(S)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["file-operate", "memory-write"]
depends_on: []
isolation: "none"
ownership: "caller"
```
