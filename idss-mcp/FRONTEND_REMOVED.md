# Frontend removed

The Next.js frontend that was in `idss-mcp/src/` has been removed. Use **YongceLi's original UI** and point it at the backend you need:

- **Original IDSS API** (chat, recommend, session): `idss/api/server.py` → run on port 8000.
- **MCP / e‑commerce API**: `idss-mcp/mcp-server/` → run on port 8001 (`uvicorn app.main:app --port 8001`).

This directory now contains only the MCP backend (`mcp-server/`). No `node_modules` or `.next` are committed.
