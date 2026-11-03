# Contributing to Lisa Harness

Bug reports, documentation improvements, tests, and focused fixes are welcome.
Read the [Code of Conduct](CODE_OF_CONDUCT.md) and use the
[security policy](SECURITY.md) for private vulnerability reports.

## Development basics

- Search [issues](https://github.com/Lisa-Harness/lisa/issues) for existing
  work. For a substantial API or architecture change, discuss scope before
  coding.
- Start from the narrowest failing case: a targeted repro or test before broad
  edits.
- Make the smallest change that solves the root cause, keep unrelated
  refactors out, and verify with the relevant tests before opening a pull
  request.
- Follow the repository's package boundaries. Application workflows normally
  belong in packs, not the core packages.

## Pull requests

- One focused change per pull request.
- Code fixes need a regression test in the same change. Do not weaken tests
  or coverage floors to manufacture a passing result.
- Describe the problem, the solution, how you verified it, and any
  compatibility impact.
- For bug reports, include expected/actual behavior, a minimal reproduction,
  OS/Python, and affected framework/host/pack versions. Do not attach live
  data directories, credentials, or private conversation logs.

## Framework and pack development

The [framework repository](https://github.com/Lisa-Harness/lisa) contains the
kernel, SDK, runtime, and the main development guides:

- [Getting started](https://github.com/Lisa-Harness/lisa/blob/main/docs/GETTING_STARTED.md)
- [Testing](https://github.com/Lisa-Harness/lisa/blob/main/docs/TESTING.md)
- [Pack authoring](https://github.com/Lisa-Harness/lisa/blob/main/docs/PACK_AUTHORING_GUIDE.md)
- [Architecture boundaries](https://github.com/Lisa-Harness/lisa/blob/main/docs/BOUNDARIES.md)