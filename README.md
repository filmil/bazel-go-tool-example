# Example go tool repository

This is an example repository containing the basic setup for go tooling.
The idea is that you can copy this repo and start your own easily.

# Refresh build files like this

```
bazel run //:gazelle
```

# Build and run the binary like this

```
bazel run //bin/hello
```

# Run tests

```
bazel test //...
```
