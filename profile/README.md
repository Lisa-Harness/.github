# Lisa Harness

Lisa is a modular, extensible AI agent runtime and host: an inspectable
tool-enabled turn loop, intent-driven mode switching, event-driven model
routing, and explicit read/write/execute approvals. A host owns the operator
conversation; installed packs supply everything the agent can do.

| Repository | Role |
| --- | --- |
| [lisa](https://github.com/Lisa-Harness/lisa) | The framework: kernel, SDK, runtime, MCP servers, and bundled reference packs |
| [lisa-cli](https://github.com/Lisa-Harness/lisa-cli) | The CLI host — install this to run Lisa |
| [lisa-go](https://github.com/Lisa-Harness/lisa-go) | Go Connector SDK for first-party MCP servers and host/embed tooling |
| [`lisa-pack-*` repositories](https://github.com/orgs/Lisa-Harness/repositories?q=lisa-pack) | One repository and PyPI distribution per capability pack |

Packs add shell execution, sandboxing, web search providers, memory backends,
document formats, and more. Installation does not imply activation: session
selection and host policy decide what the agent can see. See the
[external pack registry](https://github.com/Lisa-Harness/lisa-packs).

## Get started

- [Getting started](https://github.com/Lisa-Harness/lisa/blob/main/docs/GETTING_STARTED.md)
- [Documentation index](https://github.com/Lisa-Harness/lisa/blob/main/docs/README.md)
- [Pack authoring guide](https://github.com/Lisa-Harness/lisa/blob/main/docs/PACK_AUTHORING_GUIDE.md)

## Contribute

- [Issues](https://github.com/Lisa-Harness/lisa/issues) — bugs and features, with a minimal reproduction
- [Contributing](https://github.com/Lisa-Harness/lisa/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/Lisa-Harness/lisa/blob/main/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/Lisa-Harness/lisa/blob/main/SECURITY.md) with private vulnerability reporting

## Who's behind Lisa Harness

Lisa is built as a security-first agent runtime: explicit approvals,
inspectable tool calls, and enforceable limits are the discipline of two
decades in identity and privileged-access engineering.

Maintainer: [Adam Migus, The Migus Group](https://github.com/amigus)
([mig.us/adam](https://mig.us/adam))

Framework and pack code is [MIT licensed](https://github.com/Lisa-Harness/lisa/blob/main/LICENSE).