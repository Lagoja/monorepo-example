# Monorepo Example

This directory has 2 apps included -- a Python based project for running workflows with Temporal.io, and a NextJS based project for running a webapp with a Redis DB.

To run each project:

1. Install Devbox, following the instructions in our [Installation Guide](https://www.jetpack.io/devbox/docs/installing_devbox/)
2. To activate a shell in each of the environments, run `devbox shell`. This will install all the dependencies in your project, and run the `init-hook` in your `devbox.json`.
3. To start different services or run scripts, use `devbox run <name_of_script>`.

Each project also includes a `.envrc` file that can be used with `direnv` to automatically activate your environment -- see our [Direnv guide](https://www.jetpack.io/devbox/docs/ide_configuration/direnv/) for more details.
