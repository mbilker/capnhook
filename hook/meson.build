hook_lib = static_library(
    'hook',
    include_directories : inc,
    c_pch : '../precompiled.h',
    sources : [
        'args.c',
        'args.h',
        'com-proxy.c',
        'com-proxy.h',
        'hr.c',
        'hr.h',
        'iobuf.c',
        'iobuf.h',
        'iohook.c',
        'iohook.h',
        'pe.c',
        'pe.h',
        'peb.c',
        'peb.h',
        'process.c',
        'process.h',
        'table.c',
        'table.h',
    ],
)

hook_dep = declare_dependency(
    link_with : hook_lib,
    include_directories : inc,
)
