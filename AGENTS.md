# renovate

This repository holds only the caller of the reusable Renovate workflow in victor-software-house/actions.

## Rules

1. **This repository is public.**
   Keep local paths, machine names, private repository names and internal URLs out of every tracked file, commit message and pull request.
2. **Renovate never merges.**
   Keep draft pull requests on, and never turn on auto-merge.
3. **Change Renovate's behaviour in the actions repository.**
   Its configuration, scope rules and tools live there; this repository moves only its pin and its inputs.
4. **CI verifies.**
   Push the branch and read the result on the pull request.
