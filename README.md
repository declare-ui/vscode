<p align="left">
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/d51c038f-7822-4ee4-beb8-f438894f7736#gh-light-mode-only" />
    <img width="1280" height="192" alt="DeclareUI" src="https://github.com/user-attachments/assets/44918531-3b1b-4ace-bca0-db0ea99f8bc8#gh-dark-mode-only" />
</p>

# DeclareUI for VS Code

VS Code extension — YAML autocomplete, inline preview, AI-assisted editing, and multi-target component preview.

---

## Features

- **Schema-aware autocomplete** — intelligent suggestions for `.ui.yaml` component files
- **Inline preview** — see your component rendered without leaving the editor
- **Multi-target preview** — preview how your component looks in React, Vue, Svelte, etc.
- **Validation** — real-time error highlighting and diagnostics
- **AI-assisted editing** — works with the DeclareUI MCP server for natural language component creation
- **Go to definition** — navigate between component references
- **Snippets** — quick scaffolding for common component patterns

## Installation

Search for **DeclareUI** in the VS Code Extensions Marketplace, or:

```bash
code --install-extension declareui.declareui-vscode
```

## Usage

Open any `.ui.yaml` file and the extension activates automatically. Use the command palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) to access:

- `DeclareUI: Preview Component` — open the live preview panel
- `DeclareUI: Build Component` — compile to target frameworks
- `DeclareUI: Validate` — check your component against the schema
- `DeclareUI: New Component` — scaffold a new component from a template

## Related packages

| Package | Description |
|:--------|:------------|
| [`@declareui/core`](https://github.com/declare-ui/core) | Parser, AST, and code generators |
| [`@declareui/mcp`](https://github.com/declare-ui/mcp) | MCP server for AI agents |
| [`@declareui/components`](https://github.com/declare-ui/components) | Pre-built component library |

## Contributing

See [CONTRIBUTING.md](https://github.com/declare-ui/.github/blob/main/CONTRIBUTING.md) for guidelines.

## License

MIT
