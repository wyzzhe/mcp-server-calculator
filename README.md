# Calculator MCP Server

The Calculator MCP Server is a [Model Context Protocol (MCP)](https://modelcontextprotocol.io/introduction) server that specifically designed to perform basic arithmetic operations, including addition, subtraction, multiplication, and division. 

## Installation


### Usage with VS Code

```json
{
  "mcp": {
    "servers": {
      "github": {
        "command": "docker",
        "args": [
          "run",
          "-i",
          "--rm",
          "ghcr.io/wyzzhe/test-go-mcp-server:v1.0.1"
        ]
      }
    }
  }
}
```

### Usage with Claude Desktop
```json
{
  "mcpServers": {
    "github": {
      "command": "docker",
      "args": [
        "run",
        "-i",
        "--rm",
        "ghcr.io/wyzzhe/test-go-mcp-server:v1.0.1"
      ]
    }
  }
}
```
## Tool Configuration

### Available Toolsets

The following sets of tools are available (all are on by default):

| Toolset                      | Description                                                                              |
| -----------------------      | ---------------------------------------------------------------------------------------- |
| `calculator`                 | perform basic arithmetic operations(addition, subtraction, multiplication, and division) |

## Vscode Example
![这是一个示例图片](https://249595.xyz/ss/20250523/5c3442d0d28141d0ecd9195940d96312.png "示例图片")