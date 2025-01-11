# [db-academy.io](https://db-academy.io)'s sql parser course template project

A template project for [db-academy.io](https://db-academy.io)'s sql parser course

## DevContainer 

This project uses [DevContainer](https://devcontainer.json) to provide a consistent development environment. DevContainer image is based on the Rust toolchain, and contains several useful tools for the course.

To interact with the [db-academy-io](https://db-academy-io.github.io/db-academy-io/), you can use a [dbcheck](https://github.com/db-academy-io/cargo-dbcheck) command (which is already installed in the devcontainer). Explore the [dbcheck](https://github.com/db-academy-io/cargo-dbcheck) commands by running 

```bash
cargo dbcheck --help
```

### VSCode

If you're using [VSCode](https://code.visualstudio.com), you can install the [DevContainer extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) and reopen the project in a devcontainer. 

### Other IDEs

For other IDEs, you can use the [DevContainer CLI](https://docs.devcontainers.io/cli/installation) documentation to set up a devcontainer.
