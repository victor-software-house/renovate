# renovate

This repository contains one workflow.
It calls the reusable Renovate workflow in victor-software-house/actions.

## Rules

1. **This repository is public.**
   Keep local paths, machine names, private repository names and internal URLs out of files, commits and pull requests.
2. **Renovate never merges.**
   Keep draft pull requests on, and never turn on auto-merge.
3. **Change how Renovate works in the actions repository.**
   Its config, scope rules and tools live there.
   This repository moves only its pin and its inputs.
4. **CI checks each change.**
   Push the branch and read the result on the pull request.
