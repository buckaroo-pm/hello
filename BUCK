cxx_library(
  name = 'hello',
  header_namespace = '',
  exported_headers = [
    'hello.hpp',
  ],
  srcs = [
    'hello.cpp',
  ],
  licenses = [
    'LICENSE',
  ], 
  visibility = [
    'PUBLIC',
  ],
)

cxx_binary(
  name = 'demo',
  srcs = [
    'demo.cpp',
  ],
  deps = [
    ':hello',
  ],
)
