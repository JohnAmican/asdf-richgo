<div align="center">

# asdf-richgo [![Build](https://github.com/JohnAmican/asdf-richgo/actions/workflows/build.yml/badge.svg)](https://github.com/JohnAmican/asdf-richgo/actions/workflows/build.yml) [![Lint](https://github.com/JohnAmican/asdf-richgo/actions/workflows/lint.yml/badge.svg)](https://github.com/JohnAmican/asdf-richgo/actions/workflows/lint.yml)

[richgo](https://github.com/kyoh86/richgo) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add richgo
# or
asdf plugin add richgo https://github.com/JohnAmican/asdf-richgo.git
```

richgo:

```shell
# Show all installable versions
asdf list-all richgo

# Install specific version
asdf install richgo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global richgo latest

# Now richgo commands are available
richgo version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/JohnAmican/asdf-richgo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [John Amicangelo](https://github.com/JohnAmican/)
