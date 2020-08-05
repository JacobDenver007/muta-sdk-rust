# Examples

To run these examples, we should build sdk at first.
Recommend running these examples with VSCode,
they can auto-complete for you when you try your example code.

## Requirement

- [Muta example-chain](https://github.com/mkxbl/muta.git)

> This sdk relies on https://github.com/mkxbl/muta.git rev a18ad1e, not master branch, please notice that.

## Start A muta-example Chain

```
git clone https://github.com/mkxbl/muta.git
cd muta
git checkout a18ad1e
cargo build --release --example muta-chain
./target/release/examples/muta-chain
```

## Build The SDK

```
git clone https://github.com/nervosnetwork/muta-sdk-rust
cd muta-sdk-rust
cargo build
```

## Run The Example

```
cargo run --example send-transaction
```
