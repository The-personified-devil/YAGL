project('yagl', 'cpp',
    version: '0.0.0',
    license: 'GPL-3.0-or-later',
    default_options: ['warning_level=3', 'cpp_std=c++17', 'default_library=static', 'debug=true']
)

srcs = 'src/main.cpp'
yagl = library(meson.project_name(), srcs, version: meson.project_version(), install: true)

