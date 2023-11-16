<div align="center">

# asdf-git-subrepo [![Build](https://github.com/d3m3vilurr/asdf-git-subrepo/actions/workflows/build.yml/badge.svg)](https://github.com/d3m3vilurr/asdf-git-subrepo/actions/workflows/build.yml) [![Lint](https://github.com/d3m3vilurr/asdf-git-subrepo/actions/workflows/lint.yml/badge.svg)](https://github.com/d3m3vilurr/asdf-git-subrepo/actions/workflows/lint.yml)

[git-subrepo](https://github.com/ingydotnet/git-subrepo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add git-subrepo
# or
asdf plugin add git-subrepo https://github.com/d3m3vilurr/asdf-git-subrepo.git
```

git-subrepo:

```shell
# Show all installable versions
asdf list-all git-subrepo

# Install specific version
asdf install git-subrepo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-subrepo latest

# Now git-subrepo commands are available
git-subrepo version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/d3m3vilurr/asdf-git-subrepo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sunguk Lee](https://github.com/d3m3vilurr/)
