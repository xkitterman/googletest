cc_library(
    name       = "googlemock",
    srcs       = glob(["src/*.cc"],
                 exclude=["src/gmock-all.cc"]),
    hdrs       = glob(["include/**/*.h", "src/*.h"]),
    includes   = ["include"],
    linkopts   = ["-pthread"],
    deps       = ["//googletest"],
    visibility = ["//visibility:public"],
)
