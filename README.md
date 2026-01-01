# FirstRustProject

A Rust project.

## Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (rustc and cargo)

## Essential Commands

### Build Commands

```bash
# Check if code compiles (fast, no binary produced)
cargo check

# Build in debug mode (unoptimized, faster compile)
cargo build

# Build in release mode (optimized, slower compile, faster runtime)
cargo build --release
```

### Run Commands

```bash
# Compile and run in debug mode
cargo run

# Compile and run in release mode
cargo run --release

# Run with arguments
cargo run -- arg1 arg2
```

### Testing

```bash
# Run all tests
cargo test

# Run tests with output shown
cargo test -- --nocapture

# Run a specific test
cargo test test_name
```

### Code Quality

```bash
# Format code according to Rust style guidelines
cargo fmt

# Check formatting without making changes
cargo fmt -- --check

# Run linter (install with: rustup component add clippy)
cargo clippy

# Run clippy with warnings as errors
cargo clippy -- -D warnings
```

### Documentation

```bash
# Generate and open documentation
cargo doc --open

# Generate documentation without opening
cargo doc
```

### Dependency Management

```bash
# Add a dependency
cargo add dependency_name

# Remove a dependency
cargo rm dependency_name

# Update dependencies
cargo update
```

### Cleanup

```bash
# Remove build artifacts (target/ directory)
cargo clean
```

### Other Useful Commands

```bash
# Show project structure and metadata
cargo tree

# Check for outdated dependencies
cargo outdated  # requires: cargo install cargo-outdated

# Check for security vulnerabilities
cargo audit  # requires: cargo install cargo-audit

# Watch for changes and auto-compile
cargo watch  # requires: cargo install cargo-watch
cargo watch -x run  # auto-run on changes
```

## Quick Start

```bash
# Check if everything compiles
cargo check

# Run the project
cargo run

# Build optimized release binary
cargo build --release
# Binary will be at: ./target/release/FirstRustProject
```
