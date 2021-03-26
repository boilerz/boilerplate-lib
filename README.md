# @boilerz/boilerplate-lib

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/boilerz/boilerplate-lib/blob/master/LICENSE)
[![GH CI Action](https://github.com/boilerz/boilerplate-lib/workflows/CI/badge.svg)](https://github.com/boilerz/boilerplate-lib/actions?query=workflow:CI)
[![codecov](https://codecov.io/gh/boilerz/boilerplate-lib/branch/master/graph/badge.svg)](https://codecov.io/gh/boilerz/boilerplate-lib)

> Boilerplate lib.

### Setup

Use as template, then after pulling the repo:

```bash
yarn install
yarn custom
```

2. Add `CODECOV_TOKEN` as a secret.

3. Eventually enable auto versioning by removing `version: 'false'` in [.github/workflows/ci.yml](.github/workflows/ci.yml):

```yaml
      - uses: boilerz/action-version@master
        with:
          version: 'false'
```
