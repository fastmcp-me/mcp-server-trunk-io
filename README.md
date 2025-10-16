<!-- markdownlint-disable first-line-heading -->
[![Trunk.io](https://github.com/user-attachments/assets/c98a90ee-439b-4a9c-bb9a-69dc0e7e2c7e)](https://trunk.io)
[![docs](https://img.shields.io/badge/-docs-darkgreen?logo=readthedocs&logoColor=ffffff)][docs]
[![vscode](https://img.shields.io/visual-studio-marketplace/i/trunk.io?color=0078d7&label=vscode&logo=visualstudiocode)][vscode]
[![slack](https://img.shields.io/badge/-slack-611f69?logo=slack)][slack]
[![openssf](https://api.securityscorecards.dev/projects/github.com/trunk-io/trunk-action/badge)](https://api.securityscorecards.dev/projects/github.com/trunk-io/trunk-action)

# Trunk.io MCP Server

Leverage the power of CI Autopilot from your IDE, or the AI application of your choosing

# Use MCP Server

CI Autopilot comes with a [Model Context Protocol (MCP)](https://modelcontextprotocol.io/docs/getting-started/intro) server. AI applications like Claude Code or Cursor can use MCP servers to connect to data sources, tools, and workflows - enabling them to access key information and perform tasks.

### Supported AI applications

The following applications are currently supported: Cursor, Claude Code, Gemini CLI, and GitHub Copilot.


> [!NOTE]
> Gemini Code Assist and Windsurf are not supported due to their limited support for MCP servers

### API

Our MCP server is available at `https://mcp.trunk.io/mcp` and exposes the following tools:

<table><thead><tr><th width="265.30859375">Tool</th><th>Capability</th></tr></thead><tbody><tr><td><a href="https://docs.trunk.io/ci-autopilot/use-mcp-server/mcp-tool-reference/get-root-cause-analysis.md"><code>get-root-cause-analysis</code></a></td><td>Retrieve root cause analysis and fix suggestions</td></tr><tr><td><a href="https://docs.trunk.io/ci-autopilot/use-mcp-server/mcp-tool-reference/set-up-test-uploads.md"><code>setup-trunk-uploads</code></a></td><td>Experimental: Create a setup plan to upload test results</td></tr></tbody></table>

### Authorization

The Trunk MCP server supports the OAuth 2.0 + OpenID Connect standard for MCP authorization.

### Get started

**To get started, configure your AI application to communicate with Trunk's MCP server:**&#x20;

* [Cursor](https://docs.trunk.io/ci-autopilot/use-mcp-server/configuration/cursor-ide.md)
* [GitHub Copilot](https://docs.trunk.io/ci-autopilot/use-mcp-server/configuration/github-copilot-ide.md)
* [Claude Code CLI](https://docs.trunk.io/ci-autopilot/use-mcp-server/configuration/claude-code-cli.md)
* [Gemini CLI](https://docs.trunk.io/ci-autopilot/use-mcp-server/configuration/gemini-cli.md)

---

**Made with ❤️ by the Trunk.io team**

[slack]: https://slack.trunk.io
[docs]: https://docs.trunk.io
[vscode]: https://marketplace.visualstudio.com/items?itemName=Trunk.io
