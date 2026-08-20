# Branch Protection for `master`

To make sure only `@hoskengadu` can approve pull requests into `master`, configure the repository branch protection rules in GitHub with these settings:

## Required Settings

- Protect matching branches: `master`
- Require a pull request before merging
- Require approvals: at least `1`
- Require review from Code Owners: enabled
- Dismiss stale pull request approvals when new commits are pushed: enabled
- Restrict who can push to matching branches: enabled
- Allow force pushes: disabled
- Allow deletions: disabled

## Expected Effect

- Any pull request that changes files covered by `.github/CODEOWNERS` will require approval from `@hoskengadu`.
- Direct pushes to `master` will be blocked for everyone except users explicitly allowed by the branch rule.
- New commits pushed to an approved pull request will invalidate older approvals.

## Important Note

`CODEOWNERS` alone does not enforce branch protection. The repository settings in GitHub must also be configured.

