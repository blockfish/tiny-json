project('tiny-json', ['c'], version : '1.0', license : 'MIT')
inc = include_directories('.')
src = files('tiny-json.c')
lib_static = static_library('tiny-json', src, include_directories : inc)
dep_static = declare_dependency(link_with : lib_static, include_directories : inc)
