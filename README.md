# Awesome MCP Servers ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A curated list of awesome Model Context Protocol (MCP) servers. MCP is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

<br />

## Supported Clients

|                                                                                                 | MCP Host                                         | Documentation                                             |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------ | --------------------------------------------------------- |
| [<div align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Claude_AI_logo.svg" height="20"/></div>](https://www.claudedesktop.com/) | [Claude Desktop](https://www.claudedesktop.com/) | [Quick Start](https://modelcontextprotocol.io/quickstart) |
| [<div align="center"><img src="https://zed.dev/_next/static/media/zed-logo.11b2d662.png" height="20"/></div>](https://zed.dev/) | [Zed Editor](https://zed.dev/) | [Zed MCP Extensions](https://zed.dev/blog/mcp) |
| [<div align="center"><img src="https://sourcegraph.com/sourcegraph-logo.svg" height="20"/></div>](https://sourcegraph.com/cody) | [Sourcegraph Cody](https://sourcegraph.com/cody) | [Trying Cody with MCP](https://sourcegraph.com/blog/cody-supports-anthropic-model-context-protocol) |

<br />

## Server Implementations

- 📂 - [File Systems](#file-systems)
- 🔄 - [Version Control](#version-control)
- ☁️ - [Cloud Storage](#cloud-storage)
- 🗄️ - [Databases](#databases)
- 💬 - [Communication](#communication)
- 📊 - [Monitoring](#monitoring)
- 🔍 - [Search & Web](#search-web)
- 🗺️ - [Location Services](#location-services)
- 🧠 - [Memory Systems](#memory-systems)
- ⚡ - [Cloud Platforms](#cloud-platforms)

<br />

## Tools & Utilities

See [Helpful Tools & Utilities](#helpful-tools-&-utilities) section for tools to help manage, configure, and work with MCP servers.

<br />

## 📂 <a name="file-systems"></a>File Systems <sup>[top⇈](#server-implementations)</sup>

> Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

- [@modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Direct local file system access.
- [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) - Golang implementation for local file system access.

<br />

## 🔄 <a name="version-control"></a>Version Control <sup>[top⇈](#server-implementations)</sup>

> Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- [@modelcontextprotocol/server-github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - GitHub API integration for repository management, PRs, issues, and more
- [@modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab platform integration for project management and CI/CD operations
- [@modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Direct Git repository operations including reading, searching, and analyzing local repositories

<br />

## ☁️ <a name="cloud-storage"></a>Cloud Storage <sup>[top⇈](#server-implementations)</sup>

> Access and manage files stored in cloud storage platforms. Enables searching, reading, and organizing cloud-stored documents and data.

- [@modelcontextprotocol/server-gdrive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive integration for file access, search, and management

<br />

## 🗄️ <a name="databases"></a>Databases <sup>[top⇈](#server-implementations)</sup>

> Secure database access with schema inspection capabilities. Enables querying and analyzing data while maintaining read-only safety by default.

- [@modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database integration with schema inspection and query capabilities
- [@modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database operations with built-in analysis features

<br />

## 💬 <a name="communication"></a>Communication <sup>[top⇈](#server-implementations)</sup>

> Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

- [@modelcontextprotocol/server-slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Slack workspace integration for channel management and messaging

<br />

## 📊 <a name="monitoring"></a>Monitoring <sup>[top⇈](#server-implementations)</sup>

> Access and analyze application monitoring data. Enables AI models to review error reports and performance metrics.

- [@modelcontextprotocol/server-sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Sentry.io integration for error tracking and performance monitoring

<br />

## 🧠 <a name="memory-systems"></a>Memory Systems <sup>[top⇈](#server-implementations)</sup>

> Persistent memory storage using knowledge graph structures. Enables AI models to maintain and query structured information across sessions.

- [@modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory system for maintaining context

<br />

## 🔍 <a name="search-web"></a>Search & Web <sup>[top⇈](#server-implementations)</sup>

> Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- [@modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation for web scraping and interaction
- [@modelcontextprotocol/server-brave-search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Web search capabilities using Brave's Search API
- [@modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Efficient web content fetching and processing for AI consumption

<br />

## 🗺️ <a name="location-services"></a>Location Services <sup>[top⇈](#server-implementations)</sup>

> Geographic and location-based services integration. Enables access to mapping data, directions, and place information.

- [@modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Google Maps integration for location services, routing, and place details

<br />

## ⚡ <a name="cloud-platforms"></a>Cloud Platforms <sup>[top⇈](#server-implementations)</sup>

> Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

- [Cloudflare MCP Server](https://github.com/cloudflare/mcp-server-cloudflare) - Integration with Cloudflare services including Workers, KV, R2, and D1

<br />


# Tools & Utilities

> Tools that help manage, configure, and work with MCP servers. These utilities simplify the installation process and improve the user experience.

### Server Managers

- [mcp-get](https://github.com/michaellatman/mcp-get) - CLI tool for installing and managing MCP servers. Simplifies server installation and configuration for Claude Desktop.
  - Supports NPM-based servers
  - Automatic configuration generation
  - Easy server management

<br />


Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

---

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Stephen Akinyemi](https://github.com/appcypher) has waived all copyright and related or neighboring rights to this work.
