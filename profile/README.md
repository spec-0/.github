<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/spec-0/.github/main/profile/spec0-logo-dark.svg">
    <img alt="Spec0" src="https://raw.githubusercontent.com/spec-0/.github/main/profile/spec0-logo-light.svg" width="200">
  </picture>
</h1>

<p align="center"><b>Every API in your company, in one place, for people and for coding agents.</b></p>

Spec0 keeps your organisation's OpenAPI specs in one catalog. Teams publish from CI,
and everyone can search, read reviews and changelogs, try an API against a hosted
mock, and see who depends on what. Coding agents get the same catalog through MCP, so
they read the real contract instead of guessing. The AI features run on the OpenAI or
Anthropic account you choose.

## Open source

These are the parts of Spec0 you can run yourself. They work without a Spec0 account.

| Project | What it is |
|---|---|
| [**studio**](https://github.com/spec-0/studio) | A desktop API client built around your OpenAPI spec, for macOS, Windows and Linux. Requests come from the spec, and every JSON response is checked against it. |
| [**cli**](https://github.com/spec-0/cli) | The `spec0` command line: publish specs from CI, lint them, check for breaking changes, and install the MCP server for your coding agent. |
| [**mock-server**](https://github.com/spec-0/mock-server) | A self-hosted OpenAPI mock server with response variants, schema validation and a web UI. Runs anywhere Java or Docker does. |
| [**schema-graph**](https://github.com/spec-0/schema-graph) | A small library that turns the schemas in an OpenAPI spec into a graph, with an optional React view. |
| [**internet-public-api**](https://github.com/spec-0/internet-public-api) | A curated mirror of official OpenAPI specs for well-known public APIs, published to the [Spec0 public registry](https://app.spec0.io/registry). |

## Hosted platform

The catalog, reviews, changelogs, hosted mocks, subscriber contracts and the
organisation-wide MCP server are a hosted service.

[Website](https://www.spec0.io) · [Docs](https://docs.spec0.io) · [Public API registry](https://app.spec0.io/registry) · [Book a demo](https://cal.eu/spec0/demo)

## Feedback

Questions and ideas are welcome in each project's Discussions or Issues. To report a
security problem, please use the project's private vulnerability reporting instead
of a public issue.
