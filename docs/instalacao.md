# Instalação detalhada

Atualização Monetária é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_atualizacao-monetaria`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_atualizacao-monetaria` | nenhuma (grátis) |
| Cursor | `https://api.mcp.ai/p_atualizacao-monetaria` | nenhuma |
| VS Code (Copilot) | `https://api.mcp.ai/p_atualizacao-monetaria` | nenhuma |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.atualizacaomonetaria` (ou `servers.atualizacaomonetaria` no VS Code) do config do cliente e reinicie.
