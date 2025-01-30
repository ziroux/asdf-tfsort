# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test tfsort https://github.com/ziroux/asdf-tfsort.git "tfsort --help"
# or
asdf plugin test asdf-tfsort https://github.com/ziroux/asdf-tfsort --asdf-plugin-gitref my_branch "tfsort --help"
```

Tests are automatically run in GitHub Actions on push and PR.
