# Plugin de Bravilo

Un solo paquete para Claude y para ChatGPT/Codex. Trae el conector MCP de Bravilo ya configurado y una skill que enseña a usarlo. El usuario instala, inicia sesión en Bravilo y listo.

## Instalar en Claude

```bash
claude plugin marketplace add bravilo-ai/bravilo-plugin
claude plugin install bravilo@bravilo
```

## Instalar en ChatGPT / Codex

```bash
codex plugin marketplace add bravilo-ai/bravilo-plugin
```

Después, `/plugins` y elegir Bravilo.

## Archivos

| Archivo | Para quién |
|---|---|
| `.claude-plugin/plugin.json`, `.mcp.json`, `.claude-plugin/marketplace.json` | Claude |
| `plugin.json`, `mcp.json`, `.agents/plugins/marketplace.json` | ChatGPT / Codex |
| `skills/`, `assets/` | Los dos |
