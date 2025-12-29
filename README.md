# asdf-ruff

[ruff](https://github.com/astral-sh/ruff) plugin for the [asdf version manager](https://asdf-vm.com).

`ruff` is an extremely fast Python linter and code formatter, written in Rust.

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

**Required:**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html)
- `git`: for listing versions
- `unzip`: for Windows installations (if using on Windows/WSL)

## Install

Plugin:

```shell
asdf plugin add ruff https://github.com/AxlER8R/asdf-ruff.git
```

ruff:

```shell
# Show all installable versions
asdf list all ruff

# Install specific version
asdf install ruff 0.14.10

# Install latest version
asdf install ruff latest

# Set a version globally (on your ~/.tool-versions file)
asdf set --home ruff latest

# Now ruff commands are available
ruff --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

## Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTE.md).

## License

See [LICENSE](LICENSE) © [AxlER8R](https://github.com/AxlER8R/)
