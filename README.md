<div align="center">

# asdf-mirrord [![Build](https://github.com/infiniteregrets/asdf-mirrord/actions/workflows/build.yml/badge.svg)](https://github.com/infiniteregrets/asdf-mirrord/actions/workflows/build.yml) [![Lint](https://github.com/infiniteregrets/asdf-mirrord/actions/workflows/lint.yml/badge.svg)](https://github.com/infiniteregrets/asdf-mirrord/actions/workflows/lint.yml)

[mirrord](https://mirrord.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add mirrord
# or
asdf plugin add mirrord https://github.com/infiniteregrets/asdf-mirrord.git
```

mirrord:

```shell
# Show all installable versions
asdf list-all mirrord

# Install specific version
asdf install mirrord latest

# Set a version globally (on your ~/.tool-versions file)
asdf global mirrord latest

# Now mirrord commands are available
mirrord --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/infiniteregrets/asdf-mirrord/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Mehul](https://github.com/infiniteregrets/)
