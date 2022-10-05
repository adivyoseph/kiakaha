project('kiakaha','c')

add_global_arguments('-O2', language : 'c')

src_files = ['main.c', 'workq.c', 'common.c']

thread_dep = dependency('threads')

executable('kiakaha', sources : src_files ,dependencies : thread_dep)

