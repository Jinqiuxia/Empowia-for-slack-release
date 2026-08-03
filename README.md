# Empowia for Slack — Downloads

**Empowia for Slack** is a local-first Windows app that backs up your Slack
workspaces to your own PC and turns them into a searchable archive — with an
optional **read-only MCP server** so Claude Desktop, Cursor, Codex, and ChatGPT
can query your Slack history locally.

- Website: **https://empowia.com**
- What it does: https://empowia.com/slack-backup
- Use it in Claude / Cursor (MCP how-to): https://empowia.com/blog/use-your-slack-in-claude-cursor-with-mcp

## Download (portable)

**Latest:** https://github.com/Jinqiuxia/Empowia-for-slack-release/releases/latest/download/Empowia-Portable.zip

Unzip and run `Empowia-for-Slack.exe` — no installer, no admin rights. On first
launch Windows SmartScreen may warn (the download is not code-signed) →
**More info → Run anyway**.

All versions are on the **Releases** tab.

## MCP (Claude, Cursor, Codex, ChatGPT)

Empowia runs an optional **local, read-only** MCP server that exposes your
backed-up Slack: search messages, list workspaces / channels / files, fetch a
message or a whole thread, and pull your extracted to-dos and decisions — 100% on
your machine, nothing leaves your computer. Turn it on in **Settings → MCP** and
copy the generated config into your client. See the
[how-to](https://empowia.com/blog/use-your-slack-in-claude-cursor-with-mcp).
