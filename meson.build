project('c_meson_build',
        'c',
        version : '0.1.0',
        default_options : ['warning_level=3'])

incdir = include_directories('include')

executable('hello_meson',
           'src/main.c',
           install : true)

executable('hello_two_sourcefiles',
           'src/main2.c',
           'src/snd_file.c',
           include_directories : incdir,
           install: true)
