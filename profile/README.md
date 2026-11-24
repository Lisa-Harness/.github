# Lisa Harness

- **Want to run Lisa?** [Install lisa-cli](https://github.com/Lisa-Harness/lisa-cli#install)! 🚀
- **Like the project?** [star the repo](https://github.com/Lisa-Harness/lisa)! ⭐

Lisa is an AI agent harness and MCP-based runtime built around a flexible tool-enabled turn loop.
Running it requires a host like [lisa-cli](https://github.com/Lisa-Harness/lisa-cli).
The host supplies a transport,
LLM/model access,
and bootstraps the MCP and proxy servers.
It also loads packs that supply servers, tools and workflows.

## Key features

- **Intent-driven modes** reset the system prompt and control which tools are available.
- **Effect receipt collection** enables the harness to verify the model deliverables.
- **Event-driven model routing** changes the model dynamically based on runtime state.
- **Harness-managed model context** that does not summarize or use lossy compaction.
- **Harness-enforced limits** on iteration, token and tool-calls.

## Components

| Repository | Role |
| --- | --- |
| [lisa](https://github.com/Lisa-Harness/lisa) | Framework, kernel, SDK, and runtime — start here to understand or contribute to the project |
| [lisa-cli](https://github.com/Lisa-Harness/lisa-cli) | Recommended host for installing and running Lisa |
| [lisa-go](https://github.com/Lisa-Harness/lisa-go) | *Experimental* Go connector SDK, MCP servers and host/embed tooling |
| [lisa-pack-*](https://github.com/orgs/Lisa-Harness/repositories?q=lisa-pack) | Loadable capability packs |

## Docs

See the [documentation index](https://github.com/Lisa-Harness/lisa/blob/main/docs/README.md),
[getting started guide](https://github.com/Lisa-Harness/lisa/blob/main/docs/GETTING_STARTED.md),
or [pack authoring guide](https://github.com/Lisa-Harness/lisa/blob/main/docs/PACK_AUTHORING_GUIDE.md).

## Contribute

- [Issues](https://github.com/Lisa-Harness/lisa/issues) — bugs and features, with a minimal reproduction
- [Contributing](https://github.com/Lisa-Harness/lisa/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/Lisa-Harness/lisa/blob/main/CODE_OF_CONDUCT.md)
- [Security policy](https://github.com/Lisa-Harness/lisa/blob/main/SECURITY.md) with private vulnerability reporting

## Who's behind Lisa Harness

[Adam Migus](https://mig.us/adam)
([GitHub](https://github.com/amigus))
created and released Lisa under the
[MIT license](https://github.com/Lisa-Harness/lisa/blob/main/LICENSE).
