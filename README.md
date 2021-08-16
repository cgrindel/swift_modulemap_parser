# Clang module.modulemap Parser Written in Swift

![build status](https://github.com/cgrindel/swift_modulemap_parser/actions/workflows/bazel.yml/badge.svg)

This parser was originally created to facilitate the parsing and exposition of module information
from a clang `module.modulemap` file for the [rules_spm
repository](https://github.com/cgrindel/rules_spm). However, this effort was abandoned when it was
determined that a modulemap parser written in
[Starlark](https://docs.bazel.build/versions/main/skylark/language.html) would reduce the
complications with installing and using the repository rules contained in
[rules_spm](https://github.com/cgrindel/rules_spm).

There are no plans to maintain this project. Feel free to fork it and enhance it. 😀
