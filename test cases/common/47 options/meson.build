project('options', 'c')

if get_option('testoption') != 'optval'
  error('Incorrect value to test option')
endif

if get_option('other_one') != false
  error('Incorrect value to boolean option.')
endif

if get_option('combo_opt') != 'combo'
  error('Incorrect value to combo option.')
endif

if get_option('array_opt') != ['one', 'two']
  message(get_option('array_opt'))
  error('Incorrect value for array option')
endif

# If the default changes, update test cases/unit/13 reconfigure
if get_option('b_lto') != false
  error('Incorrect value in base option.')
endif

if get_option('includedir') != 'include'
  error('Incorrect value in builtin option.')
endif
