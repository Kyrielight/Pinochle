load("@rules_java//java:defs.bzl", "java_binary")
load("@rules_kotlin//kotlin:jvm.bzl", "kt_jvm_library")

package(default_visibility = ["//visibility:public"])

kt_jvm_library(
    name = "main",
    srcs = ["Main.kt"]
)

java_binary(
    name = "roulette",
    main_class = "moe.best.pinochle.Main",
    runtime_deps = [":main"]
)