# gnu-mode


This will let you (on MacOS, with zsh) switch to `gnu-mode` where gnu core-utils
(without "g" prefix) are available. 

# Requirements
* homebrew
* coreutils homebrew package
* gnu-sed homebrew package

# Setup
* install homebrew if you haven't. https://brew.sh
* install coreutils
  * `brew install coreutils`
* install gnu-sed
  * `brew install gnu-sed`
* Put `gnu-mode` script somewhere on your $PATH.

# Caveats

This works best, if in your .zshrc, you set your $PATH pretty early like the
below.  This is because the gnubin path will be coming on the existing $PATH. 
```bash
export PATH=/Users/danny/bin:/usr/local/bin:/Users/danny/src/go/bin:$PATH:/usr/local/sbin:$HOME/.tfenv/bin:/usr/local/opt/ruby/bin:~/.iterm2/:/usr/local/opt/openssl/bin
```

