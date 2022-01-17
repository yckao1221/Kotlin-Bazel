load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kt_android_library")

kt_android_library(
    name = "main",
    srcs = glob(["*.kt"]),
    deps = [
        "//app/src/main:res",
        "//app/src/main/java/com/ieeelab/bottomnav/ui/dashboard",
        "//app/src/main/java/com/ieeelab/bottomnav/ui/home",
        "//app/src/main/java/com/ieeelab/bottomnav/ui/notifications",
        "@maven//:androidx_appcompat_appcompat",
        "@maven//:androidx_navigation_navigation_fragment_ktx",
        "@maven//:androidx_navigation_navigation_ui_ktx",
    ],
    visibility = ["//app/src/main:__subpackages__"],
)