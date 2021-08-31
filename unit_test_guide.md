# Build and Run Instruction
### Environment setup
```sh
# Install Rust
curl --tlsv1.2 https://sh.rustup.rs -sSf | sh

# Build the project
cargo build
```

### Run tests
```sh
# Test the inner product functional encryption
cargo test test_sip -- --show-output

# Test the quadratic polynomial functional encryption
cargo test test_sgp -- --show-output

# Run the test of disease prediction (using inner product functional encryption)
cargo test test_disease_prediction -- --show-output

# Run the test of neural network (using quadratic polynomial functional encryption)
cargo test test_neural_network -- --show-output
```
