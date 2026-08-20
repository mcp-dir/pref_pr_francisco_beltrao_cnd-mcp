# Instalação detalhada

Prefeitura PR Francisco Beltrão: Certidão Negativa de Débitos é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_pref_pr_francisco_beltrao_cnd`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_pref_pr_francisco_beltrao_cnd` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_pref_pr_francisco_beltrao_cnd` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_pref_pr_francisco_beltrao_cnd` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.pref_pr_francisco_beltrao_cnd` (ou `servers.pref_pr_francisco_beltrao_cnd` no VS Code) do config do cliente e reinicie.
