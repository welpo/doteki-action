# Changelog

Welcome to the changelog for dōteki-action. This document aims to provide a comprehensive list of all notable changes made to the project, organised chronologically by release version.

We use Semantic Versioning (SemVer) for our version numbers, formatted as MAJOR.MINOR.PATCH. Major version changes involve significant (breaking) changes, minor versions introduce features and improvements in a backward compatible manner, and patch versions are for bug fixes and minor tweaks.

## [0.0.9](https://github.com/welpo/doteki-action/compare/v0.0.8..v0.0.9) - 2025-02-19

### ✨ Features

- Update dōteki to 0.0.9 ([fc8350e](https://github.com/welpo/doteki-action/commit/fc8350ea0429c607cedc00bb648c1994ee0abc52))
- Support `DRY_RUN` mode through env var ([45c53ec](https://github.com/welpo/doteki-action/commit/45c53ecb51a15ddb0d53ad28bf5e24c18537d2a0)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CI)* Add concurrency control to sumi action ([2021345](https://github.com/welpo/doteki-action/commit/2021345ae52c4480ec85376904e7bb1c7a6400cf)) by [@welpo](https://github.com/welpo)
- *(CI)* Allow longer PR titles for dep updates ([c45bf8a](https://github.com/welpo/doteki-action/commit/c45bf8ac88212074c34bfd6a3816b655430b3b96)) by [@welpo](https://github.com/welpo)
- *(CI)* Allow longer PR titles for dep updates ([07a3436](https://github.com/welpo/doteki-action/commit/07a3436463ff8404fced994898eca280d02f1c83)) by [@welpo](https://github.com/welpo)
- *(CI)* Allow longer PR titles for dep updates ([53261a7](https://github.com/welpo/doteki-action/commit/53261a7f4942e6c13af71c8138e34cbb3f82401e)) by [@welpo](https://github.com/welpo)
- *(CI)* Dry-run dōteki on PRs ([83400c7](https://github.com/welpo/doteki-action/commit/83400c7bfdaa0305a8b3d3683fd4825c148d28de)) by [@welpo](https://github.com/welpo)
- *(CI)* Use CHANGES.md for GitHub release notes ([892e357](https://github.com/welpo/doteki-action/commit/892e357944d848c9b01ef4abbb2d7249db870e97)) by [@welpo](https://github.com/welpo)
- *(deps)* Remove local release script ([4b98882](https://github.com/welpo/doteki-action/commit/4b98882a9173ea8370f65bc35f67f861d2ed72f8)) by [@welpo](https://github.com/welpo)
- *(deps)* Replace local release script w/ git submodule ([ba8dd08](https://github.com/welpo/doteki-action/commit/ba8dd084dfa19beaa79eee41a75b8f79160b0718)) by [@welpo](https://github.com/welpo)
- *(release)* Improve script robustness ([2dea9f3](https://github.com/welpo/doteki-action/commit/2dea9f3f8ff7f105504b9401fe97faf4bce65d0e)) by [@welpo](https://github.com/welpo)
- *(release)* Replace both pull and issue links ([130a131](https://github.com/welpo/doteki-action/commit/130a131c70001f71ecf25237e536a75d15b2c2da)) by [@welpo](https://github.com/welpo)
- Update git-cliff variables to `commit.remote` ([639074f](https://github.com/welpo/doteki-action/commit/639074f7f10f7ab10ad8fd212227ed46a19adc85)) by [@welpo](https://github.com/welpo)

### 👥 New contributors

🫶 [@actions](https://github.com/actions) made their first contribution

🫶 [@welpo](https://github.com/welpo) made their first contribution

🫶 [@renovate](https://github.com/renovate)[bot] made their first contribution in [#1](https://github.com/welpo/doteki-action/pull/1)

## [0.0.8](https://github.com/welpo/doteki-action/compare/v0.0.7..v0.0.8) - 2024-02-21

### ✨ Features

- Update dōteki to v0.0.8 ([14afe26](https://github.com/welpo/doteki-action/commit/14afe2658dbc8e07b447f91f41bb938db2195bc3)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(git-sumi)* Improve emoji matching ([691dea7](https://github.com/welpo/doteki-action/commit/691dea7e6226df90467c01dba54778130450b3d4)) by [@welpo](https://github.com/welpo)
- *(release)* Update CHANGELOG format ([ca3598e](https://github.com/welpo/doteki-action/commit/ca3598eb7165f834cd6cbe8812d972fb2abe5771)) by [@welpo](https://github.com/welpo)
- *(renovate)* Move config file ([5000d89](https://github.com/welpo/doteki-action/commit/5000d89b3ea6cb6a071a9509be9f6774889cdc74)) by [@welpo](https://github.com/welpo)

## [0.0.7](https://github.com/welpo/doteki-action/compare/v0.0.3..v0.0.7) - 2024-02-10

### ✨ Features

- Update dōteki to v0.0.7 ([9690782](https://github.com/welpo/doteki-action/commit/96907820cb3637ef9cf92e509b21d258b8fd638d)) by [@welpo](https://github.com/welpo)

### 📝 Documentation

- *(README)* Add git-sumi badge ([ee6e541](https://github.com/welpo/doteki-action/commit/ee6e54162e3838c35fda925cfcaeaa679b424fba)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CHANGELOG)* Improve emoji pattern ([6b6eacf](https://github.com/welpo/doteki-action/commit/6b6eacfa64e27c844329ac314612a3e7a8b58468)) by [@welpo](https://github.com/welpo)
- *(CI)* Update git-sumi config ([c564ef9](https://github.com/welpo/doteki-action/commit/c564ef93514f130dd481ce28903e0395da17d0bd)) by [@welpo](https://github.com/welpo)
- *(git-sumi)* Require a space after the gitmoji ([6956244](https://github.com/welpo/doteki-action/commit/6956244a9ae0308b8b49ca7ff8cc29bb6ebdc858)) by [@welpo](https://github.com/welpo)
- *(release)* Verify version tag format on release ([486d0d1](https://github.com/welpo/doteki-action/commit/486d0d17318658c06361c867cdb37b89122d8919)) by [@welpo](https://github.com/welpo)

## [0.0.3](https://github.com/welpo/doteki-action/compare/v0.0.2..v0.0.3) - 2024-02-07

### ✨ Features

- Update doteki version to 0.0.3 ([7ef0dea](https://github.com/welpo/doteki-action/commit/7ef0dea975052b28876e41583f1835f8dcfd9384)) by [@welpo](https://github.com/welpo)

### 🔧 Miscellaneous tasks

- *(CI)* Fix links in tag description ([9ad1fba](https://github.com/welpo/doteki-action/commit/9ad1fbadedd430f79d7a15efd8dbd4f61ce3aafd)) by [@welpo](https://github.com/welpo)
- Update changelog sections ([9ace49f](https://github.com/welpo/doteki-action/commit/9ace49f2ae3fb57bc7903ca5e600ae3810a35a9b)) by [@welpo](https://github.com/welpo)
- Use git-sumi to lint commit messages ([86c6261](https://github.com/welpo/doteki-action/commit/86c6261fde4576f4d88245d8093ed87528ebb5e5)) by [@welpo](https://github.com/welpo)
- Add continuous deployment workflow ([c9cf2f6](https://github.com/welpo/doteki-action/commit/c9cf2f659b5f0ec93b1133d461aa0390afee37b1)) by [@welpo](https://github.com/welpo)

## [0.0.2](https://github.com/welpo/doteki-action/compare/v0.0.1..v0.0.2) - 2024-01-26

### ✨ Features

- Allow custom working directory ([bd3ec1b](https://github.com/welpo/doteki-action/commit/bd3ec1b2181a021988811ffc06378af5f8d28a71)) by [@welpo](https://github.com/welpo)

### 🐛 Bug fixes

- Upgrade from doteki 0.0.1 to 0.0.2 ([406f92e](https://github.com/welpo/doteki-action/commit/406f92e15b6213e0341269112add52fffc532d57)) by [@welpo](https://github.com/welpo)

### 👥 New contributors

🫶 [@actions](https://github.com/actions) made their first contribution

## 0.0.1 - 2024-01-19

### ✨ Features

- Initial commit ([b44d617](https://github.com/welpo/doteki-action/commit/b44d617a2c06940615a838b2a62df7b2186ab53c)) by [@welpo](https://github.com/welpo)

### 👥 New contributors

🫶 [@welpo](https://github.com/welpo) made their first contribution

<!-- generated by git-cliff -->
