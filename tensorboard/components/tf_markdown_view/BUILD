load("//tensorboard/defs:defs.bzl", "tensorboard_webcomponent_library")
load("//tensorboard/defs:web.bzl", "tf_web_library")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])  # Apache 2.0

tf_web_library(
    name = "tf_markdown_view",
    srcs = ["tf-markdown-view.html"],
    path = "/tf-markdown-view",
    deps = [
        "//tensorboard/components/tf_imports:polymer",
        "@org_polymer_paper_styles",
    ],
)

tensorboard_webcomponent_library(
    name = "legacy",
    srcs = ["tf_markdown_view"],
    destdir = "tf-markdown-view",
    deps = [
        "//tensorboard/components/tf_imports:polymer_lib",
        "//third_party/javascript/polymer/v2/paper-styles:lib",
    ],
)
