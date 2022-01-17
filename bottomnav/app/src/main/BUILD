android_binary(
    name = "app",
    manifest = "AndroidManifest.xml",
    manifest_values = {
        "versionCode": "1",
        "versionName": "1.0",
        "minSdkVersion": "21",
        "targetSdkVersion": "30",
    },
    deps = [
        ":res",
        "//app/src/main/java/com/ieeelab/bottomnav:main",
    ],
)

android_library(
    name = "res",
    manifest = "manifest/AndroidManifest.xml",
    custom_package = "com.ieeelab.bottomnav",
    resource_files = glob(["res/**"]),
    visibility = ["//visibility:public"],
    deps = [
        "@maven//:com_google_android_material_material",
        "@maven//:androidx_constraintlayout_constraintlayout",
        "@maven//:androidx_navigation_navigation_ui_ktx",
        "@maven//:androidx_navigation_navigation_fragment_ktx",
    ]
)
