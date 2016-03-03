load("@bazel_tools//tools/build_rules/rust:rust.bzl", "rust_binary")

rust_binary(
    name = "hello",
    srcs = ["hello.rs"],
)

rust_binary(
    name = "local",
    srcs = ["local.rs"],
    deps = [
    	"//local",
    ]
)
