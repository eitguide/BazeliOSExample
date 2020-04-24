load("@build_bazel_rules_swift//swift:swift.bzl", "swift_library")

swift_library(
    name = "Networking",
    module_name = "Networking",
    srcs = glob([
        "Sources/**/*.swift",
    ]),
    deps = [
        "//BazelExample/Submodule/Database:Database"
    ],
    visibility = ["//visibility:public"]
)


# bazel build //BazelExample/Submodule/Networking:Networking --apple_platform_type=ios
