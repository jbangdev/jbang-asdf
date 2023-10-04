# jbang-asdf [![build](https://github.com/jbangdev/jbang-asdf/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/jbangdev/jbang-asdf/actions/workflows/build.yml) [![License](https://img.shields.io/github/license/jbangdev/jbang-asdf?style=plastic)](https://github.com/jbangdev/jbang-asdf/blob/master/LICENSE)

[jbang](https://jbang.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

## Install Plugin

```bash
asdf plugin-add jbang
or
asdf plugin-add https://github.com/jbangdev/jbang-asdf
```

## Install jbang

```shell
# Show all installable versions
asdf list-all jbang

# Install specific version
asdf install jbang latest

# Set a version globally (on your ~/.tool-versions file)
asdf global jbang latest

# Now ag commands are available
jbang
```

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of `jbang`.
