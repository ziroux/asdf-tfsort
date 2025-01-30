<div align="center">

# asdf-tfsort [![Build](https://github.com/ziroux/asdf-tfsort/actions/workflows/build.yml/badge.svg)](https://github.com/ziroux/asdf-tfsort/actions/workflows/build.yml) [![Lint](https://github.com/ziroux/asdf-tfsort/actions/workflows/lint.yml/badge.svg)](https://github.com/ziroux/asdf-tfsort/actions/workflows/lint.yml)

[tfsort](https://github.com/AlexNabokikh/tfsort) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add tfsort
# or
asdf plugin add tfsort https://github.com/ziroux/asdf-tfsort.git
```

tfsort:

```shell
# Show all installable versions
asdf list-all tfsort

# Install specific version
asdf install tfsort latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tfsort latest

# Now tfsort commands are available
tfsort --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ziroux/asdf-tfsort/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ziroux](https://github.com/ziroux/)
