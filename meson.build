project('cge', 'cpp',
  version : '0.1',
  default_options : ['cpp_std=c++17'])

deps = [
  dependency('ncurses')
]

cge_dep = declare_dependency(
  include_directories : include_directories('.'),
  dependencies : deps)
