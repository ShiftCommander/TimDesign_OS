# Knowledge Profile

Purpose: give AI assistants a compact, living map of Timtim's working knowledge so they can skip obvious explanations and move directly to decisions, implementation, critique, and next actions.

This file should be maintained by AI assistants, not manually by Timtim.

## Default assistant rule

Assume advanced knowledge by default in Timtim's core domains unless the current conversation shows otherwise. Prefer advancing the work over teaching fundamentals. When context already proves familiarity, skip definitions and give the useful next move.

## Expert / daily working level

- Premium web design for high-end Swiss real estate.
- Webflow site architecture, CMS structure, responsive design, interaction quality, client handoff, and delivery constraints.
- UX/UI critique, layout balance, spacing, typography, hierarchy, conversion logic, and perceived quality.
- Freelance business operations: positioning, offer design, client communication, pricing logic, scoping, audits, and commercial judgment.
- Premium website copy direction: clear, specific, human, commercially useful, avoiding generic AI/corporate phrasing.
- Product thinking: audience, positioning, objections, proof, offer clarity, and decision-oriented strategy.

## Advanced / active working level

- AI-assisted development workflows with Codex, Gemini, Antigravity, Cursor, and agentic IDEs.
- Prompting for coding agents, including repo-aware prompts, task scoping, verification, and handoff instructions.
- MCP concepts, connectors, local bridges, browser/DevTools needs, and tool orchestration.
- GitHub-based project context and AI-maintained operating systems.
- Webflow automation and browser-assisted implementation workflows.
- Practical model selection for autonomous coding/design/testing tasks.

## Intermediate / project-dependent

- Astro and static/PWA implementation patterns.
- Netlify serverless functions, simple API routes, runtime config, and deployment validation.
- JavaScript project structure, tests, PWA/offline behavior, and lightweight backend persistence.
- Privacy/cookie audit implementation for Swiss nLPD/RGPD-adjacent sites.
- Technical SEO and performance improvement for small-to-medium websites.

## Currently evolving

- Fully autonomous AI-maintained business operating system.
- Agentic workflows that inspect, modify, test, and push production-ready changes with low manual supervision.
- AI-managed knowledge maintenance across conversations, repositories, prompts, and business context.
- Division of work between ChatGPT memory, GitHub canonical context, Codex/Gemini agents, and project-specific instructions.

## Communication preferences relevant to knowledge handling

- Skip fundamentals when Timtim's wording or prior context shows familiarity.
- Avoid long caveats and counterexamples unless they materially change the decision.
- Give direct recommendations and concrete next actions.
- Use longer explanations when they add new insight, decision value, or implementation clarity.

## Maintenance protocol

AI assistants should update this file when one of these happens:

1. Timtim explicitly says that a topic is already known, too basic, newly learned, outdated, or no longer relevant.
2. A conversation shows repeated competent use of a concept across multiple steps.
3. A project reaches a stable state that changes what future assistants should assume.
4. A tool, workflow, or repo becomes canonical or deprecated.
5. Timtim asks for less explanation or more advanced handling in a recurring domain.

Suggested commit message:

`Update knowledge profile`

## Last AI-maintained update

2026-06-07: Created initial profile from current long-term memory and conversation context. Added explicit default: assume advanced knowledge in web design, Webflow, UX/UI, product strategy, AI tools, coding agents, MCPs, prompting, and freelance business operations unless evidence suggests otherwise.
