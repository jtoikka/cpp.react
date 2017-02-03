project('CppReact', 'cpp',
  default_options: ['cpp_std=c++14'])

include_dirs = include_directories('include')

sources = [
  'src/engine/PulsecountEngine.cpp',
  'src/engine/SubtreeEngine.cpp',
  'src/engine/ToposortEngine.cpp',
  'src/logging/EventLog.cpp',
  'src/logging/EventRecords.cpp',
]

CppReact_lib = library(
  'CppReact',
  sources: sources
)

CppReact_dep = declare_dependency(
  link_with: CppReact_lib,
  include_directories: include_dirs
)
