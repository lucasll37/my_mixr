source_files = [
    'MetaObject.cpp',
    './Object.cpp',
    'SlotTable.cpp',


]

mixr_base = library(
    'mixr_base',
    source_files,
    include_directories : public_headers,
    dependencies : [
        thread_dep,
    ],
    link_args : [
        static_flags
    ],
    install : true,
)

mixr_base_dep = declare_dependency(
    link_with : mixr_base,
    include_directories : public_headers
)

pkg.generate(mixr_base, name : 'mixr-base')
