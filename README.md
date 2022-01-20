# Build Java with Maven GitHub Action
## Development
### Updating Release
- Commit local changes
- Push local changes
- Use `git log` to get the `HEAD` hash
- Update local tag to the `HEAD` hash
  - `git tag -f <TAG> <HEAD_HASH>`
- Push the updated tag to the remote
  - `git push --force origin <TAG>`