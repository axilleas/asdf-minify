# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test minify https://github.com/axilleas/asdf-minify.git "minify --help"
```

Tests are automatically run in GitHub Actions on push and PR.
