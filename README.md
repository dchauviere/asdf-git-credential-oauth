<div align="center">

# asdf-git-credential-oauth [![Build](https://github.com/dchauviere/asdf-git-credential-oauth/actions/workflows/build.yml/badge.svg)](https://github.com/dchauviere/asdf-git-credential-oauth/actions/workflows/build.yml) [![Lint](https://github.com/dchauviere/asdf-git-credential-oauth/actions/workflows/lint.yml/badge.svg)](https://github.com/dchauviere/asdf-git-credential-oauth/actions/workflows/lint.yml)

[git-credential-oauth](https://github.com/hickford/git-credential-oauth) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add git-credential-oauth
# or
asdf plugin add git-credential-oauth https://github.com/dchauviere/asdf-git-credential-oauth.git
```

git-credential-oauth:

```shell
# Show all installable versions
asdf list-all git-credential-oauth

# Install specific version
asdf install git-credential-oauth latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-credential-oauth latest

# Now git-credential-oauth commands are available
git-credential-oauth version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dchauviere/asdf-git-credential-oauth/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [David Chauviere](https://github.com/dchauviere/)
