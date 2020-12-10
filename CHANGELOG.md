# Changelog

[PyPI History][1]

[1]: https://pypi.org/project/google-cloud-runtimeconfig/#history

### [0.32.1](https://www.github.com/googleapis/python-runtimeconfig/compare/v0.32.0...v0.32.1) (2020-12-10)


### Documentation

* update intersphinx for grpc and auth ([#27](https://www.github.com/googleapis/python-runtimeconfig/issues/27)) ([1044e73](https://www.github.com/googleapis/python-runtimeconfig/commit/1044e73a4e65e2bef5e9a5a36d1e64e28169dc3e))

## [0.32.0](https://www.github.com/googleapis/python-runtimeconfig/compare/v0.31.0...v0.32.0) (2020-06-05)


### Features

* support variable create / update methods and text attribute ([#17](https://www.github.com/googleapis/python-runtimeconfig/issues/17)) ([84a50ad](https://www.github.com/googleapis/python-runtimeconfig/commit/84a50ad6cd0765bd86a4ed7c338aec2612e5e91c)), closes [#1](https://www.github.com/googleapis/python-runtimeconfig/issues/1)

## [0.31.0](https://www.github.com/googleapis/python-runtimeconfig/compare/v0.30.0...v0.31.0) (2020-05-01)


### Features

* set release_status to beta ([#9](https://www.github.com/googleapis/python-runtimeconfig/issues/9)) ([679df3f](https://www.github.com/googleapis/python-runtimeconfig/commit/679df3fda74a20b3788f5e0fe7dac5d1d22b90cb))


### Bug Fixes

* **runtimeconfig:** update test assertion and core version pins ([#10097](https://www.github.com/googleapis/python-runtimeconfig/issues/10097)) ([cb421af](https://www.github.com/googleapis/python-runtimeconfig/commit/cb421af64af0aa7e73d0da146458194fb955801d))

## 0.30.0

10-15-2019 06:53 PDT


### New Features
- Add `client_options` to client. ([#9045](https://github.com/googleapis/google-cloud-python/pull/9045))

### Dependencies
- Pin 'google-cloud-core >= 1.0.3, < 2.0.0dev'. ([#9445](https://github.com/googleapis/google-cloud-python/pull/9445))

### Documentation
- Fix intersphinx reference to requests. ([#9294](https://github.com/googleapis/google-cloud-python/pull/9294))
- Fix broken links in docs. ([#9148](https://github.com/googleapis/google-cloud-python/pull/9148))
- Remove compatability badges from READMEs. ([#9035](https://github.com/googleapis/google-cloud-python/pull/9035))
- Update intersphinx mapping for requests. ([#8805](https://github.com/googleapis/google-cloud-python/pull/8805))

## 0.29.2

07-24-2019 17:26 PDT


### Documentation
- Fix docs navigation issues. ([#8723](https://github.com/googleapis/google-cloud-python/pull/8723))
- Link to googleapis.dev documentation in READMEs. ([#8705](https://github.com/googleapis/google-cloud-python/pull/8705))
- Add compatibility check badges to READMEs. ([#8288](https://github.com/googleapis/google-cloud-python/pull/8288))

### Internal / Testing Changes
- Add nox session 'docs' to remaining manual clients. ([#8478](https://github.com/googleapis/google-cloud-python/pull/8478))
- Add docs job to publish to googleapis.dev. ([#8464](https://github.com/googleapis/google-cloud-python/pull/8464))

## 0.29.1

06-04-2019 11:15 PDT


### Dependencies
- Don't pin `google-api-core` in libs using `google-cloud-core`. ([#8213](https://github.com/googleapis/google-cloud-python/pull/8213))

## 0.29.0

05-16-2019 12:32 PDT


### Implementation Changes
- Remove classifier for Python 3.4 for end-of-life. ([#7535](https://github.com/googleapis/google-cloud-python/pull/7535))

### New Features
- Add `client_info` support to client / connection. ([#7871](https://github.com/googleapis/google-cloud-python/pull/7871))

### Dependencies
- Pin `google-cloud-core >= 1.0.0, < 2.0dev`. ([#7993](https://github.com/googleapis/google-cloud-python/pull/7993))

### Documentation
- Updated client library documentation URLs. ([#7307](https://github.com/googleapis/google-cloud-python/pull/7307))

## 0.28.3

12-17-2018 17:01 PST


### Documentation
- Document Python 2 deprecation ([#6910](https://github.com/googleapis/google-cloud-python/pull/6910))
- Docs/fixit: normalize docs for `page_size` / `max_results` / `page_token`. ([#6842](https://github.com/googleapis/google-cloud-python/pull/6842))

## 0.28.2

12-10-2018 13:05 PST


### Implementation Changes
- Import `iam.policy` from `google.api_core`. ([#6741](https://github.com/googleapis/google-cloud-python/pull/6741))
- Fix variable nanosecond timestamp `update_time` from response ([#4819](https://github.com/googleapis/google-cloud-python/pull/4819))

### Dependencies
- Update dependency to google-cloud-core ([#6835](https://github.com/googleapis/google-cloud-python/pull/6835))
- Bump minimum `api_core` version for all GAPIC libs to 1.4.1. ([#6391](https://github.com/googleapis/google-cloud-python/pull/6391))

### Documentation
- Update README service links in quickstart guides. ([#6322](https://github.com/googleapis/google-cloud-python/pull/6322))
- Normalize use of support level badges ([#6159](https://github.com/googleapis/google-cloud-python/pull/6159))
- Prep docs for repo split. ([#6023](https://github.com/googleapis/google-cloud-python/pull/6023))

### Internal / Testing Changes
- Add blacken to noxfile ([#6795](https://github.com/googleapis/google-cloud-python/pull/6795))
- Blackening Continued... ([#6667](https://github.com/googleapis/google-cloud-python/pull/6667))
- Add templates for flake8, coveragerc, noxfile, and black. ([#6642](https://github.com/googleapis/google-cloud-python/pull/6642))
- Use new Nox ([#6175](https://github.com/googleapis/google-cloud-python/pull/6175))
- Add Test runs for Python 3.7 and remove 3.4 ([#5295](https://github.com/googleapis/google-cloud-python/pull/5295))
- Add tests with microseconds and nanoseconds ([#5150](https://github.com/googleapis/google-cloud-python/pull/5150))
- Fix bad trove classifier

## 0.28.1

### Implementation changes

- Set default variable state to Unspecified (#4738)

### Dependencies

- Update dependency range for api-core to include v1.0.0 releases (#4944)

### Documentation

- Fixing "Fore" -> "For" typo in README docs. (#4317)

### Testing and internal changes

- Install local dependencies when running lint (#4936)
- Re-enable lint for tests, remove usage of pylint (#4921)
- Normalize all setup.py files (#4909)
- Making a `nox -s default` session for all packages. (#4324)
- Shorten test names (#4321)

## 0.28.0

### Documentation

- Added link to "Python Development Environment Setup Guide" in
  project README (#4187, h/t to @michaelawyu)
- Fix example in `Config.get_variable()` (#3910)

### Dependencies

- Upgrading to `google-cloud-core >= 0.28.0` and adding dependency
  on `google-api-core` (#4221, #4280)

PyPI: https://pypi.org/project/google-cloud-runtimeconfig/0.28.0/
