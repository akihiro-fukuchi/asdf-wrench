<div align="center">

# asdf-wrench [![Build](https://github.com/akihiro-fukuchi/asdf-wrench/actions/workflows/build.yml/badge.svg)](https://github.com/akihiro-fukuchi/asdf-wrench/actions/workflows/build.yml) [![Lint](https://github.com/akihiro-fukuchi/asdf-wrench/actions/workflows/lint.yml/badge.svg)](https://github.com/akihiro-fukuchi/asdf-wrench/actions/workflows/lint.yml)

[wrench](https://github.com/akihiro-fukuchi/wrench) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wrench
# or
asdf plugin add wrench https://github.com/akihiro-fukuchi/asdf-wrench.git
```

wrench:

```shell
# Show all installable versions
asdf list-all wrench

# Install specific version
asdf install wrench latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wrench latest

# Now wrench commands are available
wrench --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/akihiro-fukuchi/asdf-wrench/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [akihiro-fukuchi](https://github.com/akihiro-fukuchi/)
