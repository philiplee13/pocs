## Workflow

- when PR is created - `during-pr.yaml` should run github actions for all commits
- when PR is merged - `on-merge.yaml` should run action once

  ### Future

  - It might be nice to include
    - https://github.com/googleapis/release-please-action?tab=readme-ov-file
  - potential gotchas
    - https://github.com/googleapis/release-please-action/issues/533
    - this can lead to recursive calls if not careful
