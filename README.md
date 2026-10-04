# cntxt-labs

The distributable Claude Code plugin marketplace for cntxt-labs.

## Install

Add the marketplace once, then install the plugins you want:

```sh
/plugin marketplace add nimishph/cntxt-labs
/plugin install medha@cntxt-labs
/plugin install anvesa@cntxt-labs
/plugin install yojana@cntxt-labs
```

The same steps work from the shell:

```sh
claude plugin marketplace add nimishph/cntxt-labs
claude plugin install medha@cntxt-labs
```

## Plugins

| Plugin | What it brings |
| --- | --- |
| **medha** | Evidential memory: MCP server, agent skill, and slash commands for rules, recipes and tools. Needs `medha init` in the project. |
| **anvesa** | Find code by meaning and by structure: semantic search, WQL structural queries, call graph, offline over MCP and the CLI. |
| **yojana** | Plans as checkable contracts: claims verified against the code, suggested changes, live review pages, and decisions on beads that a person finalizes. |

## Versioning

Entries track the default branch of each product repository (anvesa tracks
`feat/claude-plugin` until that branch merges). Stable releases are tagged in the product
repositories themselves; this marketplace only says where to fetch from.

Alpha/beta builds are not distributed here. They come from a local, machine-only marketplace
(`cntxt-labs-dev`) that loads the workspace working trees in place.
