load("//tensorboard/defs:web.bzl", "tf_web_library")

package(default_visibility = ["//tensorboard:internal"])

licenses(["notice"])  # Apache 2.0

tf_web_library(
    name = "tf_categorization_utils",
    srcs = [
        "categorizationUtils.ts",
        "tf-categorization-utils.html",
        "tf-tag-filterer.html",
    ],
    path = "/tf-categorization-utils",
    deps = [
        "//tensorboard/components/tf_backend",
        "//tensorboard/components/tf_dashboard_common",
        "//tensorboard/components/tf_imports:lodash",
        "//tensorboard/components/tf_imports:polymer",
        "//tensorboard/components/tf_storage",
        "//tensorboard/components/vz_sorting",
        "@org_polymer_iron_collapse",
        "@org_polymer_iron_icon",
        "@org_polymer_paper_input",
    ],
)
