### Hey, I'm Fran 👋

I build tools for Final Fantasy XIV — mostly Dalamud plugins that take the tedium out of crafting, retainers, and the market board — plus the plumbing that lets AI agents help develop them safely. Based in Ontario. Built heavily with AI assistance, fuckin sue me.
**Try it live:** [xivcraftarchitect.com](https://xivcraftarchitect.com) — build a craft list, get prices & market data + step-by-step shopping plans across worlds.

#### Plugins

Install any of these by adding my repo in Dalamud (`/xlsettings` → Experimental → Custom Plugin Repositories):

```
https://raw.githubusercontent.com/FranFkntastic/DalamudPlugins/main/pluginmaster.json
```

| | |
|---|---|
| [**MarketMafioso**](https://github.com/FranFkntastic/MarketMafioso) | It does a fuckin lot, honestly. Mostly reimplementations of dropbox, workshoppa, and a bunch of inventory management tooling used by... |
| [**Quartermaster**](https://github.com/FranFkntastic/Quartermaster) | Keep target stock levels across your retainers, see what's short, and move items with a review step before anything happens. |
| [**Sapphire Avenue Assistant**](https://github.com/FranFkntastic/SapphireAvenueAssistant) | Bridges a Discord channel and an in-game cross-world linkshell, without ever posting into the wrong chat. |

#### Under the hood

- [**Franthropy**](https://github.com/FranFkntastic/Franthropy) — the shared library all of the above are built on: a filter language, FFXIV item/ownership vocabulary, and inventory persistence.
- [**DalamudAgentBridge**](https://github.com/FranFkntastic/DalamudAgentBridge) — an MCP server and local dashboard that let coding agents inspect and drive a running plugin, with auth, a loopback-only boundary, and frame-validated UI control.

#### Elsewhere

Occasional Minecraft modding (NeoForge) — e.g. [astruct-raft-tuah](https://github.com/FranFkntastic/astruct-raft-tuah), an async floating-settlement engine.
