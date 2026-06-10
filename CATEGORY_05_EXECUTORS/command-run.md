```yaml
primitive_name: "command-run"
category: "CATEGORY_05_EXECUTORS"
operation: "Execute an external system command in a subprocess, capture its exit code, standard output, and standard error streams"
signature_shape: "R command_run(S, C)"
state_required: "per-call"
determinism: "deterministic"
platform: "stdlib"
decomposable: true
decomposes_to: ["memory-read", "memory-write", "file-operate"]
depends_on: []
isolation: "process"
ownership: "caller"
```
