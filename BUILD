load("@io_bazel_rules_rust//rust:rust.bzl", "rust_binary")

rust_binary(
    name = "hello",
    srcs = ["hello.rs"],
)

rust_binary(
    name = "local",
    srcs = ["local.rs"],
    deps = [
        "//local_mylib",
    ],
)
