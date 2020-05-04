## Wasmtime Embedding API

_This is a fork, patching some thread-safety into this crate. It is deprecated and
only exists until [#888](https://github.com/bytecodealliance/wasmtime/issues/888) is fixed._

The `wasmtime` crate is an embedding API of the `wasmtime` WebAssembly runtime.
This is intended to be used in Rust projects and provides a high-level API of
working with WebAssembly modules.

If you're interested in embedding `wasmtime` in other languages, you may wish to
take a look a the [C embedding API](../c-api) instead!
