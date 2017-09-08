include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'curlpp',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.hpp'),
    ('include', '**/*.inl'),
  ]),
  srcs = glob([
    'src/curlpp/**/*.cpp',
  ]),
  deps = BUCKAROO_DEPS,
  visibility = [
    'PUBLIC',
  ],
)
