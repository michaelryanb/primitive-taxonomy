# Primitive Taxonomy — Master Index

A reference catalog of leaf-function primitives for systems engineering. Each primitive is an atomic, independently implementable unit of software capability. This document is the master index; each primitive is fully specified in its own file within the category directory.

## Categories

### CATEGORY_03_TRANSFORMS
Data transformation primitives — convert data between representations.

| Primitive | Operation |
|-----------|-----------|
| `encoding-convert` | Convert a byte sequence from one character encoding to another |
| `compress` | Reduce the size of a byte sequence using a compression algorithm |
| `decompress` | Restore a compressed byte sequence to its original form |
| `encrypt` | Transform plaintext to ciphertext using a key and cipher |
| `decrypt` | Transform ciphertext back to plaintext using a key and cipher |
| `validate` | Check a data element against structural or constraint rules |
| `filter` | Select elements from a collection that satisfy a predicate |

### CATEGORY_04_MEASUREMENTS
Measurement and computation primitives — derive properties from data.

| Primitive | Operation |
|-----------|-----------|
| `hash` | Compute a fixed-size digest from arbitrary input data |
| `time-delta` | Measure the elapsed interval between two temporal points |
| `size-delta` | Compute the difference in size between two data states |
| `entropy` | Estimate the information density or randomness of a byte sequence |
| `ratio` | Compute the proportional relationship between two numeric values |
| `identifier-generate` | Produce a unique label from entropy and context inputs |

### CATEGORY_05_EXECUTORS
Execution primitives — interface with the runtime environment.

| Primitive | Operation |
|-----------|-----------|
| `command-run` | Execute an external system command or subprocess |
| `library-load` | Load a shared library into the calling process address space |
| `thread-spawn` | Create a new thread of execution within the calling process |
| `memory-read` | Read a sequence of bytes from a memory address |
| `memory-write` | Write a sequence of bytes to a memory address |
| `file-operate` | Perform read, write, or metadata operations on a filesystem entry |

### CATEGORY_06_STATE_MANAGERS
State management primitives — persist, retrieve, and manage keyed data.

| Primitive | Operation |
|-----------|-----------|
| `store` | Persist a value associated with a key |
| `retrieve` | Fetch a value by its key |
| `delete` | Remove a key and its associated value |
| `list` | Enumerate all currently stored keys |
| `purge` | Remove all stored key-value pairs |
| `expire` | Remove or mark entries that have exceeded a time-to-live threshold |

## Using This Taxonomy

Each primitive is defined in its own `.md` file using the schema in `schema.json`. The file format is YAML frontmatter with the following required fields: `primitive_name`, `category`, `operation`, `signature_shape`, `state_required`, `determinism`, `platform`, `decomposable`, `isolation`, `ownership`. Optional fields include `decomposes_to` and `depends_on`.

Primitives are intended to be independently implementable — a model receiving a single primitive file should have all information needed to build it without cross-referencing other primitives.
