project('glad','c')

inc = include_directories('include')
glad_lib = library('glad', sources: 'src/glad.c', include_directories: inc)

glad_dep = declare_dependency(
  include_directories: inc,
  link_with: glad_lib,
)
