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


https://www.lpalmieri.com/

## User story - 1

As a blog visitor, I want to subscribe to the newsletter, So that I can receive email updates when new content is published on the blog.

```
cargo install cargo-edit
cargo add actix-web --vers 4.0.0
```