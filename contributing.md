# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test go-getter https://github.com/ryodocx/asdf-go-getter.git "go-getter --help"
```

Tests are automatically run in GitHub Actions on push and PR.
