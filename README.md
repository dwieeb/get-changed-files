# Get All Changed Files

Get all of the files changed/modified in a pull request or push's commits.
You can choose to get all changed files, only added files, only modified files, only removed files, only renamed files, or all added and modified files.
These outputs are available via the `steps` output context.
The `steps` output context exposes the output names `all`, `added`, `modified`, `removed`, `renamed`, and `added_modified`.

# Usage

See [action.yml](action.yml)

```yaml
- uses: dwieeb/get-changed-files@main
  with:
    format: 'json'
```
