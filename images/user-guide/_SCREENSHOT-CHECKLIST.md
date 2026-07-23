# Screenshot capture checklist — User Guide

Every image in the guide is now a **`.png`** (the pages reference `.png`), and this folder holds a **labelled placeholder PNG** for each one. To swap in a real screenshot, you only need to:

1. Log into the app (e.g. `suite.sundaypyjamas.com`) with a **dummy workspace** that has sample data (a chat, an app, a report, a couple of uploaded docs) so screens aren't empty.
2. Navigate to the screen listed below and capture it.
3. Save/overwrite the PNG into this folder using the **exact base name** shown (e.g. `first-chat-empty.png`).

That's it — **no `.mdx` edits needed**. The page already points at that filename, so dropping the real PNG over the placeholder upgrades the page automatically.

> Real screenshots weren't fully auto-captured: the browser tool's `save_to_disk` writes to a store the assistant can't read, and the FireShot extension only fires on a manual trigger whose button sits outside the automated page area. `agents-tab-overview.png` is already a **real** capture of the Agents tab; the rest are placeholders awaiting the real shot.

| Image base name | App route / where to find it | What to capture |
|---|---|---|
| `create-account-login` | `/login` | Login screen, Sign up tab visible |
| `create-account-signin` | `/login` | Sign in form (email + password) |
| `workspace-tour-overview` | `/workspace/[id]/dashboard` | Whole screen: sidebar + top bar + main area |
| `workspace-tour-topbar` | any workspace page | Top-right: workspace switcher, bell, profile |
| `workspace-tour-command` | press Ctrl/Cmd+K | Command search menu open |
| `first-chat-empty` | `/workspace/[id]/chat` | Empty chat with the message box |
| `first-chat-answer` | `/workspace/[id]/chat` | A user message + AI reply |
| `choosing-models-picker` | chat, model dropdown open | The model picker list |
| `reports-home` | `/workspace/[id]/insights/reports` (Reports) | Reports list + New report button |
| `reports-generated` | a generated report | A finished report with sections |
| `images-playground` | `/workspace/[id]/images/playground` | Description box + Generate button |
| `images-result` | images, after generating | A generated image shown |
| `knowledge-upload` | app → RAG/Data, or Storage | The upload area |
| `knowledge-answer` | chat/app answering from a doc | Answer citing an uploaded doc |
| `build-app-list` | `/workspace/[id]/platform/apps` | Apps list + New app button |
| `build-app-playground` | app → playground | Test conversation in the playground |
| `integrations-list` | `/workspace/[id]/integrations` | Gallery of connectors |
| `sharing-button` | any report/chat, Share button | Share button + panel |
| `sharing-link` | share panel | The copyable link |
| `agents-tab-overview` | `/workspace/[id]/agents` | The Agents tab with the Core Agent |
| `agents-tab-layout` | `/workspace/[id]/agents` | Session list + chat tabs + preview panel |
| `agents-tab-picker` | Agents tab, agent picker open | Core Agent / custom agents dropdown |
| `agents-capabilities-tools` | Agents tab, an agent using a tool | Tool step shown mid-task |
| `agents-capabilities-artifact` | Agents tab, agent created a file | File open in the right preview panel |
| `agents-configure-overview` | Agents tab → gear/settings | Core Agent configuration screen |
| `agents-run-chat` | Agents tab | Giving the agent a task |
| `agents-run-steps` | Agents tab, a run | List of steps performed |
| `agents-share` | Agents tab, session share panel | Share link for a session |
| `agents-create-assistant-start` | `/workspace/[id]/platform/assistants/create` | Create Assistant start |
| `agents-create-assistant-instructions` | assistant create form | Name + instructions fields |
| `agents-create-assistant-test` | assistant preview | Preview test chat |
| `agents-managed-create` | `/workspace/[id]/platform/managed-agents/create` | Create managed agent |
| `agents-managed-run` | managed agent run | Run steps / progress |
| `team-members` | `/workspace/[id]/settings/members` | Members list + Invite |
| `team-usage` | `/workspace/[id]/settings/token-usage` (Usage) | Credits used / remaining |
