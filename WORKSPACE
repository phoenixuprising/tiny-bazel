workspace(name = "tiny_bazel")

local_repository(
    name="io_bazel_rules_kotlin",
    path="../gruber-kotlin-rules"
)
load("@io_bazel_rules_kotlin//kotlin:kotlin.bzl", "kotlin_repositories", "kt_register_toolchains")
kotlin_repositories()
kt_register_toolchains()