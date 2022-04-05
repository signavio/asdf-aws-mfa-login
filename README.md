<div align="center">

# asdf-aws-mfa-login [![Build](https://github.com/signavio/asdf-aws-mfa-login/actions/workflows/build.yml/badge.svg)](https://github.com/signavio/asdf-aws-mfa-login/actions/workflows/build.yml) [![Lint](https://github.com/signavio/asdf-aws-mfa-login/actions/workflows/lint.yml/badge.svg)](https://github.com/signavio/asdf-aws-mfa-login/actions/workflows/lint.yml)


[aws-mfa-login](https://github.com/signavio/aws-mfa-login) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `gunzip`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add aws-mfa-login
# or
asdf plugin add aws-mfa-login https://github.com/signavio/asdf-aws-mfa-login.git
```

aws-mfa-login:

```shell
# Show all installable versions
asdf list-all aws-mfa-login

# Install specific version
asdf install aws-mfa-login latest

# Set a version globally (on your ~/.tool-versions file)
asdf global aws-mfa-login latest

# Now aws-mfa-login commands are available
aws-mfa-login --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/signavio/asdf-aws-mfa-login/graphs/contributors)!

## Testing
```bash
asdf plugin-test aws-mfa-login https://github.com/signavio/asdf-aws-mfa-login --asdf-tool-version latest --asdf-plugin-gitref $(git rev-parse HEAD) aws-mfa-login --version
```


# License

See [LICENSE](LICENSE) © [signavio](https://github.com/signavio/)
