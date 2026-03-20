# Credos

Share your team's coding best practices with Cursor.

---

## Plugin Setup

This plugin automatically configures the Credos MCP server and rules in your project.

1. Install the Credos plugin
2. Get an API key from your [Credos account](https://credos.dev)
3. Set your API key as a persistent environment variable:

**macOS** (add to `~/.zshrc`):

```sh
echo 'export CREDOS_MCP_API_KEY="your-api-key-here"' >> ~/.zshrc && source ~/.zshrc
```

**Linux** (add to `~/.bashrc`):

```sh
echo 'export CREDOS_MCP_API_KEY="your-api-key-here"' >> ~/.bashrc && source ~/.bashrc
```

**Windows** (PowerShell, run as Administrator):

```powershell
[Environment]::SetEnvironmentVariable("CREDOS_MCP_API_KEY", "your-api-key-here", "User")
```

4. Restart your terminal and Cursor for the changes to take effect
5. Enable the Credos MCP server from Cursor settings

---

## Manual Setup

Prefer to set things up yourself? See the [Cursor integration docs](https://credos.dev/docs/integrations/cursor) for step-by-step instructions to manually configure Credos MCP server.
