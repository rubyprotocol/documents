# Docker 

You need to first install [Docker](https://docs.docker.com/engine/install/) before moving on.

### Build docker image
```sh
docker build -t ruby-protocol .
```

### Start a docker container
```sh
docker run -it ruby-protocol /bin/bash
```

### Run tests
Inside the container, we can try the following tests:
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
