# Quick Branch Protection Checklist

Use these settings in GitHub for `master`:

1. Open the repository settings.
2. Go to Branches.
3. Add or edit the protection rule for `master`.
4. Enable `Require a pull request before merging`.
5. Enable `Require review from Code Owners`.
6. Set required approvals to `1`.
7. Enable `Dismiss stale pull request approvals when new commits are pushed`.
8. Enable `Restrict who can push to matching branches`.
9. Disable `Allow force pushes`.
10. Disable `Allow deletions`.

Expected result:

- Only approved pull requests can reach `master`.
- `@hoskengadu` remains the required code owner approver through `.github/CODEOWNERS`.

