# Sample MCP server and client

To start the inspector on the server, run:

```bash
mcp dev server.py
```

To start the server, run:

```bash
mcp run
```

To start the clients, run:

```bash
python client.py
python client_llm.py
```

## SSE server

Run the SSE server with:

```bash
uvicorn server_sse:app
```

and the inspector with:

```bash
npx @modelcontextprotocol/inspector --cli http://localhost:8000/sse --method tools/list
```
