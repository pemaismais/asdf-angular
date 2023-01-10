<div align="center">

# asdf-angular [![Build](https://github.com/ronangaillard/asdf-angular/actions/workflows/build.yml/badge.svg)](https://github.com/ronangaillard/asdf-angular/actions/workflows/build.yml) [![Lint](https://github.com/ronangaillard/asdf-angular/actions/workflows/lint.yml/badge.svg)](https://github.com/ronangaillard/asdf-angular/actions/workflows/lint.yml)


[angular](https://github.com/illuin-tech/asdf-angular) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add angular
# or
asdf plugin add angular https://github.com/ronangaillard/asdf-angular.git
```

angular:

```shell
# Show all installable versions
asdf list-all angular

# Install specific version
asdf install angular latest

# Set a version globally (on your ~/.tool-versions file)
asdf global angular latest

# Now angular commands are available
ng --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/ronangaillard/asdf-angular/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ronan Gaillard](https://github.com/ronangaillard/)
