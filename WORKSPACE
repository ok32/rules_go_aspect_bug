workspace(
    name = "abc",
)

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "io_bazel_rules_go",
    commit = "451f26754eeb2c4002984873774414caab1cfd57",
    remote = "https://github.com/bazelbuild/rules_go.git",
)

load("@io_bazel_rules_go//go:deps.bzl", "go_register_toolchains", "go_rules_dependencies")

go_rules_dependencies()

go_register_toolchains(go_version = "1.17.8")
