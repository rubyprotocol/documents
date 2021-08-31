# Benchmark
We give a benchmark of the implemented functional encryption schemes below. Experiments are performed on a Macbook Pro with 2.5 GHz Dual-Core Intel Core i7. All tests are run in a single thread. We run the experiments for vectors of length 1, 5, 10, and 20.

Scheme 1 | 1 | 5 | 10 | 20 
------ | ------ | ------ | ------ | ------
Encrypt | 56.1 ms | 153.3 ms | 273.9 ms | 545.7 ms
Derive Key | 0.9 ms | 3.6 ms | 5.9 ms | 11.0 ms
Decrypt | 436.5 ms | 730.5 ms | 1.1 s | 1.2 s


Scheme 2 | 1 | 5 | 10 | 20 
------ | ------ | ------ | ------ | ------
Encrypt | 50.4 ms | 277.9 ms | 600.1 ms |  1.1 s
Derive Key | 186.4 ms | 663.6 ms | 1.2 s | 2.3 s
Decrypt | 947.2 ms | 1.1 s | 1.2 s | 1.5 s


Scheme 3 | 1 | 5 | 10 | 20 
------ | ------ | ------ | ------ | ------
Encrypt | 320.7 ms | 1.5 s | 2.9 s |  5.6 s
Derive Key | 56.1 ms | 66.0 ms | 101.8 ms | 244.4 ms
Decrypt | 2.5 s | 16.8 s | 57.1 s | 179.0 s
