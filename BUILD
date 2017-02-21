package(
    default_visibility=["//visibility:public"]
)

alias(
    name='sources',
    actual='@arrow_repo//:sources',
)

alias(
    name='headers',
    actual='@arrow_repo//:headers',
)

cc_library(
    name="arrow",
    srcs=[":sources"],
    hdrs=[":headers"],
    strip_include_prefix="external/arrow_repo/cpp/src/",
)
