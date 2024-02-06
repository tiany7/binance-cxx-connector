cc_library(
    name = "jsoncpp",
    srcs = ["jsoncpp/src/jsoncpp.cpp"],
    hdrs = glob(["jsoncpp/include/**/*.h"]),
    visibility = ["//visibility:public"],
)

cc_library(
    name = "libbinacpp",
    srcs = glob(["libbinacpp/lib/*.o"]),
    hdrs = glob(["libbinacpp/include/**/*.h"]),
    visibility = ["//visibility:public"],
    deps = [":jsoncpp"],
)

cc_library(
    name = "libcurl",
    srcs = [],
    hdrs = glob(["libcurl-7.56.0/include/curl/*.h"]),
    visibility = ["//visibility:public"],
)

cc_library(
    name = "libwebsockets",
    srcs = [],
    hdrs = glob(["libwebsockets-2.4.0/include/**/*.h"]),
    visibility = ["//visibility:public"],
)
