include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'chaiscript', 
  header_only = True,
  header_namespace = 'chaiscript',
  exported_headers = subdir_glob([
    ('include/chaiscript', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
