Create one new Markdown file in the repository root:

KSoR-MCP-SETTING-FOR-CHATGPT.md

Do not modify any existing files, code, deployment, Auth0, Render, Neon, or secrets.

Write a polished project document combining the completed KSoR Hello World Handbook project summary and the connector authentication instructions.

Include these sections:

1. Title:
   KSoR Hello World Handbook — Authenticated MCP Project

2. Official tutorial:
   https://github.com/panaversity/ksor/blob/main/docs/tutorials/01-hello-world.md

3. Public human website:
   https://ksor-hello-world-handbook-by-azmat-ali.netlify.app/

4. GitHub repository:
   https://github.com/azmataliakbar/KSOR-HELLO-WORLD-HANDBOOK-BY-AZMAT-ALI

5. Protected MCP endpoint:
   https://ksor-handbook-mcp.onrender.com/mcp

6. Project workflow:
   - ChatGPT Plus / ChatGPT Work used for prompts, guidance, MCP configuration, and tests
   - OpenAI Codex used for coding, testing, verification, GitHub commits, and pushes
   - Neon Postgres with pgvector used for the KSoR record
   - Netlify used for the human-facing website
   - Render used for the public MCP server
   - Auth0 OAuth used for protected MCP authentication
   - GitHub used for source control

7. MCP features:
   - Search approved handbook knowledge
   - Retrieve governed documents
   - Return document title and stable ID
   - Require Auth0 OAuth
   - Return “not found” when information is not indexed, rather than using general knowledge

8. Verified example:
   Include the refund-policy result and source:
   Refund policy — knowledge/refund-policy

9. Add this exact connector authentication rule:

   ## Connector Authentication Rule

   This protected KSoR MCP works successfully with both ChatGPT Work and Claude Cowork.

   When adding the MCP connector:

   - Select OAuth / Sign in / Authenticate.
   - Complete the secure Auth0 login when requested.
   - Leave all custom header fields empty.
   - Do not choose No sign-in.
   - Do not add a static bearer token such as Authorization: Bearer disabled-public.

   The MCP receives a secure temporary OAuth access token automatically after authentication.

10. Credits:
   - Tutorial Source: Panaversity KSoR Hello World
   - Learning Support: Sir Zia, Sir Junaid, Ma'am Wania
   - Project Builder / Author: Azmat Ali
   - Tools Used: ChatGPT Work, ChatGPT Plus, OpenAI Codex, KSoR, Neon, Render, Auth0, GitHub, Netlify, and Claude Cowork

Requirements:
- Use clear Markdown headings, short paragraphs, and bullets.
- Keep all technical statements accurate.
- Never include credentials, tokens, secrets, or personal billing information.
- Run a relevant safe check if available.
- Commit only this new file with message:
  docs: add KSoR MCP connector settings guide
- Push to origin/main.
- Report the file path, commit hash, and push result.