# plonky2-sha256

This repository contains [SNARK](https://en.wikipedia.org/wiki/Non-interactive_zero-knowledge_proof) circuits of a
cryptographic hash function [SHA-256](https://en.wikipedia.org/wiki/SHA-2) implemented
with [Plonky2](https://github.com/mir-protocol/plonky2).

Run benchmarks

```console
RUSTFLAGS=-Ctarget-cpu=native cargo run --release --package plonky2_sha256 --bin plonky2_sha256
```

Benchmark on a Macbook Pro (M1), preimage message size = 128 (block count = 2)

```console

```
