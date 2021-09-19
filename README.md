<div align="center">

# asdf-go-getter [![Build](https://github.com/ryodocx/asdf-go-getter/actions/workflows/build.yml/badge.svg)](https://github.com/ryodocx/asdf-go-getter/actions/workflows/build.yml) [![Lint](https://github.com/ryodocx/asdf-go-getter/actions/workflows/lint.yml/badge.svg)](https://github.com/ryodocx/asdf-go-getter/actions/workflows/lint.yml)


[go-getter](https://github.com/hashicorp/go-getter) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add go-getter
# or
asdf plugin add go-getter https://github.com/ryodocx/asdf-go-getter.git
```

go-getter:

```shell
# Show all installable versions
asdf list-all go-getter

# Install specific version
asdf install go-getter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-getter latest

# Now go-getter commands are available
go-getter --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ryodocx/asdf-go-getter/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [ryodocx](https://github.com/ryodocx/)
