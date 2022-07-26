load("@hedron_compile_commands//:refresh_compile_commands.bzl", "refresh_compile_commands")

refresh_compile_commands(
    name = "refresh_compile_commands",
    targets = {
        "//:test": "",
    },
)

cc_library(
    name = "test",
    srcs = ["test.cc"],
    deps = [":test_h"],
)

cc_library(
    name = "test_h",
    hdrs = ["test.h"],
)