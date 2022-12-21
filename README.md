<div align="center">

# asdf-lefthook [![Build](https://github.com/bradym/asdf-lefthook/actions/workflows/build.yml/badge.svg)](https://github.com/bradym/asdf-lefthook/actions/workflows/build.yml) [![Lint](https://github.com/bradym/asdf-lefthook/actions/workflows/lint.yml/badge.svg)](https://github.com/bradym/asdf-lefthook/actions/workflows/lint.yml)


[lefthook](<TOOL HOMEPAGE>) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add lefthook
# or
asdf plugin add lefthook https://github.com/bradym/asdf-lefthook.git
```

lefthook:

```shell
# Show all installable versions
asdf list-all lefthook

# Install specific version
asdf install lefthook latest

# Set a version globally (on your ~/.tool-versions file)
asdf global lefthook latest

# Now lefthook commands are available
lefthook version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bradym/asdf-lefthook/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Brady Mitchell](https://github.com/bradym/)
