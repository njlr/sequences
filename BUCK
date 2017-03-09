include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'tao-sequences',
  header_only = True,
  header_namespace = 'tao/seq',
  exported_headers = subdir_glob([
    ('include/tao/seq', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC'
  ],
  deps = BUCKAROO_DEPS,
)
