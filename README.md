# Get Git Version Github Action

A GitHub Action to get a [semver using git log](https://gitversion.net/docs/reference/variables).

## Usage

```yaml
  - uses: albumprinter/actions-get-git-version@v1
    id: git-version
  - run: |
    echo ${{ steps.git-version.outputs.version }}
```
