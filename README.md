# setup-aws-amplify-cli

An Action to setup the @aws-amplify/cli npm package.

## Inputs

- `cache_dependencies` (Optional, Default: `false`): Whether to cache the installed @aws-amplify/cli or not. Uses <https://github.com/actions/cache>.
- `cli_version` (Optional, Default: `latest`): The version of @aws-amplify/cli to install.
- `node_version` (Optional): The version of node to setup. Uses <https://github.com/actions/setup-node>. If not supplied, the node version from PATH will be used. However, it is recommended to always specify Node.js version and don't rely on the system one.
