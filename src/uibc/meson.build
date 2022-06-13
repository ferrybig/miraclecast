inc = include_directories('../..')
m = c_compiler.find_library('m', required: false)
executable('miracle-uibcctl', 'uibcctl.h', 'uibcctl.c',
  install: true,
  include_directories: inc,
  dependencies: [m, glib2, libmiracle_shared_dep]
)
