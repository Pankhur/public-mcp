# Public MCP Server

A Model Context Protocol (MCP) server implementation.

## Installation

### Using uvx (Recommended)

The easiest way to install and run this MCP server is using `uvx`:

```json
{
  "public-mcp": {
    "command": "uvx",
    "args": [
      "--from",
      "git+https://github.com/Pankhur/public-mcp.git",
      "mcp-server"
    ]
  }
}
```

You can add this configuration to your project or Claude Desktop config to use this MCP server.

### Manual Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Pankhur/public-mcp.git
   cd public-mcp
   ```

2. **Install dependencies**
   ```bash
   pip install -e .
   ```
   
   Alternatively, you can install dependencies using `uv`:
   ```bash
   pip install uv
   uv pip install -e .
   ```

## Usage

After installation, you can run the server with:

```bash
python -m mcpserver
```

## Development

To contribute to this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request