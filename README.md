# PersonCraft MCP

Remote MCP server where **your own Claude designs and codes Godot 4 games**. PersonCraft stores the project and its numbered
revisions, lets Claude read and edit the files, runs each revision in an isolated sandbox and returns **real screenshots** to
Claude, generates art, audio and 3D models with credits, and hands you the project as a ZIP.

- Server: `https://personcraft.com/api/mcp` (streamable HTTP, OAuth 2.0)
- Website: https://personcraft.com
- Documentation: https://personcraft.com/en/guias/conectar-claude-mcp
- What a small game costs: https://personcraft.com/en/guias/cuanto-cuesta-juego-pequeno

> The server itself is a hosted service and its source code is not published in this repository. This repository holds the
> public documentation, the registry metadata (`server.json`) and usage examples.

## Connect from Claude

1. Open Claude and go to **Customize → Connectors**.
2. Choose **Add custom connector** and paste `https://personcraft.com/api/mcp`.
3. Press **Connect** and sign in to PersonCraft to authorize.
4. Ask Claude to start a game, for example:

   > Connect to PersonCraft and make me a small 2D platformer for the Web. Quote the credits before asking me to approve any art,
   > and run a test after each revision so you can look at the screenshots.

## Requirements

- A paid Claude plan (Pro or higher), billed by Anthropic.
- A PersonCraft account. Plans start at US$9 a month plus VAT; credits pay for generated art, audio, 3D models and test runs.
- Godot 4.7 on your computer to open and export the project.

## Tools

61 tools, each with a title and a read-only or destructive annotation. They are grouped in the documentation page: project and
design, code editing, drafts, tests and screenshots, your own files, and art/audio/3D generation with credits (always quoted
first and approved by the owner). Names are in Spanish (`personcraft_...`).

## Limits

- Verification covers the Web and Windows exports. Android and iOS builds are exported by you in Godot.
- No multiplayer.
- An automatic test does not judge whether a game is fun: a person has to play it.

## Privacy Policy

Full notice: https://personcraft.com/en/privacidad

- **Data collection:** PersonCraft receives only what Claude sends when it calls a tool (project files, prompts for generation,
  decisions you approve), plus your account email and payment confirmations. It does not read your conversation history,
  Claude's memory or your files.
- **Usage and storage:** projects, revisions and generated assets are private to your account and stored with our hosting and
  database providers. Test frames are checked by moderation before anyone sees them.
- **Third-party sharing:** with service providers needed to run the service (hosting, database, payments, and the AI generation
  you request). They are listed in the privacy notice. We do not sell personal data or use it for advertising.
- **Retention:** you can delete your projects and data from your account. Payment and credit records are kept for audit and
  dispute handling.
- **Contact:** personcraft@zohomail.com

## Support

personcraft@zohomail.com
