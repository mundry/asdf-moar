<div align="center">

# asdf-moar [![Build](https://github.com/mundry/asdf-moar/actions/workflows/build.yml/badge.svg)](https://github.com/mundry/asdf-moar/actions/workflows/build.yml) [![Lint](https://github.com/mundry/asdf-moar/actions/workflows/lint.yml/badge.svg)](https://github.com/mundry/asdf-moar/actions/workflows/lint.yml)

[moar](https://github.com/walles/moar) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add moar
# or
asdf plugin add moar https://github.com/mundry/asdf-moar.git
```

moar:

```shell
# Show all installable versions
asdf list-all moar

# Install specific version
asdf install moar latest

# Set a version globally (on your ~/.tool-versions file)
asdf global moar latest

# Now moar commands are available
moar --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mundry/asdf-moar/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mundry](https://github.com/mundry/)
