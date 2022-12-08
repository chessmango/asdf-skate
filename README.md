<div align="center">

# asdf-skate [![Build](https://github.com/chessmango/asdf-skate/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-skate/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-skate/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-skate/actions/workflows/lint.yml)


[skate](https://github.com/charmbracelet/skate) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add skate https://github.com/chessmango/asdf-skate.git
```

skate:

```shell
# Show all installable versions
asdf list-all skate

# Install specific version
asdf install skate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global skate latest

# Now skate commands are available
skate --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-skate/graphs/contributors)!

# License

See [LICENSE](LICENSE)
