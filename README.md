# python_setting
only for me

vi ~/.config/fish/config.fish
  1 set -g fish_user_paths "/usr/local/opt/icu4c/bin" $fish_user_paths
  2 set -g fish_user_paths "/usr/local/opt/icu4c/sbin" $fish_user_paths
  3 set -gx HOMEBREW_GITHUB_API_TOKEN xxxxxxxxxxxxxxxxxxxx
  4 set -g fish_user_paths "/usr/local/sbin" $fish_user_paths
  5 eval (python -m virtualfish compat_aliases)
  6 set -g WORKON_HOME $HOME/.virtualenvs
  7 set -g PIP_VIRTUALENV_BASE $WORKON_HOME
  8 set -g PIP_RESPECT_VIRTUALENV true
  9 eval "bash /usr/local/bin/virtualenvwrapper.sh"
