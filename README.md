# Installation Steps

To install the `add_tool` MCP server in Claude, add this to claude_desktop_config.json:

```json
{
  "mcpServers": {
	"Add Demo":{
		"command": "uvx",
		"args": [
		   "--from",
		   "git+https://github.com/paulchin20/mcpserverexample.git",
		   "mcp-server"
		]
	}
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.