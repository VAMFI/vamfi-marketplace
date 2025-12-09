# VAMFI Plugin Marketplace

High-quality, research-grounded Claude Code plugins from VAMFI.

## Installation

Add the VAMFI marketplace to Claude Code:

```bash
/plugin marketplace add VAMFI/vamfi-marketplace
```

Then browse and install plugins:

```bash
/plugin menu
```

Or install directly:

```bash
/plugin install skill-forge@vamfi-plugins
```

## Available Plugins

| Plugin | Description | Category |
|--------|-------------|----------|
| [skill-forge](https://github.com/VAMFI/skill-forge) | Autonomously create research-grounded Claude Code skills with verified documentation | Development |

## Plugin Philosophy

All VAMFI plugins follow these principles:

1. **Research-First** — Fetch official documentation before generating anything
2. **Source Verification** — Every fact is traced to authoritative sources
3. **Citation Included** — Full source documentation with URLs and dates
4. **Quality Over Quantity** — Fewer plugins, higher standards

## Adding Your Plugin

Want to add a plugin to the VAMFI marketplace?

1. Ensure it follows the research-first philosophy
2. Include proper source citations
3. Submit a PR to this repository

## Marketplace Structure

```
vamfi-marketplace/
├── .claude-plugin/
│   └── marketplace.json    # Plugin catalog
├── plugins/                # Local plugins (optional)
└── README.md
```

## How It Works

Users add the marketplace once:
```bash
/plugin marketplace add VAMFI/vamfi-marketplace
```

Then they can install any plugin from our catalog. Plugins can be:
- **Local**: Stored in `./plugins/` directory
- **External**: Referenced from other GitHub repos (like skill-forge)

## License

MIT

## Links

- [VAMFI GitHub](https://github.com/VAMFI)
- [skill-forge](https://github.com/VAMFI/skill-forge)
