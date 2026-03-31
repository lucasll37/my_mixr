subdir('./base')

# Executable
src_main = files('main.cpp')

executable('main',
    src_main,
    dependencies: [mixr_base_dep],
    link_with: [mixr_base],
    include_directories: public_headers,
    install: true
)