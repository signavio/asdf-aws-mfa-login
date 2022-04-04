# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test aws-mfa-login https://github.com/karlderkaefer/asdf-aws-mfa-login.git "aws-mfa-login --version"
```

Tests are automatically run in GitHub Actions on push and PR.
