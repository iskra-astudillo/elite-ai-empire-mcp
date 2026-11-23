# Elite AI Empire MCP

Start with find_servers. A search for calendar gives you the CoHostBnB address. Open the guide in that result to connect the rental workspace.

Use an email-confirmed EliteSSO owner key to open the directory. Search by product, tool name or task. Each result has a connection guide. Try the word calendar. The result points to /mcp/cohostbnb and names three tools. To open a guest message from there, you need a key issued by that rental workspace.

Run this from the repository. Enter your product key when prompted.

```sh
python3 client.py --key-file ./elite-ai-empire.key connect
python3 client.py --key-file ./elite-ai-empire.key list
```

Keep the .key file private. To close the connection, run `python3 client.py --key-file ./elite-ai-empire.key revoke`.

[Connect an MCP app](https://auth.eliteaiempire.com/mcp-docs/elite-ai-empire) · [Server manifest](https://auth.eliteaiempire.com/mcp-docs/elite-ai-empire/server.json)
