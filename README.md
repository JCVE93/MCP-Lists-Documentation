# MCP Lists Documentation

A comprehensive collection of Model Context Protocol (MCP) server implementations and curated lists for reference and exploration.

## Repository Structure

This repository is organized into three main directories:

### 📁 official/
Contains the official MCP servers repository maintained by Anthropic:
- **[servers](https://github.com/modelcontextprotocol/servers)** - Reference implementations demonstrating MCP features and the TypeScript/Python SDKs
  - Everything - Reference/test server with prompts, resources, and tools
  - Fetch - Web content fetching and conversion
  - Filesystem - Secure file operations with configurable access controls
  - Git - Tools to read, search, and manipulate Git repositories
  - Memory - Knowledge graph-based persistent memory system
  - Sequential Thinking - Dynamic and reflective problem-solving
  - Time - Time and timezone conversion capabilities

### 📁 community/
Popular community-built MCP servers:

1. **[github-mcp-server](https://github.com/github/github-mcp-server)** - GitHub's official MCP Server for managing issues, PRs, and discussions
2. **[playwright-mcp](https://github.com/microsoft/playwright-mcp)** - Browser automation for testing and scraping
3. **[aws-mcp](https://github.com/awslabs/mcp)** - AWS documentation, billing, service metadata, and more
   - AWS Bedrock KB Retrieval
   - AWS CDK
   - AWS Core
   - AWS Cost Analysis
   - AWS Documentation
   - AWS Nova Canvas
4. **[mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server)** - MongoDB database interactions
5. **[brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server)** - Web search integration via Brave Search API
6. **[postgresql-mcp](https://github.com/neondatabase/mcp-server-neon)** - PostgreSQL database access (Neon serverless Postgres)
7. **[gdrive-mcp-server](https://github.com/felores/gdrive-mcp-server)** - Google Drive integration for file operations
8. **[google-maps-mcp](https://github.com/cablate/mcp-google-map)** - Google Maps API integration
9. **[slack-mcp-server](https://github.com/korotovsky/slack-mcp-server)** - Slack workspace integration

### 📁 curated-lists/
Comprehensive lists of MCP servers from the community:

1. **[awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)** - Curated list of MCP servers (https://mcpservers.org)
2. **[TensorBlock-awesome-mcp-servers](https://github.com/TensorBlock/awesome-mcp-servers)** - Extensive list covering 7,260+ servers
3. **[appcypher-awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers)** - Another curated collection of MCP servers

## About Model Context Protocol (MCP)

The Model Context Protocol is an open standard that enables seamless integration between AI applications and external data sources. MCP servers provide a standardized way to expose tools, resources, and prompts to AI models.

## Usage

Each cloned repository contains its own documentation, installation instructions, and usage examples. Refer to the individual repository READMEs for specific setup and configuration details.

## Notes

- These repositories are cloned as Git submodules for documentation and reference purposes
- Each server may have different requirements (API keys, credentials, etc.)
- Check individual repository documentation for:
  - Installation requirements
  - Configuration steps
  - Usage examples
  - API limitations

## Resources

- [Model Context Protocol Documentation](https://modelcontextprotocol.io/)
- [MCP Servers Registry](https://mcpservers.org/)
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk)
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)

## Contributing

This is a documentation repository. To contribute to individual MCP servers, please visit their respective repositories listed above.
