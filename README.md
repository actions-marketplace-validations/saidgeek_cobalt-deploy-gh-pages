# Cobalt deploy GithubPages

This action deploy the build generated by cobalt.

## inputs
### `githubToken`
**Required** Personal Access Token with permission to the repository.
### `repo`
Repository to push building page. By default use env `GITHUB_REPOSITORY`
### `branch`
Branch to push building page. Default: `gh-pages`
### `cname`
Registry dns name to GithubPage. By default is assigned by Github.

## Example
```yaml

```