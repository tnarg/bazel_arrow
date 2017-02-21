package(
    default_visibility=["//visibility:public"]
)

alias(
    name='sources',
    actual='//external:arrow_sources',
)

alias(
    name='headers',
    actual='//external:arrow_headers',
)

cc_library(
    name="arrow",
    srcs=[":sources"],
    hdrs=[":headers"],
    strip_include_prefix="external/arrow_repo/cpp/src/",
)
