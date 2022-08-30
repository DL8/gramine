# KSS Hello World

This directory contains a Makefile and a manifest template for running a simple
"Hello World" program with KSS in Gramine.

# Building

## Building for Linux

Run `make` (non-debug) or `make DEBUG=1` (debug) in the directory.

## Building for SGX

Run `make SGX=1` (non-debug) or `make SGX=1 DEBUG=1` (debug) in the directory.

# Run Hello World with Gramine

With SGX:
```sh
gramine-sgx helloworld
```
