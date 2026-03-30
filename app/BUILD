load("@rules_cc//cc:defs.bzl", "cc_library", "cc_binary", "cc_test")

cc_library(
    name = "calculator_lib",
    srcs = ["calculator.cpp"],
    hdrs = ["calculator.h"],
)

cc_binary(
    name = "calculator_app",
    srcs = ["main.cpp"],
    deps = [":calculator_lib"],
)

cc_test(
    name = "math_test",
    srcs = ["math_test.cpp"],
    deps = [":calculator_lib"],
)