workspace(name = "libparserutils")

load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")

git_repository(
    name = "com_github_zaucy_bazel_gnuwin_libiconv",
    remote = "https://github.com/zaucy/bazel_gnuwin_libiconv",
    commit = "2e5b17165016a5f76e18820cedb3f1d4d3e5eee6",
    shallow_since = "1602451268 -0700",
)

load("@com_github_zaucy_bazel_gnuwin_libiconv//:index.bzl", "gnuwin_libiconv_repository")

gnuwin_libiconv_repository(name = "libiconv")
