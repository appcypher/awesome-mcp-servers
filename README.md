# Awesome MCP Servers ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A curated list of awesome Model Context Protocol (MCP) servers. MCP is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

<br />

## Supported Clients

|                                                                                                                                                                                 | MCP Host                                         | Documentation                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | --------------------------------------------------------------------------------------------------- |
| [<div align="center"><img src="https://claude.ai/favicon.ico" height="20"/></div>](https://www.claudedesktop.com/)                                                              | [Claude Desktop](https://www.claudedesktop.com/) | [Quick Start](https://modelcontextprotocol.io/quickstart)                                           |
| [<div align="center"><img src="https://zed.dev/_next/static/media/zed-logo.11b2d662.png" height="20"/></div>](https://zed.dev/)                                                 | [Zed Editor](https://zed.dev/)                   | [Zed MCP Extensions](https://zed.dev/blog/mcp)                                                      |
| [<div align="center"><img src="https://storage.googleapis.com/sourcegraph-assets/docs/images/cody/cody-logomark-default.svg" height="20"/></div>](https://sourcegraph.com/cody) | [Sourcegraph Cody](https://sourcegraph.com/cody) | [Trying Cody with MCP](https://sourcegraph.com/blog/cody-supports-anthropic-model-context-protocol) |

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
- 📱 - [Social](#social)

<sup><details>

<summary>Legend</summary>

- <sup>⭐</sup> Official protocol implementation
- <sup>1</sup> First implementation (when multiple implementations exist)
- <sup>2</sup> Second implementation
- <sup>3</sup> Third implementation
- <sup>n</sup> Subsequent implementations
</details></sup>

<br />

## Tools & Utilities

See [Helpful Tools & Utilities](#helpful-tools-&-utilities) section for tools to help manage, configure, and work with MCP servers.

<br />

## 📂 <a name="file-systems"></a>File Systems <sup><small>[top⇈](#server-implementations)</small></sup>

> Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

- <img src="https://cdn.simpleicons.org/files/4A90E2" height="20"/> [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) <sup><sup>1</sup></sup> - Direct local file system access
- <img src="https://cdn.simpleicons.org/files/4A90E2" height="20"/> [FileSystem](https://github.com/mark3labs/mcp-filesystem-server) <sup><sup>2</sup></sup> - Golang implementation for local file system access

<br />

## 🔄 <a name="version-control"></a>Version Control <sup><small>[top⇈](#server-implementations)</small></sup>

> Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

- <img src="https://cdn.simpleicons.org/github/181717" height="20"/> [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - GitHub API integration for repository management, PRs, issues, and more
- <img src="https://cdn.simpleicons.org/gitlab/FC6D26" height="20"/> [GitLab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab platform integration for project management and CI/CD operations
- <img src="https://cdn.simpleicons.org/git/F05032" height="20"/> [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Direct Git repository operations including reading, searching, and analyzing local repositories
- <img src="https://cdn.simpleicons.org/phabricator/4A5F88" height="20"/> [Phabricator](https://github.com/baba786/phabricator-mcp-server) - Phabricator API integration for repository and project management

<br />

## ☁️ <a name="cloud-storage"></a>Cloud Storage <sup><small>[top⇈](#server-implementations)</small></sup>

> Access and manage files stored in cloud storage platforms. Enables searching, reading, and organizing cloud-stored documents and data.

- <img src="https://cdn.simpleicons.org/googledrive/4285F4" height="20"/> [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - Google Drive integration for file access, search, and management

<br />

## 🗄️ <a name="databases"></a>Databases <sup><small>[top⇈](#server-implementations)</small></sup>

> Secure database access with schema inspection capabilities. Enables querying and analyzing data while maintaining read-only safety by default.

- <img src="https://cdn.simpleicons.org/postgresql/4169E1" height="20"/> [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - PostgreSQL database integration with schema inspection and query capabilities
- <img src="https://cdn.simpleicons.org/sqlite/003B57" height="20"/> [SQLite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - SQLite database operations with built-in analysis features
- <img src="https://cdn.simpleicons.org/duckdb/FFF000" height="20"/> [DuckDB](https://github.com/ktanaka101/mcp-server-duckdb) - DuckDB database integration with schema inspection and query capabilities

<br />

## 💬 <a name="communication"></a>Communication <sup><small>[top⇈](#server-implementations)</small></sup>

> Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

- <img src="https://cdn.simpleicons.org/slack/4A154B" height="20"/> [Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Slack workspace integration for channel management and messaging

<br />

## 📊 <a name="monitoring"></a>Monitoring <sup><small>[top⇈](#server-implementations)</small></sup>

> Access and analyze application monitoring data. Enables AI models to review error reports and performance metrics.

- <img src="https://cdn.simpleicons.org/sentry/362D59" height="20"/> [Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Sentry.io integration for error tracking and performance monitoring
- <img src="https://raygun.com/favicon.ico" height="20"/> [Raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - Raygun API V3 integration for crash reporting and real user monitoring

<br />

## 🧠 <a name="memory-systems"></a>Memory Systems <sup><small>[top⇈](#server-implementations)</small></sup>

> Persistent memory storage using knowledge graph structures. Enables AI models to maintain and query structured information across sessions.

- <img src="https://icons.iconarchive.com/icons/iconsmind/outline/24/Brain-2-icon.png" height="20"/> [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory system for maintaining context
- <img src="https://cdn.simpleicons.org/obsidian/7C3AED" height="20"/> [Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) <sup><sup>1</sup></sup> - Obsidian vault integration with tools for file management, search, and content manipulation
- <img src="https://cdn.simpleicons.org/obsidian/7C3AED" height="20"/> [Obsidian](https://github.com/calclavia/mcp-obsidian) <sup><sup>2</sup></sup> - Alternative implementation for reading and searching Markdown notes
- <img src="https://cdn.simpleicons.org/notion/000000" height="20"/> [Notion](https://github.com/danhilse/notion_mcp) <sup><sup>1</sup></sup> - Notion API integration for managing personal todo lists and notes
- <img src="https://cdn.simpleicons.org/notion/000000" height="20"/> [Notion](https://github.com/suekou/mcp-notion-server) <sup><sup>2</sup></sup> - Alternative implementation for Notion API integration

<br />

## 🔍 <a name="search-web"></a>Search & Web <sup><small>[top⇈](#server-implementations)</small></sup>

> Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

- <img src="https://cdn.simpleicons.org/puppeteer/40B5A4" height="20"/> [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation for web scraping and interaction
- <img src="https://cdn.simpleicons.org/brave/FB542B" height="20"/> [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Web search capabilities using Brave's Search API
- <img src="https://cdn.simpleicons.org/curl/073551" height="20"/> [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Efficient web content fetching and processing for AI consumption
- <img src="https://cdn.simpleicons.org/kagi/4173FF" height="20"/> [Kagi Search](https://github.com/ac3xx/mcp-servers-kagi) - TypeScript-based MCP server that integrates the Kagi Search API
- <img src="https://www.tryleap.ai/assets/integrations/exa.svg" height="20"/> [Exa Search](https://github.com/exa-labs/exa-mcp-server) - Integration with Exa AI Search API for real-time web information retrieval
- <img src="https://cdn.simpleicons.org/newyorktimes" height="20"/> [NYTimes](https://github.com/angheljf/nyt) - Search articles using the NYTimes API
- <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7e/Vector_search_icon.svg/800px-Vector_search_icon.svg.png" height="20"/> [Search1API](https://github.com/fatwang2/search1api-mcp) - Search via search1api (requires paid API key)
- <img src="https://tavily.com/favicon.ico" height="20"/> [Tavily](https://github.com/Tomatio13/mcp-server-tavily) - Tavily AI search API integration
- <img src="https://cdn.simpleicons.org/arxiv/B31B1B" height="20"/> [ArXiv](https://github.com/blazickjp/arxiv-mcp-server) - Search ArXiv research papers

<br />

## 🗺️ <a name="location-services"></a>Location Services <sup><small>[top⇈](#server-implementations)</small></sup>

> Geographic and location-based services integration. Enables access to mapping data, directions, and place information.

- <img src="https://cdn.simpleicons.org/googlemaps/4285F4" height="20"/> [Google Maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Google Maps integration for location services, routing, and place details

<br />

## ⚡ <a name="cloud-platforms"></a>Cloud Platforms <sup><small>[top⇈](#server-implementations)</small></sup>

> Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

- <img src="https://cdn.simpleicons.org/cloudflare/F38020" height="20"/> [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) - Integration with Cloudflare services including Workers, KV, R2, and D1
- <img src="https://cdn.simpleicons.org/kubernetes/326CE5" height="20"/> [Kubernetes](https://github.com/strowk/mcp-k8s-go) - Kubernetes cluster operations through MCP

<br />

## 📱 <a name="social"></a>Social <sup><small>[top⇈](#server-implementations)</small></sup>

> Integration with social media platforms and content sharing services. Enables interaction with social networks, media platforms, and content creation tools.

- <img src="https://cdn.simpleicons.org/bluesky/0085FF" height="20"/> [BlueSky](https://github.com/keturiosakys/bluesky-context-server) - Bluesky API integration for querying and searching feeds and posts
- <img src="https://cdn.simpleicons.org/youtube/FF0000" height="20"/> [YouTube](https://github.com/anaisbetts/mcp-youtube) <sup><sup>1</sup></sup> - YouTube integration using yt-dlp for subtitle downloading and video analysis
- <img src="https://cdn.simpleicons.org/youtube/FF0000" height="20"/> [YouTube](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) <sup><sup>2</sup></sup> - Alternative implementation for fetching YouTube subtitles and transcripts
- <img src="https://cdn.simpleicons.org/openai/412991" height="20"/> [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) - Query OpenAI models directly from Claude using MCP protocol
- <img src="https://cdn.simpleicons.org/apple/000000" height="20"/> [Apple Notes](https://github.com/sirmews/apple-notes-mcp) - Read from local Apple Notes database (macOS only)
- <img src="https://cdn.simpleicons.org/coinmarketcap/17181B" height="20"/> [CoinMarket](https://github.com/anjor/coinmarket-mcp-server) - Coinmarket API integration for cryptocurrency data
- <img src="https://cdn.simpleicons.org/notion/000000" height="20"/> [Notion](https://github.com/suekou/mcp-notion-server) - Alternative implementation for Notion API integration
- <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/dna.svg" height="20"/> [Ancestry](https://github.com/reeeeemo/ancestry-mcp) - Read .ged files and genetic data
- <img src="https://cdn.simpleicons.org/shell/4EAA25" height="20"/> [WCGW](https://github.com/rusiaaman/wcgw) - Autonomous shell execution and computer control (Mac)

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
