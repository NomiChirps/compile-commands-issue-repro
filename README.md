Minimal-ish reproduction for https://github.com/hedronvision/bazel-compile-commands-extractor/issues/70

Run with:

```
# See .bazelrc for implicit flags
bazel run :refresh_compile_commands
```

Then observe that compile_commands.json contains extraneous entries for `test.h` and many system header files, when it should have only one entry: `test.cc`.