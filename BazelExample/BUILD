load("@build_bazel_rules_apple//apple:ios.bzl", "ios_application")

ios_application(
    name = "BazelExample",
    bundle_id = "vn.com.nghianv.bazelexample",
    families = [
        "iphone",
        "ipad",
    ],
    minimum_os_version = "10.0",
    infoplists = [":Info.plist"],
    visibility = ["//visibility:public"],
    deps = [
        "//BazelExample/Submodule/Networking:Networking",
        "//BazelExample/Submodule/Database:Database"
    ],
)

# bazel build //BazelExample:BazelExample --apple_platform_type=ios
