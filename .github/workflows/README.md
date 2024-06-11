## Workflow

- when PR is created - `merge-pr.yaml` should run
  - this includes when it gets merged to main
- on merge to main
  - `release-please.yaml` should run to create the release
- when the `release pr` gets merged - that should trigger the `release-based.yaml`
  - this is the workflow that should happen when we `release` a given software
