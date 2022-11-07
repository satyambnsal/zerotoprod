```
cargo install cargo-watch
cargo watch -x check
cargo watch -x check -x test -x run
```

For code coverage

```
cargo install cargo-tarpaulin
cargo tarpaulin --ignore-tests
```

For linting

```
rustup component add clippy
cargo clippy
```

Disable a noisy lint
```#[allow(clippy::lint_name)]```

For formatting

```
rustup component add rustfmt
cargo fmt
cargo fmt -- --check
```

Check for security vulnerabilities

```
cargo install cargo-audit
cargo audit
```

