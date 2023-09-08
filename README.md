


# 📛 Had

Redis Rate Limiter

> Make sure that you've filled up the env vars inside `.env` file, also make sure you've installed the wallexerr crate using ```cargo add wallexerr```.

## 🚀 Run

```bash
cargo run --bin had
```

## 📦 Publish

```bash
cargo login
cargo publish --dry-run
cargo publish
```

## 🚧 WIP

* cookie session with private key based on [wallexerr](https://crates.io/crates/wallexerr) for time hash api and rate limiting by signing a request using the private key

* add cli arg setups

* publish to crate
