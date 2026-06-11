```yaml
primitive_name: thread-spawn
category: CATEGORY_05_EXECUTORS
operation: Create a new thread of execution within the calling process to run a given function concurrently
signature_shape: H thread_spawn(F)
state_required: per-call
determinism: entropy-dependent
platform: stdlib
decomposable: false
decomposes_to: []
depends_on: []
isolation: thread
ownership: caller
```
