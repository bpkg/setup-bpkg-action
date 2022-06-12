setup-bpkg-action
=================

> A GitHub Action the provides the [bkpg](https://github.com/bpkg/bpkg)
> command in an action environment.

## Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: actions/checkout@v3
- uses: bpkg/setup-bpkg-action@v1
  with:
    bpkg-version: 1.1.2
```

## License

MIT
