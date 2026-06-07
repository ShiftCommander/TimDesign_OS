# Tool Registry

Purpose: track tools, connectors, apps, MCPs, IDEs, models, setup notes, known issues, successful patterns, and fallback routes.

This file helps new AI sessions avoid rediscovering the same setup details.

## Use rule

For any task involving a tool, read the matching entry before asking Timtim for context.

After a useful run, update the entry with status, last successful use, setup notes, known issues, fixes, fallbacks, and recommended prompt patterns.

## Entry template

Tool name
Status: unknown / working / partial / blocked / deprecated
Category: app / connector / MCP / IDE / model / hosting / browser / automation / other
Last verified: YYYY-MM-DD
Used for:
- ...
Known setup:
- ...
Successful patterns:
- ...
Known issues:
- ...
Fallbacks:
- ...
Maintenance notes:
- ...

## Current entries

### ChatGPT

Status: working
Category: app
Last verified: 2026-06-07
Used for:
- strategy
- writing
- repo-connected context work
- stable preference memory
- GitHub connector operations when available

Successful patterns:
- Use ChatGPT memory for stable preferences and durable personal context.
- Use TimDesign_OS for operational knowledge, project state, tools, skills, and cross-agent routing.

Known issues:
- ChatGPT memory alone is too small and too implicit for full operating-system knowledge.

Fallbacks:
- Put durable operational context into this repo.

### GitHub Connector

Status: working
Category: connector
Last verified: 2026-06-07
Used for:
- reading TimDesign_OS
- creating and updating AI context files
- checking repo metadata

Successful patterns:
- Use ShiftCommander/TimDesign_OS as canonical repo.
- Prefer fetch_file before updating existing files.
- Keep write payloads compact and operational.

Known issues:
- Some very directive files may be blocked by connector safety checks.

Fallbacks:
- Retry with calmer wording.
- Split large documents into smaller files.

### Codex

Status: partial
Category: coding agent
Last verified: 2026-06-07
Used for:
- repo-aware implementation
- testing
- autonomous coding tasks
- project handoffs

Successful patterns:
- Start Codex tasks by telling it to read ai_context/os_index.md first.
- Include model and reasoning level in prompts when giving Codex work.

Known issues:
- Usage quotas can interrupt long autonomous tasks.
- New sessions may miss existing operating context unless explicitly routed to the OS.

Fallbacks:
- Use smaller task chunks.
- Continue in another agent only after reading the OS index and project registry.

### Antigravity

Status: partial
Category: coding agent / IDE
Last verified: 2026-06-07
Used for:
- agentic implementation
- tool exploration
- Webflow/MCP-related attempts

Successful patterns:
- Start with the OS read order.
- Give explicit setup and verification goals.
- Require it to update the tool registry after success or failure.

Known issues:
- Can miss setup context at the start of a new session.
- May ask Timtim to do manual work before checking documented fallbacks.

Fallbacks:
- Point it to ai_context/tool_registry.md and ai_context/agent_operating_protocol.md before any task.
- Ask for a diagnostic summary before accepting a manual handoff.

### OpenCode

Status: partial
Category: coding agent
Last verified: 2026-06-07
Used for:
- codebase editing
- model experiments
- lower-cost agentic work

Successful patterns:
- Read OS index first.
- Use project registry to identify repo, stack, and constraints.

Known issues:
- Model/tool setup varies by provider.
- Free models may have context or capability limits.

Fallbacks:
- Keep prompts scoped.
- Document model-specific success/failure here.

### Webflow

Status: working
Category: app
Last verified: 2026-06-07
Used for:
- TimDesign and client websites
- CMS
- layout
- interactions
- client handoff

Successful patterns:
- Treat Webflow as a core delivery environment for TimDesign.
- For automation, document exact bridge/MCP/browser workflow once verified.

Known issues:
- Browser automation and Designer access need precise setup.

Fallbacks:
- Use documented Webflow-specific skills and manual verification steps when automation is unavailable.

### Webflow MCP / Browser bridge

Status: unknown
Category: MCP
Last verified: 2026-06-07
Used for:
- intended Webflow Designer automation
- inspecting or modifying Webflow settings through an agent

Known setup:
- Needs a dedicated verified entry after the next successful connection.

Known issues:
- Agents may ask for connection details repeatedly.

Fallbacks:
- Record URL, transport type, required app/browser state, and successful test command here after verification.

### Netlify

Status: working
Category: hosting
Last verified: 2026-06-07
Used for:
- serverless functions
- deploys
- runtime config
- PWA/backend experiments

Successful patterns:
- Netlify serverless backend used successfully for Peach app work.

Maintenance notes:
- Project-specific details should live in project_registry.md.

## Maintenance log

2026-06-07: Initial registry created for cross-agent routing.
