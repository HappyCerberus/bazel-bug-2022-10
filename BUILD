cc_library(
    name = "library",
    srcs = ["library.cc"],
    hdrs = ["library.h"],
)

cc_test(
    name = "library_test",
    srcs = ["library_test.cc"],
    deps = [":library"],
    target_compatible_with = [
        '@platforms//os:windows',
    ]
)