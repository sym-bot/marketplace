# SYM.BOT plugin marketplace

The official Claude Code plugin marketplace for [SYM.BOT](https://sym.bot) — real-time mesh and collective-intelligence tools built on the [Mesh Memory Protocol (MMP)](https://meshcognition.org/spec/mmp).

## Install

In Claude Code:

```
/plugin marketplace add sym-bot/marketplace
/plugin install <plugin>@sym-bot
```

## Plugins

| Plugin | Description | Source |
|---|---|---|
| [`sym-mesh-channel`](https://github.com/sym-bot/sym-mesh-channel) | Real-time communication and collaboration among Claude Code sessions — agent-to-agent cognitive signals over Bonjour LAN or a WebSocket relay. | [sym-bot/sym-mesh-channel](https://github.com/sym-bot/sym-mesh-channel) |

```
/plugin install sym-mesh-channel@sym-bot
```

Each plugin's code lives in its own repository; this repo is the catalog that lists them. Adding a plugin is a one-line entry here pointing at its source repo, so the `@sym-bot` handle stays stable as the catalog grows.

## License

Apache-2.0 — [SYM.BOT](https://sym.bot).
