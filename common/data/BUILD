load("@rules_proto//proto:defs.bzl", "proto_library")

package(default_visibility = ["//visibility:public"])

proto_library(
    name = "characters_storage",
    srcs = ["characters_storage.proto"],
)

proto_library(
    name = "characters_client",
    srcs = ["characters_client.proto"],
)

proto_library(
    name = "characters_service",
    srcs = ["characters_service.proto"],
    deps = [":characters_client"],
)
