# Atom dot files

This are my personal Atom settings.

## How to install

```Shell
# On Windows
cd C:\Users\Admin\.atom
git clone https://github.com/felixbaron/.atom
```

## Install dependencies

(1) C++ Build tools (for Microsoft Windows only).

```Shell
Run https://visualstudio.microsoft.com/visual-cpp-build-tools/
# Download and install Build tools
```

(2) Install Python language server

```Shell
# On Windows:
pip install python-language-server[all]
# On Linux platforms
pip install 'python-language-server[all]'
```

## Install starred packages

```Shell
apm stars --install
```

## Further configurations

Add Linux file endings:

```Shell
git config --global core.eol lf
```
