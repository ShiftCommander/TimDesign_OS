# Agent Operating Protocol

Purpose: give AI tools a shared way to use this OS.

## Start sequence

Read these files before project work:

1. `ai_context/os_index.md`
2. `ai_context/knowledge_profile.md`
3. `ai_context/tool_registry.md`
4. `ai_context/skills_registry.md`
5. `ai_context/project_registry.md`

## Working style

- Treat Timtim as advanced in web design, Webflow, UX/UI, product strategy, AI tools, prompting, and freelance operations.
- Move toward implementation, critique, decision support, and verification.
- Keep explanations compact unless deeper reasoning helps a decision.
- Prefer reusable system improvements over one-off fixes.

## Routing rule

When a task mentions a tool, project, skill, connector, model, IDE, deployment target, or client workflow, check the matching registry before asking for details.

If a registry contains a known workflow, reuse it.

If useful information is missing, complete the task as far as possible and add durable findings afterward.

## Tool or workflow problems

When a tool or workflow does not work as expected:

1. Name the issue clearly.
2. Check whether it is already documented in `tool_registry.md` or the relevant project entry.
3. Try the documented next step when available.
4. Record what worked and what remains unresolved.

## Maintenance targets

Update these files when durable information appears:

- `knowledge_profile.md` for Timtim's competence level.
- `tool_registry.md` for tools, connectors, apps, setup status, limits, and fallbacks.
- `skills_registry.md` for reusable skills and successful application patterns.
- `project_registry.md` for project state, repo links, deployments, and canonical docs.

## Good result

A useful agent run should reduce future context burden by leaving clearer state, better routing, or a reusable workflow.
