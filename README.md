# Windsurf-MCP

A repository for Windsurf Model Context Protocol (MCP) integration and examples.

## Overview

This repository contains examples, configurations, and documentation for using Model Context Protocol (MCP) with Windsurf. MCP enables AI assistants to access external tools and data sources, enhancing their capabilities and making them more useful for a wide range of tasks.

## Features

- MCP server configurations
- Integration examples
- Documentation and guides
- Sample applications
- Troubleshooting resources

## Getting Started

To get started with Windsurf MCP:

1. Clone this repository
2. Configure your MCP servers in Windsurf
3. Explore the examples provided
4. Implement MCP in your own projects

### Configuration Example

```json
{
  "mcpServers": {
    "github": {
      "command": "npx",
      "args": [
        "-y",
        "@modelcontextprotocol/server-github"
      ],
      "env": {
        "GITHUB_PERSONAL_ACCESS_TOKEN": "your_github_token_here"
      }
    }
  }
}
```

## MCP Servers

This repository includes examples for various MCP servers including:

- GitHub - For repository management and code operations
- Linear - For project and issue tracking
- Firecrawl - For web scraping and data extraction
- And more...

## Use Cases

- Automate repository management tasks
- Create and manage project issues
- Extract and analyze web data
- Enhance AI assistant capabilities with external tools

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.