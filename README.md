<div align="center">

# asdf-ffizer [![Build](https://github.com/ffizer/asdf-ffizer/actions/workflows/build.yml/badge.svg)](https://github.com/ffizer/asdf-ffizer/actions/workflows/build.yml)

[ffizer](https://ffizer.github.io/ffizer/book/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add ffizer
# or
asdf plugin add ffizer https://github.com/ffizer/asdf-ffizer.git
```

ffizer:

```shell
# Show all installable versions
asdf list-all ffizer

# Install specific version
asdf install ffizer latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ffizer latest

# Now ffizer commands are available
ffizer --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.
