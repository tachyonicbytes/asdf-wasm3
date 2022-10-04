# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test wasm3 https://github.com/TachyonicBytes/asdf-wasm3.git "wasm3 --version"
```

Tests are automatically run in GitHub Actions on push and PR.
