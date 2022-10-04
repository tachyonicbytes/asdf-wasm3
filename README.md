<div align="center">

# asdf-wasm3 [![Build](https://github.com/TachyonicBytes/asdf-wasm3/actions/workflows/build.yml/badge.svg)](https://github.com/TachyonicBytes/asdf-wasm3/actions/workflows/build.yml) [![Lint](https://github.com/TachyonicBytes/asdf-wasm3/actions/workflows/lint.yml/badge.svg)](https://github.com/TachyonicBytes/asdf-wasm3/actions/workflows/lint.yml)


[wasm3](https://github.com/wasm3/wasm3) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add wasm3
# or
asdf plugin add wasm3 https://github.com/TachyonicBytes/asdf-wasm3.git
```

wasm3:

```shell
# Show all installable versions
asdf list-all wasm3

# Install specific version
asdf install wasm3 latest

# Set a version globally (on your ~/.tool-versions file)
asdf global wasm3 latest

# Now wasm3 commands are available
wasm3 --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/TachyonicBytes/asdf-wasm3/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [TachyonicBytes](https://github.com/TachyonicBytes/)
