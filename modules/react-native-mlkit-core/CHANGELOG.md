# @infinitered/react-native-mlkit-core

## 2.0.0

### Major Changes

- 1e282e0: Update modules and example app to be compatible with Expo v51. Increases minimum deployment target to 13.4.

  To ensure that your app will be compatible, make sure your minimum deployment version is set higher than 13.4 by
  using the `expo-build-properties` plugin in your `app.json`.

  ```json
  {
    "plugins": [
      [
        "expo-build-properties",
        {
          "ios": {
            "deploymentTarget": "13.4"
          }
        }
      ]
    ]
  }
  ```

## 1.0.0

### Major Changes

- 4048d34: Updated modules to be compatible with Expo 50

### Minor Changes

- 4048d34: Upgrade expo and related deps to v50.
- 4048d34: Bump expo to v50

## 0.7.7

### Patch Changes

- 190d017: bump
- 55ba468: bump for ci test
- 7eb5434: Bump for CI
- fd2c513: bump for CI purposes

## 0.7.6

### Patch Changes

- f595da2: bump to trigger ci

## 0.7.5

### Patch Changes

- c2e52fc: bump version to trigger release action

## 0.7.4

### Patch Changes

- 09bea9d: bump to trigger docs deployment

## 0.7.3

### Patch Changes

- 90d6e74: bump to trigger docs deployment

## 0.7.2

### Patch Changes

- ebe42ad: bump to trigger docs deployment

## 0.7.1

### Patch Changes

- 5d3b30d: bump to test CI
- d1c784c: bump

## 0.7.0

### Minor Changes

- 8a3770d: bump for testing

### Patch Changes

- 8a3770d: change prepare to postinstall

## 0.6.9

### Patch Changes

- e84624c: bump to test CI

## 0.6.8

### Patch Changes

- 473c8df: test bump
- b74c44b: Build script update

## 0.6.7

### Patch Changes

- d52d34f: Bump to set version tags

## 0.6.6

### Patch Changes

- 0465390: style docs and fix deploy scripts

## 0.6.5

### Patch Changes

- 68a9bec: Bump

## 0.6.4

### Patch Changes

- 5ed9f17: Bump for testing

## 0.6.3

### Patch Changes

- 6cbb6fc: Bump to test release script

## 0.6.2

### Patch Changes

- 3d7866a: Remove skip-ci flag from version PRs

## 0.6.1

### Patch Changes

- 62486bb: Fix dependencies and bump version on all packages for safety
- c592f22: Add publish action for docs, and bump versions of packages to test.

## 0.6.0

### Minor Changes

- 799515e: Bumping version after rebase for safety.
- 1dd30dc: Fixing build scripts
- b70bbc0: Canges to typescript and eslint configs. Improved docs.
- 3a7d3a8: Create and import shared typescript configs

### Patch Changes

- 877cffb: docs changes and refactoring
- 8d53eb0: add dummy tests

## 0.5.0

### Minor Changes

- e0359c1: Fix release scripts

## 0.4.0

### Minor Changes

- 81e8fe2: Fix URLs in package.json

## 0.3.0

### Minor Changes

- 74e343a: remove dummy vars

## 0.2.0

### Minor Changes

- 71fdf60: Added tests and updated linter settings and scripts. Cleared linter errors.

## 0.1.0

### Minor Changes

- a287809: More testing
- a287809: Added a var to test changesets
