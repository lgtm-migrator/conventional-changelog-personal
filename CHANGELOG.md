## [2.1.1](https://github.com/Alorel/conventional-changelog-personal/compare/2.1.0...2.1.1) (2019-07-15)


### Dependency updates

* **package:** update lodash to version 4.17.14 ([70478e4](https://github.com/Alorel/conventional-changelog-personal/commit/70478e4)), closes [#8](https://github.com/Alorel/conventional-changelog-personal/issues/8)

# [2.1.0](https://github.com/Alorel/conventional-changelog-personal/compare/2.0.4...2.1.0) (2019-03-27)


### Features

* Add 'tweak' commit type ([ce4927a](https://github.com/Alorel/conventional-changelog-personal/commit/ce4927a))


### Maintenance

* Update dependencies ([c4ced5b](https://github.com/Alorel/conventional-changelog-personal/commit/c4ced5b))


### Performance Improvements

* Reuse the same RegExp object for greenkeeper matching ([ba66505](https://github.com/Alorel/conventional-changelog-personal/commit/ba66505))

## [2.0.4](https://github.com/Alorel/conventional-changelog-personal/compare/2.0.3...2.0.4) (2018-09-12)


### Bug Fixes

* **isGreenkeeperLockfileCommit:** The check is now case-insensitive ([01e7316](https://github.com/Alorel/conventional-changelog-personal/commit/01e7316))


### Maintenance

* **package:** Use tilde dev dependency versions ([61e8861](https://github.com/Alorel/conventional-changelog-personal/commit/61e8861))


### Reverts

* chore(package): Use tilde dev dependency versions ([2a130fe](https://github.com/Alorel/conventional-changelog-personal/commit/2a130fe))

## [2.0.3](https://github.com/Alorel/conventional-changelog-personal/compare/2.0.2...2.0.3) (2018-08-20)


### Bug Fixes

* Now correctly excludes dev dependency updates from changelog but keeps prod dependency updates ([d66e319](https://github.com/Alorel/conventional-changelog-personal/commit/d66e319))

## [2.0.2](https://github.com/Alorel/conventional-changelog-personal/compare/2.0.1...2.0.2) (2018-08-17)


### Bug Fixes

* **package:** Add yarn.lock to npmignore ([6874a19](https://github.com/Alorel/conventional-changelog-personal/commit/6874a19))
* Production dependency Greenkeeper updates now correctly fall under the right category ([9665cff](https://github.com/Alorel/conventional-changelog-personal/commit/9665cff))

## [2.0.1](https://github.com/Alorel/conventional-changelog-personal/compare/2.0.0...2.0.1) (2018-08-17)


### Bug Fixes

* **package:** update json5 to version 2.0.0 ([cdb6401](https://github.com/Alorel/conventional-changelog-personal/commit/cdb6401))

# [2.0.0](https://github.com/Alorel/conventional-changelog-personal/compare/1.2.0...2.0.0) (2018-08-16)


### Maintenance

* Disable "build" and "ci" by default ([599344c](https://github.com/Alorel/conventional-changelog-personal/commit/599344c))


### BREAKING CHANGES

* Disable "build" and "ci" by default

# [1.2.0](https://github.com/Alorel/conventional-changelog-personal/compare/1.1.0...1.2.0) (2018-08-09)


### Features

* Ignore release scope from changelog ([c460690](https://github.com/Alorel/conventional-changelog-personal/commit/c460690))


### Maintenance

* **package:** Refresh package-lock.json ([1da1fd6](https://github.com/Alorel/conventional-changelog-personal/commit/1da1fd6))
* **package:** update [@semantic-release](https://github.com/semantic-release)/npm to version 5.0.1 ([546337d](https://github.com/Alorel/conventional-changelog-personal/commit/546337d)), closes [#2](https://github.com/Alorel/conventional-changelog-personal/issues/2)

# [1.1.0](https://github.com/Alorel/conventional-changelog-personal/compare/1.0.1...1.1.0) (2018-08-02)


### Build System

* don't execute semantic-release dry run if env is not set ([cfdabdc](https://github.com/Alorel/conventional-changelog-personal/commit/cfdabdc))
* remove lts/boron ([66974b3](https://github.com/Alorel/conventional-changelog-personal/commit/66974b3))
* use lts/* for releases ([7185c09](https://github.com/Alorel/conventional-changelog-personal/commit/7185c09))


### Features

* process Greenkeeper dependency update commits in their own category ([1b6b5be](https://github.com/Alorel/conventional-changelog-personal/commit/1b6b5be))


### Tests

* Make a semantic-release dry run for testing ([ce86a75](https://github.com/Alorel/conventional-changelog-personal/commit/ce86a75))

## [1.0.1](https://github.com/Alorel/conventional-changelog-personal/compare/1.0.0...1.0.1) (2018-07-23)


### Bug Fixes

* Switched texts for "docs" and "revert" ([980124b](https://github.com/Alorel/conventional-changelog-personal/commit/980124b))


### Documentation

* **CHANGELOG:** Changed "Reverts" to "Documentation" in v1 ([3e202cd](https://github.com/Alorel/conventional-changelog-personal/commit/3e202cd))


### Maintenance

* add unnecessary production files to npmignore ([0b4d658](https://github.com/Alorel/conventional-changelog-personal/commit/0b4d658))

# 1.0.0 (2018-07-23)


### Build System

* Configure release ([c5c0aad](https://github.com/Alorel/conventional-changelog-personal/commit/c5c0aad))
* Enable signed commits ([5cd2e1f](https://github.com/Alorel/conventional-changelog-personal/commit/5cd2e1f))


### Features

* Initial implementation ([e32d078](https://github.com/Alorel/conventional-changelog-personal/commit/e32d078))


### Maintenance

* init ([ba7f0f9](https://github.com/Alorel/conventional-changelog-personal/commit/ba7f0f9))


### Documentation

* **readme:** add Greenkeeper badge ([077ad61](https://github.com/Alorel/conventional-changelog-personal/commit/077ad61))
