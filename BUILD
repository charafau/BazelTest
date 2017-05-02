android_binary(
    name = "BazelTest",
    custom_package = "com.nullpointerbay.bazeltest",
    manifest = "app/src/main/AndroidManifest.xml",
    visibility = ["//visibility:public"],
    resource_files = glob(["app/src/main/res/**"]),
    deps = [":activities"],
)

android_library(
    name = "activities",
    srcs = glob(["app/src/main/java/com/nullpointerbay/bazeltest/*.java"]),
    manifest = "app/src/main/AndroidManifest.xml",
    custom_package = "com.nullpointerbay.bazeltest",
    resource_files = glob(["app/src/main/res/**"]),
    deps = ["@androidsdk//com.android.support:appcompat-v7-25.3.1"],
)