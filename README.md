# burn_gaussian_splatting 🌌

[![test](https://github.com/mosure/burn_gaussian_splatting/workflows/test/badge.svg)](https://github.com/Mosure/burn_gaussian_splatting/actions?query=workflow%3Atest)
[![GitHub License](https://img.shields.io/github/license/mosure/burn_gaussian_splatting)](https://raw.githubusercontent.com/mosure/burn_gaussian_splatting/main/LICENSE)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/mosure/burn_gaussian_splatting)](https://github.com/mosure/burn_gaussian_splatting)
[![GitHub Releases](https://img.shields.io/github/v/release/mosure/burn_gaussian_splatting?include_prereleases&sort=semver)](https://github.com/mosure/burn_gaussian_splatting/releases)
[![GitHub Issues](https://img.shields.io/github/issues/mosure/burn_gaussian_splatting)](https://github.com/mosure/burn_gaussian_splatting/issues)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/mosure/burn_gaussian_splatting.svg)](http://isitmaintained.com/project/mosure/burn_gaussian_splatting)
[![crates.io](https://img.shields.io/crates/v/burn_gaussian_splatting.svg)](https://crates.io/crates/burn_gaussian_splatting)

burn gaussian splatting differentiable render and training pipeline

![Alt text](docs/notferris.png)

`cargo run -- scenes/person.gcloud`

## capabilities

- [ ] gaussian splatting person reconstruction

## usage

```rust
```

## wasm support

to build wasm run:
- `cargo build --target wasm32-unknown-unknown --release`
- `wasm-bindgen --out-dir ./out/ --target web ./target/`

