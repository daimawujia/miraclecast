subdir('shared')
subdir('wifi')
subdir('dhcp')
subdir('ctl')
subdir('uibc')

executable('miracled', 'miracled.c',
  dependencies: [libmiracle_shared_dep, m],
  include_directories: include_directories('..'),
  install: true
)
