# merge-push

This action merges two branches and pushes the result.

## Inputs

### `from-branch`
**Required** The source branch.
### `to-branch`
**Required** The target branch
### `merge-type`
The type of the merge: `merge`, `rebase`, `squash`. Default: "merge".
### `merge-commit-message`
The message for the merge commit. With `rebase` it is not used. Default: "ci: merge branches".
### `committer-name`
The name of the committer. Default: "github-actions".
### `committer-email`
The email of the committer. Default: "github-actions@github.com".
