project('drl-game', 'c',
    version: '0.0.1',
    meson_version: '>= 0.49.0',
    default_options: [
        'c_std=c99',
        'warning_level=1',
        'buildtype=debug'
    ]
)

drl_game_sources = [
    'main.c'
]

drl_game_deps = [
    dependency('le'),
    dependency('gtk+-3.0')
]

incdir = include_directories('.')

executable('drl-game', drl_game_sources,
    dependencies: drl_game_deps,
    include_directories: incdir,
    install: false
)
