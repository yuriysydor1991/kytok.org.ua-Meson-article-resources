project(
  'TheMesonEasyStarterDemoProject',
  'cpp',
  license: 'Free to use',
  version: '0.1.0',
  meson_version: '>= 0.61.2',
  default_options: [
    'cpp_std=c++17',
  ],
)

executable(
  meson.project_name(), 
  ['main.cpp'],
  include_directories: [include_directories('.')],
  install: true,
  install_dir: 'bin'
)
