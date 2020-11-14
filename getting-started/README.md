# Boson Protocol : Getting Started Guide

## Contents

* [System Setup](#system-setup)
  * [OS X](#osx)
  * [Linux](#linux)

## System Setup

### <a name="osx"></a>OS X

#### Homebrew

This getting started guide makes use of Homebrew to install system level 
dependencies.

To install Homebrew:

```shell script
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

#### Node.js

We use JavaScript or JavaScript-like languages for the majority of the platform.
As a result, you'll need Node.js and NPM installed to work with most of the 
repositories. There are a number of ways to manage Node.js version on OS X
and one that has worked well for some of us is `nvm`.

To install `nvm`:

```shell script
brew install nvm
mkdir ~/.nvm
echo 'export NVM_DIR="$HOME/.nvm"' >> ~/.zshrc
echo '[ -s "/usr/local/opt/nvm/nvm.sh" ] && . "/usr/local/opt/nvm/nvm.sh"' >> ~/.zshrc
echo '[ -s "/usr/local/opt/nvm/etc/bash_completion.d/nvm" ] && . "/usr/local/opt/nvm/etc/bash_completion.d/nvm"' >> ~/.zshrc
```

Note: if you use bash instead of zsh, change `~/.zshrc` above to `~/.bashrc`

Each repository pins the version of Node.js that it requires. To install the
correct version for a repository:

```shell script
cd <repository-path>
nvm install
```

This will install both Node.js and the latest version of NPM configured for that
Node.js installation.

### Linux

Coming soon...
