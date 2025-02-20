# gh-releases

Example of using `semantic-release` 

- [gh-releases](#gh-releases)
  - [Commit formats:](#commit-formats)
  - [Configurations](#configurations)


## Commit formats:

- `BREAKING CHANGE(login): new SSO provider` -> Major version bump (1.1.0 -> 2.0.0)
- `feat(login): add SSO option` → Minor version bump (1.1.0 → 1.2.0)
- `fix(login): validation error formatting` → Patch version bump (1.1.1 → 1.1.2)

`semantic-release` is the core driver for reading, extracting and utilising commit messages. More info on sematic-release can be found here: https://semantic-release.gitbook.io/semantic-release

## Configurations

Additional settings can be applied within `.releaserc.yaml`. More info can be found here: https://github.com/semantic-release/semantic-release/blob/master/docs/usage/configuration.md#configuration