# bazel-example-rust

An example project demonstrating bazel build rules for rust with
a local binary (rust_binary) and a local library (rust_library).

This requires bazel release > `bazel-0.20`.

```
$ bazel run :hello
$ bazel run :local
```


