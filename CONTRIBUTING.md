## Release Process

### Setup

Update version in `package.json`

### Verification

1. Verify contents to publish `vsce ls`
1. Package local `.vsix` for testing `npm run package:latest`

### Publishing

```sh
vsce publish
```

```sh
git tag vX.X.X
git push --tags
```
