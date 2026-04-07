### Home automation + AI agents on NVIDIA DGX Spark

Building smart home systems and AI tools in Finland. Everything runs locally on a DGX Spark GB10 -- no cloud dependencies for core functionality.

#### What I build

**AI Agent Tools**
- [nemoclaw-skill](https://github.com/Koneisto/nemoclaw-skill) -- Claude Code skill for NVIDIA NemoClaw sandboxed agents. 14 operational rules, automated recovery, Signal bridge hardening.
- [no-as-a-service](https://github.com/Koneisto/no-as-a-service) -- 1,000+ creative rejection responses. REST API + MCP server.

**MCP Servers**
- [mcp-weather](https://github.com/Koneisto/mcp-weather) -- European weather from 6 sources. No API keys needed.
- [HomeAssistant-Light-MCP](https://github.com/Koneisto/HomeAssistant-Light-MCP) -- Save and control HA light scenes via MCP.

**Home Assistant Integrations**
- [ruuvihome](https://github.com/Koneisto/ruuvihome) -- BLE-to-MQTT bridge for Ruuvi sensors with HA auto-discovery.
- [home-assistant-toshiba_ac](https://github.com/Koneisto/home-assistant-toshiba_ac) -- Toshiba AC integration for Home Assistant.

**Node-RED**
- [dashboard2-chart-persistence](https://github.com/Koneisto/dashboard2-chart-persistence) -- Data persistence for FlowFuse dashboard charts.

#### Stack

DGX Spark GB10 | Home Assistant | Node-RED | n8n | NemoClaw/OpenClaw | Qwen3.5-35B (local vLLM) | OpenMemory | Signal
