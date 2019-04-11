# pre-commit hooks

- `go-fmt`: gofmt golang files before git commit. ref: [golang.org](https://golang.org/misc/git/pre-commit)


## Usage

example `.pre-commit-config.yaml`

```yaml
repos:
-   repo: https://github.com/x1ah/pre-commit-hooks
    rev: 'master'
    hooks:
        -   id: go-fmt
```
