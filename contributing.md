# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test git-credential-oauth https://github.com/dchauviere/asdf-git-credential-oauth.git "git-credential-oauth version"
```

Tests are automatically run in GitHub Actions on push and PR.
