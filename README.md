<div align="center">

# asdf-go-getter [![Build](https://github.com/ryodocx/asdf-go-getter/actions/workflows/build.yml/badge.svg)](https://github.com/ryodocx/asdf-go-getter/actions/workflows/build.yml) [![Lint](https://github.com/ryodocx/asdf-go-getter/actions/workflows/lint.yml/badge.svg)](https://github.com/ryodocx/asdf-go-getter/actions/workflows/lint.yml)

[go-getter](https://github.com/hashicorp/go-getter) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Install

Plugin:

```shell
asdf plugin add go-getter
# or
asdf plugin add go-getter https://github.com/ryodocx/asdf-go-getter.git
```

go-getter:

```shell
# Install latest version
asdf install go-getter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global go-getter latest
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.
