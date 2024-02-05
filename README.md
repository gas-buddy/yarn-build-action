# gas-buddy/yarn-build-action

This Github Action runs the boilerplate to build and test a node project. It handles NPM_TOKEN, installs packages, runs build lint and test node scripts.

## Options

| Option Key | Required | Default |
|------------|----------|---------|
| npm-token | yes | |
| node-version | no  | 18.x    |
| node-version-file | no | "" |
| skip-test | no | "false" |
| skip-lint | no | "false" |
| ci-setup | no | "false" |

**NOTE:** Setting up Node.js version is determined from `node-version` and `node-version-file`. If node-version-file is provided as input, it will take the precedence.
