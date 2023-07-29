# Rust Axum Web Development Example 1

```bash
cargo install cargo-watch
cargo watch -q -c -w src/ -x run # server
cargo watch -q -c -w tests/ -x "test -q quick_dev -- --nocapture" # client / test
```

## Creation History

```bash
cargo new rust-axum-ex1
cd rust-axum-ex1/
cargo add tokio -F full
cargo add axum
cargo add --dev httpc-test
cargo add --dev anyhow
cargo add serde -F derive
cargo add serde_json
```

## Code History

The code in this repository is based on the
[Rust Axum Full Course - Web Development](https://youtu.be/XZtlD_m59sM)
video.
