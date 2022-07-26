Minimal-ish reproduction for https://github.com/hedronvision/bazel-compile-commands-extractor/issues/70

Run with:

```
bazel run :refresh_compile_commands
```

Tested on Windows with the following Bazel version, but I have no reason to believe it won't work the same way on Linux.
```
Bazelisk version: v1.12.0
Build label: 5.2.0
Build target: bazel-out/x64_windows-opt/bin/src/main/java/com/google/devtools/build/lib/bazel/BazelServer_deploy.jar
Build time: Tue Jun 7 16:03:57 2022 (1654617837)
Build timestamp: 1654617837
Build timestamp as int: 1654617837
```
