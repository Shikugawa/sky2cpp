load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
  name = "tracer_lib",
  srcs = ["tracer_impl.cc"],
  hdrs = ["tracer_impl.h"],
  deps = ["//cpp2sky:tracer_interface"],
  visibility = ["//visibility:public"],
)