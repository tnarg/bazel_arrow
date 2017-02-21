new_http_archive(
    name='arrow_repo',
    build_file='BUILD.arrow',
    url='https://github.com/apache/arrow/archive/66f650cd359e13f3d5c3d4ef78d89f389d6bcecc.tar.gz',
    sha256='a0cab137118171d1e61c363f9449d599914f050116f735f8245b7447e5f399fe',
    strip_prefix='arrow-66f650cd359e13f3d5c3d4ef78d89f389d6bcecc',
)

bind(
    name='arrow_sources',
    actual='@arrow_repo//:sources',
)

bind(
    name='arrow_headers',
    actual='@arrow_repo//:headers',
)