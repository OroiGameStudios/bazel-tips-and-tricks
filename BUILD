package(default_visibility = ["//visibility:public"])

load("//:custom_rules.bzl","build_with_custom_python")

build_with_custom_python(
    name = "write-to-file",
    data_to_write_to_file = "This will look great in a text file!",
    python_compiler = ["@hermetic_python//:FunOnABun"]
    )

