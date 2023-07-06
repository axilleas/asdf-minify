<div align="center">

# asdf-minify [![Build](https://github.com/axilleas/asdf-minify/actions/workflows/build.yml/badge.svg)](https://github.com/axilleas/asdf-minify/actions/workflows/build.yml) [![Lint](https://github.com/axilleas/asdf-minify/actions/workflows/lint.yml/badge.svg)](https://github.com/axilleas/asdf-minify/actions/workflows/lint.yml)


[minify](https://github.com/tdewolff/minify) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add minify
# or
asdf plugin add minify https://github.com/axilleas/asdf-minify.git
```

`minify`:

```shell
# Show all installable versions
asdf list-all minify

# Install specific version
asdf install minify latest

# Set a version globally (on your ~/.tool-versions file)
asdf global minify latest

# Now minify commands are available
minify --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

# License

See [LICENSE](LICENSE) © [Achilleas Pipinellis](https://gitlab.com/axil)
