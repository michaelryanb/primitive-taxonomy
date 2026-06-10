# CATEGORY_05_EXECUTORS — Readme

This category contains execution primitives. Each primitive interfaces with the runtime environment — spawning subprocesses, loading libraries, creating threads, reading and writing memory, and operating on files.

These primitives bridge between the software layer and the operating system or hardware. They are the leaf-level building blocks for any pipeline that needs to execute external code, manage memory, or interact with the filesystem.

Every primitive in this category is defined using the schema in `../schema.json`. Each file is self-contained: a model receiving a single primitive file has all information needed to implement it without cross-referencing other primitives or categories.

## Primitives

| File | Summary |
|------|---------|
| `command-run.md` | Execute a system command in a subprocess |
| `library-load.md` | Load a shared library into process memory |
| `thread-spawn.md` | Create a new execution thread |
| `memory-read.md` | Read bytes from a memory address |
| `memory-write.md` | Write bytes to a memory address |
| `file-operate.md` | Read, write, or query a filesystem entry |
