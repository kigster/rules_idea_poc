workspace(name = "rules_idea_poc")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")
load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")
load("//jetbrains:jetbrains_shared_index_runtime.bzl", 'jetbrains_shared_index_runtime')

jetbrains_shared_index_runtime(
    name = "flare_shared_index_runtime",
    uploader_sha = "",
    upload_url = "https://storage.googleapis.com/flare-public",
)

