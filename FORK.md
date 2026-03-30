# Fork Notes

Personal fork of [HiEventsDev/hi.events](https://github.com/HiEventsDev/hi.events).

## Divergences from upstream

This section tracks intentional changes that differ from upstream.
Update this file whenever a patch is added or removed.

| Description | Files affected | Status |
|-------------|---------------|--------|
| *(none — fork is clean)* | — | — |

## Upstream sync

Synced automatically every Monday via `.github/workflows/sync-upstream.yml`.

- **Strategy**: `git rebase upstream/develop` (linear history, no merge commits)
- **On conflict**: a draft PR is opened for manual resolution
- Manual trigger: GitHub Actions → "Sync with upstream" → Run workflow

## Contributing back to upstream

Before opening a PR to upstream:
1. Verify the change is not already in a pending upstream PR
2. Check upstream's open issues for related discussions
3. Target upstream's `develop` branch
