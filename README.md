<div align="center">

# asdf-zed [![Build](https://github.com/vad/asdf-zed/actions/workflows/build.yml/badge.svg)](https://github.com/vad/asdf-zed/actions/workflows/build.yml) [![Lint](https://github.com/vad/asdf-zed/actions/workflows/lint.yml/badge.svg)](https://github.com/vad/asdf-zed/actions/workflows/lint.yml)


[zed](https://github.com/authzed/zed) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add zed
# or
asdf plugin add zed https://github.com/vad/asdf-zed.git
```

zed:

```shell
# Show all installable versions
asdf list-all zed

# Install specific version
asdf install zed latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zed latest

# Now zed commands are available
zed version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/vad/asdf-zed/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Davide Setti](https://github.com/vad/)
