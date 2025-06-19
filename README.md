<div align="center">

# asdf-wash [![Build](https://github.com/jtakakura/asdf-wash/actions/workflows/build.yml/badge.svg)](https://github.com/jtakakura/asdf-wash/actions/workflows/build.yml) [![Lint](https://github.com/jtakakura/asdf-wash/actions/workflows/lint.yml/badge.svg)](https://github.com/jtakakura/asdf-wash/actions/workflows/lint.yml)

[wash](https://wasmcloud.com/docs/intro/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add wash
# or
asdf plugin add wash https://github.com/jtakakura/asdf-wash.git
```

wash:

```shell
# Show all installable versions
asdf list-all wash

# Install specific version
asdf install wash latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wash latest

# Now wash commands are available
wash --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtakakura/asdf-wash/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Junji Takakura](https://github.com/jtakakura/)
