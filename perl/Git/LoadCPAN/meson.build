test_dependencies += custom_target('Error.pm',
  input: 'Error.pm',
  output: 'Error.pm',
  command: generate_perl_command,
  install: true,
  install_dir: get_option('datadir') / 'perl5/Git/LoadCPAN',
)

subdir('Mail')
