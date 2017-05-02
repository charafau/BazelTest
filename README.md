# BazelTest
sample bazel with gradle android project

this doesnt work yet (compiles but got an error when starts)

sample `WORKSPACE` file:

```
android_sdk_repository(
    name = "androidsdk",
    # Replace with your installed Android SDK API level
    api_level = 25,
    path="/Users/charafau/Utils/android-sdk",
    build_tools_version = "25.0.2",
)
```
